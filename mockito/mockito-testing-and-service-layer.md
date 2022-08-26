## Mockito

**Table of Contents**

**1. Maven Dependencies**

**2. Setup**

2.1. MockitoExtension

2.2. MockitoAnnotations.openMocks() method

2.3. @Mock vs @InjectMocks

**3. JUnit Tests using Mockito**

3.1. Service Layer Tests

3.2. Service Layer Class

3.3. Dao Layer Class

**4. Conclusion**

## 1. Maven Dependencies

-   Learn to write **unit tests** **for the service layer** using JUnit 5 and Mockito testing frameworks.
-   Let’s add the JUnit 5 (jupiter) and *mockito* dependencies:

\<**dependency**\>

\<**groupId**\>org.junit.jupiter\</**groupId**\>

\<**artifactId**\>junit-jupiter-engine\</**artifactId**\>

\<**version**\>5.8.1\</**version**\>

\<**scope**\>test\</**scope**\>

\</**dependency**\>

\<**dependency**\>

\<**groupId**\>org.mockito\</**groupId**\>

\<**artifactId**\>mockito-core\</**artifactId**\>

\<**version**\>2.21.0\</**version**\>

\<**scope**\>test\</**scope**\>

\</**dependency**\>

**Note**

1.  **junit-jupiter-engine** is the main JUnit 5 library.
2.  **junit-platform-launcher** is used with the Maven plugin and IDE launcher.

## 2. Setup

-   In this example, we are unit testing primarily two classes EmployeeManager and EmployeeDao. As the name implies, the manager class represents the service layer, and dao class interacts with the database.
-   EmployeeManager class has a dependency on EmployeeDao and delegate method calls to get the data which is finally returned to controller classes.
-   To test the methods in EmployeeManager, we can create a JUnit test class *TestEmployeeManager* in below given two ways:

## 2.1. *MockitoExtension*

-   To process Mockito annotations with JUnit 5, we need to use *MockitoExtention* that automatically initializes all the objects annotated with @Mock and @InjectMocks annotations.

**@ExtendWith(MockitoExtension.class)**

public class TestEmployeeManager {

@InjectMocks

EmployeeManager manager;

@Mock

EmployeeDao dao;

*//tests*

}

## 2.2. *MockitoAnnotations.openMocks()* method

-   If we are not using the MockitoJUnitRunner class approach, then we can use the static method MockitoAnnotations.initMocks(). This method also, upon initialization of junit tests, initializes the mock objects.

**TestEmployeeManager.java**

public class TestEmployeeManager {

@InjectMocks

EmployeeManager manager;

@Mock

EmployeeDao dao;

@Before

**public** **void** init() {

MockitoAnnotations.openMocks(**this**);

}

*//tests*

}

## 2.3. *@Mock* vs *@InjectMocks*

-   The **@Mock** annotation creates a mock implementation for the class it is annotated with.
-   **@InjectMocks** also creates the mock implementation and additionally injects the dependent mocks that are marked with the annotations @Mock into it.
-   In the above example, we have annotated EmployeeManager class with @InjectMocks, so mockito will create the mock object for EmployeeManager class and inject the mock dependency of EmployeeDao into it.

## 3. JUnit Tests using Mockito

-   Let’s see a few examples of writing the junit tests to *unit test the service layer and* *DAO layer* methods using mock objects created with mockito.
-   A few example methods could be for *getAllEmployees()* returning a list of EmployeeVO objects, *getEmployeeById(int id)* for returning an employee by given id; and createEmployee() for adding an employee object and return void.

## 3.1. Service Layer Tests

**TestEmployeeManager.java**

**import** **static** org.junit.Assert.assertEquals;

**import** **static** org.mockito.Mockito.times;

**import** **static** org.mockito.Mockito.verify;

**import** **static** org.mockito.Mockito.when;

**import** java.util.ArrayList;

**import** java.util.List;

**import** org.junit.Before;

**import** org.junit.Test;

**import** org.junit.runner.RunWith;

**import** org.mockito.InjectMocks;

**import** org.mockito.Mock;

**import** org.mockito.MockitoAnnotations;

**import** com.howtodoinjava.demo.dao.EmployeeDao;

