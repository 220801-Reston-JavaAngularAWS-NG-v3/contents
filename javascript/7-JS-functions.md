## JS Functions

**Contents**

**1. JS Function Definitions**

1.1 Why Functions needed?

1.2 How to define a functions?

1.2.1 Function Declaration

1.2.2 Function Expressions

1.2.3 Arrow Functions

**2. JS Function Parameters**

2.1 Parameter Rules

**3 JS Function Invocation**

3.1 Invoking a Function as a Function

3.2 Invoking a Function as a Method

**4 JS Function Return**

**5. References**

# 1. JS Function Definitions

-   A JavaScript function is a block of code designed to perform a particular task.
-   A JavaScript function is executed when "something" invokes it (calls it).

## 1.1 Why Functions needed?

-   You can reuse code: Define the code once, and use it many times.
-   You can use the same code many times with different arguments, to produce different results.

## 1.2 How to define a functions?

They are three ways to define a function

1.  Function Declaration
2.  Function Expression
3.  Arrow function

## 1.2.1 Function Declaration

-   A JavaScript function is defined with the function keyword, followed by a **name**, followed by parentheses **()**.
-   Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).
-   The parentheses may include parameter names separated by commas:  
    **(parameter1, parameter2, ...)**
-   The code to be executed, by the function, is placed inside curly brackets: **{}**
-   Semicolons are used to separate executable JavaScript statements. Since a function **declaration** is not an executable statement, it is not common to end it with a semicolon.
-   A Function is much the same as a Procedure or a Subroutine, in other programming languages.
-   Declared functions are not executed immediately. They are "saved for later use", and will be executed later, when they are invoked (called upon).

**Syntax**

function function*name*(*parameter1, parameter2, parameter3*)

{  
// *code to be executed;*  
}

## 1.2.2 Function Expressions

-   A JavaScript function can also be defined using an **expression**.
-   A function expression can be stored in a variable:

**Example-1**

const x = function (a, b) {return a \* b};

-   After a function expression has been stored in a variable, the variable can be used as a function:

**Example-2**

const x = function (a, b) {return a \* b};  
let z = x(4, 3);

-   The function above is actually an **anonymous function** (a function without a name).
-   Functions stored in variables do not need function names. They are always invoked (called) using the variable name.

**Note:**

-   The function above ends with a semicolon because it is a part of an executable statement.

## 1.2.3 Arrow Functions

-   Arrow functions allows a short syntax for writing function expressions.
-   You don't need the function keyword, the return keyword, and the **curly brackets**.

**Example**

// ES5  
var x = function(x, y) {  
return x \* y;  
}

// ES6  
const x = (x, y) =\> x \* y;

-   Arrow functions do not have their own this. They are not well suited for defining **object methods**.
-   Using const is safer than using var, because a function expression is always constant value.

## 2. JS Function Parameters

-   Function **parameters** are listed inside the parentheses () in the function definition.
-   Function **arguments** are the real **values** received by the function when it is invoked.
-   Inside the function, the arguments (the parameters) behave as local variables.

## 2.1 Parameter Rules

-   JavaScript function definitions do not specify data types for parameters.
-   JavaScript functions do not perform type checking on the passed arguments.
-   JavaScript functions do not check the number of arguments received.

**Example**

function myFunction(a, b)

{  
return a \* b;  
}

## 3 JS Function Invocation

-   The code inside a function is not executed when the function is **defined**.
-   The code inside a function is executed when the function is **invoked**.

## 3.1 Invoking a Function as a Function

**Example**

function myFunction(a, b)

{  
 return a \* b;  
}  
myFunction(10, 2); // Will return 20

**Note**

-   This is a common way to invoke a JavaScript function, but not a very good practice.
-   Global variables, methods, or functions can easily create name conflicts and bugs in the global object.

## 3.2 Invoking a Function as a Method

-   In JavaScript you can define functions as object methods.
-   The following example creates an object (**myObject**), with two properties (**firstName** and **lastName**), and a method (**fullName**):

**Example**

const myObject = {  
 firstName:"John",  
 lastName: "Doe",  
 fullName: function () {  
 return this.firstName + " " + this.lastName;  
 }  
}  
myObject.fullName(); // Will return "John Doe"

## 4 JS Function Return

-   When JavaScript reaches a return statement, the function will stop executing.
-   If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.
-   Functions often compute a **return value**. The return value is "returned" back to the "caller":

**Example**

-   Calculate the product of two numbers, and return the result

let x = myFunction(4, 3); // Function is called, return value will end up in x  
function myFunction(a, b)

{  
return a \* b; // Function returns the product of a and b  
}

**Output**

The result in x will be:

12

## 5. References

1.  <https://www.w3schools.com/js/js_functions.asp>
2.  <https://www.w3schools.com/js/js_function_definition.asp>
3.  <https://www.w3schools.com/js/js_function_parameters.asp>
4.  https://www.w3schools.com/js/js_function_invocation.asp
