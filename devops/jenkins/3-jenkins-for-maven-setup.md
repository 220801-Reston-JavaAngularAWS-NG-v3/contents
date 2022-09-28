# Maven Setup for Jenkins

**Content**

1\. Maven

2\. Downloading Maven

3\. Setting up Java and Maven in Jenkins

4\. References

## 1. Maven

-   **Maven** is a powerful project management and comprehension tool that provides complete build life cycle framework to assist developers.
-   It is based on the concept of a POM (Project Object Model) that includes project information and configuration information for Maven such as construction directory, source directory, test source directory, dependency, Goals, plugins etc.
-   Maven is build automation tool used basically for Java projects, though it can also be used to build and manage projects written in C\#, Scala, Ruby, and other languages.
-   Maven addresses two aspects of building software: 1st it describes how software is build and 2nd it describes its dependencies.

## 2. Downloading Maven

-   The official website for Apache Maven is <https://maven.apache.org/download.cgi>. Click on the given link to **download** the Maven.
-   When you click on the given link, you will get the home page of the official Maven website as given below:

![](media/905cda1fee66b0ccf1571dad6badd7ed.png)

-   Go to the **files** section and **download** the Maven by the given link for **Binary zip archive file.**

![](media/bdd5ca8bacfce80097fd0b875ea46682.png)

-   Once the file is downloaded, extract the file into your system.

## 3. Setting Up Java and Maven in Jenkins

-   First of all, you have to set the JAVA_HOME and MAVEN_HOME environment variable in your system.
-   To set the JAVA_HOME and MAVEN_HOME path, [**click here**](https://www.mkyong.com/maven/how-to-install-maven-in-windows/).
-   You can verify that the JAVA_HOME environment variable is properly configured or not by using the following command:

![](media/074c11abd9b37fb746f80b8c2e0d64c3.png)

![](media/bca6bab5f7a7f98c52e3e3d4effb7f6e.png)

-   Similarly, you can verify that the JAVA_HOME environment variable is properly configured or not by using the following command:

![](media/fb307647c47510478738f9a29ecce9ce.png)

![](media/543624559a6b153c15f638b3d21feb3b.png)

-   Now, in the **Jenkins dashboard** (Home screen) click on **manage Jenkins** from the left-hand side menu.

![](media/298cd677075c144c98afb1d85ac334b2.png)

-   Click on "**Global Tool Configuration**" option.

![](media/29abec788faeb49c949806576930e472.png)

-   To configure Java, click on "**Add JDK**" button in the JDK section.

![](media/e93a0986fd696735ccfb113d6bd6e9d6.png)

-   Give a **Name** and **JAVA_HOME** path, or check on **install automatically** checkbox.

![](media/8fb6af728bcb735580e3479070c6ebd8.png)

-   And now, to configure Maven, click on "**Add Maven**" button in the Maven section, give any **Name** and **MAVEN_HOME** path or check to install automatically checkbox.

![](media/10fe1fc18dafa3b4f599d8bb95a26971.png)

-   Then, click on the "**Save**" button at the end of the screen.
-   Now, you can create a job with the Maven project. To do that, click on the **New Item** option or **create a new job** option.

![](media/f3a53bece026905a4356ee78e610bafe.png)

-   Enter the **Item Name** and select the **Maven Project**. Click OK.

![](media/51bec8ea099b85fbdfc896029a07e4b8.png)

![](media/f79be4f6cc4cbff50ba03d1685f5e672.png)

-   Now configure the job. Give the description and in the **Source Code Management** section, select the required option.

![](media/8209f3aad8747a853698c117bdb9d242.png)

-   In the **Build Triggers** section, there are multiple options, select the required one.
-   Add the pom.xml file's path in the **Root POM** option in **Pre Steps** Section.

![](media/7acb7ba145486c729dd6ded2d8090134.png)

-   Configure the other fields as per your requirement and then click on the **Save** button.

## 4. References

1.  https://www.javatpoint.com/jenkins-maven-setup