**import** com.howtodoinjava.demo.model.EmployeeVO;

**import** com.howtodoinjava.demo.service.EmployeeManager;

**public** **class** TestEmployeeManager {

@InjectMocks

EmployeeManager manager;

@Mock

EmployeeDao dao;

@Before

**public** **void** init() {

MockitoAnnotations.initMocks(**this**);

}

@Test

**public** **void** getAllEmployeesTest()

{

List\<EmployeeVO\> list = **new** ArrayList\<EmployeeVO\>();

EmployeeVO empOne = **new** EmployeeVO(1, "John", "John", "howtodoinjava@gmail.com");

EmployeeVO empTwo = **new** EmployeeVO(2, "Alex", "kolenchiski", "alexk@yahoo.com");

EmployeeVO empThree = **new** EmployeeVO(3, "Steve", "Waugh", "swaugh@gmail.com");

list.add(empOne);

list.add(empTwo);

list.add(empThree);

when(dao.getEmployeeList()).thenReturn(list);

*//test*

List\<EmployeeVO\> empList = manager.getEmployeeList();

assertEquals(3, empList.size());

verify(dao, times(1)).getEmployeeList();

}

@Test

**public** **void** getEmployeeByIdTest()

{

when(dao.getEmployeeById(1)).thenReturn(**new** EmployeeVO(1,"Lokesh","Gupta","user@email.com"));

EmployeeVO emp = manager.getEmployeeById(1);

assertEquals("Lokesh", emp.getFirstName());

assertEquals("Gupta", emp.getLastName());

assertEquals("user@email.com", emp.getEmail());

}

@Test

**public** **void** createEmployeeTest()

{

EmployeeVO emp = **new** EmployeeVO(1,"Lokesh","Gupta","user@email.com");

manager.addEmployee(emp);

verify(dao, times(1)).addEmployee(emp);

}

}

The unit test results will be like this.

Spring boot mockito junit example

## 3.2. Service Layer Class

**EmployeeManager.java**

**import** java.util.List;

**import** org.springframework.beans.factory.annotation.Autowired;

**import** org.springframework.stereotype.Service;

**import** com.howtodoinjava.demo.dao.EmployeeDao;

**import** com.howtodoinjava.demo.model.EmployeeVO;

@Service

**public** **class** EmployeeManager

{

@Autowired

EmployeeDao dao;

**public** List&lt;EmployeeVO&gt; getEmployeeList() {

**return** dao.getEmployeeList();

}

**public** EmployeeVO getEmployeeById(**int** id) {

**return** dao.getEmployeeById(id);

}

**public** **void** addEmployee(EmployeeVO employee) {

dao.addEmployee(employee);

}

}

## 3.3. Dao Layer Class

**EmployeeDao.java**

**package** com.howtodoinjava.demo.dao;

**import** java.util.ArrayList;

**import** java.util.HashMap;

**import** java.util.List;

**import** java.util.Map;

**import** org.springframework.stereotype.Repository;

**import** com.howtodoinjava.demo.model.EmployeeVO;

@Repository

**public** **class** EmployeeDao {

**private** Map\<Integer, EmployeeVO\> DB = **new** HashMap\<\>();

**public** List\<EmployeeVO\> getEmployeeList()

{

List\<EmployeeVO\> list = **new** ArrayList\<\>();

**if**(list.isEmpty()) {

list.addAll(DB.values());

}

**return** list;

}

**public** EmployeeVO getEmployeeById(**int** id) {

**return** DB.get(id);

}

**public** **void** addEmployee(EmployeeVO employee) {

employee.setEmployeeId(DB.keySet().size() + 1);

DB.put(employee.getEmployeeId(), employee);

}

**public** **void** updateEmployee(EmployeeVO employee) {

DB.put(employee.getEmployeeId(), employee);

}

**public** **void** deleteEmployee(**int** id) {

DB.remove(id);

}

}

## 4. Conclusion

-   This mockito taught us to unit test the service layer using JUnit and Mockito. We learned to setup the test class and to write JUnit tests.

## References

1.  https://howtodoinjava.com/spring-boot2/testing/spring-boot-mockito-junit-example/
2.  https://www.baeldung.com/mockito-junit-5-extension
