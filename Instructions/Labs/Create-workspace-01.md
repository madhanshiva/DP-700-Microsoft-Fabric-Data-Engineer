# Lab: Prerequisite: Create a Fabric workspace

### Estimated Duration: 15 Minutes

In this exercise, you will sign up for the Microsoft Fabric and create a workspace, establishing the foundation for working within the Microsoft Fabric platform. This initial setup enables you to explore and utilize a wide range of integrated tools and services for data integration, analytics, and visualization. Creating a workspace provides a dedicated environment to organize and manage resources effectively, while also supporting collaboration across teams and projects. This foundational step is essential for understanding how to navigate and operate within Microsoft Fabric.

## Lab Objectives

In this lab, you will be able to complete the following tasks:

- Task 1: Sign up for the Microsoft Fabric
- Task 2: Create a workspace

## Task 1: Sign up for Microsoft Fabric

In this task you'll sign in to Microsoft Fabric and access the Fabric platform.

1. Open the **Microsoft Edge** browser in the LabVM, navigate to the following URL  

   ```
   https://app.fabric.microsoft.com/home?experience=fabric-developer
   ```

1. Enter below Email and click on **Submit (2)**:
 
   - Email/Username: **<inject key="AzureAdUserEmail"></inject> (1)**
 
     ![](./Images/signin-1811.png)

1. Next, provide the password below and click on **Sign in (2)**
 
   - Password: **<inject key="AzureAdUserPassword"></inject> (1)**
 
      ![Enter Your Username](./Images/siginin-pr.png)

1. On **Stay signed in?** pop-up window appears, click on **Yes**.

   ![](./Images/siginin2-pr.png)

## Task 2: Create a workspace

In this task, you will create a Fabric workspace. The workspace contains all the items needed for this tutorial, which includes lakehouse, dataflows, Data Factory pipelines, notebooks, Power BI datasets, and reports.

1. From the left menu bar, select **Workspaces (1)** and click on **+ New workspace (2)**.

   ![New Workspace](./Images/workspace-pr.png)

1. On **Create a workspace** window, enter the below name and expand the **Advanced (2)** setttings:

   - **Name:** Enter **fabric-<inject key="DeploymentID" enableCopy="false"/>** (1)

     ![New Workspace](./Images/l3-05-l2.png)

1. Under **License mode**, select the **Fabric (1)** and click on **Apply (2)**.

   ![New Workspace](./Images/dpl1-07-01.png)

   >**Note:** If the **On the Introducing task flows** window opens, select **Got it**.

## Summary

In this exercise, you have signed up for the Microsoft Fabric and created a workspace.

## Review 
In this lab, you have completed:

 + Signed up for Microsoft Fabric
 + Created a workspace

### Now, click on Next >> from the lower right corner to move on to the next lab.

![Start Your Azure Journey](./Images/nextpage-02.png)