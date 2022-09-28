# GitHub Setup for Jenkins

**Content**

1\. GitHub Setup for Jenkins

2\. Integrating Jenkins with GitHub

3\. References

## 1. GitHub Setup for Jenkins

-   Jenkins is a CI (Continuous Integration) server and this means that it needs to check out source code from a source code repository and build code.
-   Jenkins has outstanding support for various source code management systems like Subversion, CVS etc.
-   Github is the fast becoming one of the most popular source code management systems.
-   It is a web based repository of code which plays a major role in DevOps.

To do the GitHub setup, make sure that internet connectivity is present in the machine where Jenkins is installed.

-   In the Home screen of the Jenkins (Jenkins Dashboard), click on the **Manage Jenkins** option on the left hand side of the screen.

![](media/e32ef1caac8d335e518abb8caca64971.png)

-   Now, click on the **Manage Plugins** option.

![](media/a9f68377618a858f0b6a363ae6eb09a2.png)

-   In the next page, click on the "**Available tab**".

![](media/6fb4b886cec470a96a32c55d5057f859.png)

-   The "Available" tab gives a list of plugins which are available for downloading. In the **Filter tab** type, type the "**Git Plugin**".
-   Select the **Git Plugin**.
-   Click on the "**install without restart**".
-   The plugin will take some time to finish downloading depending on your internet connection, and will be installed automatically.
-   You can also click on "**Download now and install after restart**" button in which the git plugin is installed after restart.
-   If you already have the Git plugin installed then go to "**Installed**" tab and in filter option type Git plugin.

![](media/c09d98bd30c6ddfa6368be517f3652fd.png)

-   Once all the installations are completed, restart Jenkins by giving the following command in the browser. <http://localhost:8080/jenkins/restart>
-   After Jenkins is restarted, Git will available as an option while configuring jobs.

## 2. Integrating Jenkins with GitHub

Let's see the process of integrating GitHub into Jenkins in a windows system.

-   First create a new job in Jenkins, open the **Jenkins Dashboard** and click on "**create new jobs**".

![](media/5418d62f8f6c3b67221210d89e15aa02.png)

-   Now enter the item name and select the job type. For example, item name is **javaTpoint**" and job type is "**Freestyle project**".
-   Click on **OK**.

![](media/82b4c73a9f47042b74da2b69e39cf4e8.png)

-   Once you click OK, the page will be redirected to its **project configuration**. Enter the project information:

![](media/a42c64022b2c8a692cffd9598e1df2c6.png)

-   Now, under the "Source Code Management" you will see the Git option, if your **Git** plugin has been installed in Jenkins:

![](media/da6e80c53e66746284f68bc91236cb01.png)

![](media/ecad303e64d7df981f035ccf0e5efa65.png)

-   Enter the Git repository URL on the "Repository URL" option to pull the code from GitHub.

![](media/5397a13272f80091d27f7f1354321ea5.png)

-   You might get an error when first time you enter the repository URL. For example:

![](media/4a8084ee8f2a397ffd47ebed9c41c37e.png)

-   This happens if you don't have Git installed in your system.
-   To install the Git in your system, download the appropriate Git setup according to your operating system.
-   I am installing for windows. Once the download is completed, install the Git.

![](media/f1546a810928231cde8685e63b9612d4.png)

-   Complete the following instructions to install the Git:

![](media/9e9137a8415dbf9ac29cb5eb349f4ad5.png)

-   You can execute Git repositories in your Jenkins once Git has been installed on your system.
-   To check if the Git has been installed on your system, open the command prompt, type Git and press Enter.

![](media/52479479da81b3c4a225eeda9aa345f5.png)

In the above screen, you observe that syntax and different options come up for Git. This means that Git has been installed in your machine.

-   Now try to add the Git URL into Jenkins.
-   Git is now successfully configured on your system.

## 3. References

1.  https://www.javatpoint.com/github-setup-for-jenkins
