# Jenkins - Setup Build Jobs

**Content**

1\. Jenkins - Setup Build Jobs

2\. References

## 1. Jenkins - Setup Build Jobs

-   Let's create and run a job in Jenkins for simple **HelloWorld** in Java.

**Step 1:** Go to the **Jenkins dashboard** and click on the **New Item**.

![](media/ad64392f5031fb037d221833280067a1.png)

**Step 2:** In the next page, enter the **item name**, and select the **'Freestyle project'** option. And click OK.

-   Here, my item name is HelloWorld.

![](media/7082ec4914057857a455880796bba2a7.png)

**Step 3:** When you click OK, you will get a **configuration page**.

-   Enter the details of the project in the **Description section**.

![](media/9c1755584468cb7b277d7077558b47e3.png)

**Step 4:** On the **Source Code Management section**, select the **Git** option, and specify the **Repository URL**.

-   To do that you should have proper github setup on your system.

**To do the github setup:**

-   First, you have to create a project in java.
-   Here, I created a simple **HelloWorld** program and saved it to one folder i.e. C:\\GitRepo.
-   Compile the HelloWorld.java file.

![](media/52e0b4d00230c173686f6db474ae7d2d.png)

-   Now create a project/repository in your GitHub account and give the Repository name.
-   Here my repository name is HelloWorld.

![](media/2367b4f97d03095a122aafe2ac95ab27.png)

-   Click on **Create repository**.

![](media/8ff2c1f1636b7fc9ad0621ba2df5af50.png)

-   Your repository is created. Copy the repository URL.
-   Open the command prompt in your Windows and go to the path where your java file is created.
-   Then run the following command.

![](media/a14a37fe45c0d0f08036ef3ab09b4bb1.png)

![](media/069fde03d5821b05e547861a948e45c6.png)

-   Configure your GitHub account in your system.

![](media/72bc8244948fd6749d2d7542e720cf78.png)

![](media/fbf0520e09cc2d0b4ba57accfb7061cb.png)

-   Commit it and add the repository URL.

![](media/cc2eb9cc633627ad5b06cbbe08bf302b.png)

![](media/bab380fec50161b842babd5a08efe618.png)

-   Now, when you refresh your GitHub account, the helloWorld file will be added in your repository.

![](media/c11fa6999d664451aefc79d500a4742a.png)

**Step 5:** Add the Repository URL in the **Source Code Management** section.

![](media/26682d49b0668e330110b0f3c5ddc4c4.png)

-   You can also use a local repository.
-   And if your GitHub repository is private, Jenkins will first validate your login credentials with GitHub and only then access the source code from your GitHub repository.

**Step 6:** Now, it is time to build the code.

-   Click on "**Add build step**" and select the "**Execute Windows batch command**".

![](media/a3c77cf3c2ff97021fecf739812678b5.png)

**Step 7:** Enter the following command to compile the java code.

![](media/e867492deaf8eeb80370f4120b9aaea5.png)

![](media/23ac4e79b2b4a3510836f2e23557358f.png)

**Step 8:** Click **Apply** and then **Save** button.

**Step 9:** Once you saved the configuration, then now can click on **Build Now** option on left-hand side.

![](media/7e997146591a0224ec330a852eee8cae.png)

**Step 10:** After clicking on **Build Now**, you can see the status of the build on the Build History section.

![](media/e80abacd6957c258fe0a0a64dd3c8d82.png)

-   Once the build is completed, a status of the build will show if the build was successful or not.
-   If the build is failed then it will show in **red** color. **Blue** symbol is for success.

![](media/b332fecd7162b300eab5eacba6e549ce.png)

-   Click on the build number **\#1** in the **Build History section** to see the details of the build.

![](media/7307cdec032a833adf71ad5bbe3115d1.png)

**Step 11:** Click on **Console Output** from the left side of the screen to see the status of the build you run.

-   It should show the success message.

![](media/9e1b747d77deac5a4ceda4ce4cd791b5.png)

## 2. References

1.  https://www.javatpoint.com/jenkins-setup-build-jobs
