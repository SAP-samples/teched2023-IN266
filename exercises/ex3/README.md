# Exercise 3 - Configuration Steps

In this exercise, we will execute the workflow tasks. Following are the tasks that you have to execute.

## Task: Disclaimer

The first task of the workflow is the **Disclaimer** task. Please read the instructions of the **Disclaimer** task and click on **I Agree** as shown below.

![disclaimer](/exercises/ex3/images/disclaimer.png)


## Task: Confirm Systems

The next task is the **Confirm System Components** task. In this task, we will confirm the system/tenant details that will be used to set up the integration scenario. You need to select the destination (**CI: Cloud Integration Destination**) for the **SAP Cloud Integration tenant** as shown in the image below. Once that is done, click on **Confirm Systems** as shown in the above diagram. 

**NOTE:** Please **DO NOT** change any other system details that are already pre-filled.

![systems](/exercises/ex3/images/system.png)

## Task: Assign Users to required Roles

The next task is the **Assign Users to required Roles** task. In this task, you will assign the user to the roles that are required by the workflow. In the productive scenario, these users may be different. For example, in a customer environment, the BTP Administrator might be different from the S/4 Administrator. But for the hands-on session, kindly assign your user to all the roles.

**NOTE:** Click on the **Assign all roles to my user** (1) as shown below. It will automatically fill in your user details in the input fields (2) and proceed to the next task by clicking **Confirm Role Assignment** (3).

![roles](/exercises/ex3/images/roles1.png)


## Task: Create Subaccount

Now you will be presented with the first task of the integration scenario - **Create Subaccount**. 

This is an **automation task**. For more details on the different kinds of tasks and how to identify them, kindly read this [section](https://github.com/SAP-samples/teched2023-IN266/blob/main/exercises/ex0/README.md#task-execution-in-inbox). There are two automation in this task - **Create Subaccount** and **Assign Subaccount Administrator**, which will create the BTP Subaccount and assign your user as the Subaccount Admin for the same.

The parameters required for this automation task are already filled out. You **DO NOT** have to change anything. Kindly execute the automation task by clicking on the **Execute** (1) button. The automation status (2) would be displayed near the parameters section. Kindly wait for the automation to complete (In progress status will change to Success)(4). Optionally, while the automation executes, you can also read the automation documentation (5), to better understand what is going on in the background.

![create_subaccount](/exercises/ex3/images/create_subaccount.png)
![create_subaccount2](/exercises/ex3/images/create_subaccount2.png)

Once the automation is completed successfully, you can proceed to the next task by clicking on **Task Completed** button.

## Task: Assign Entitlement of SAP S/4HANA Cloud for Projects, Collaborative Project Management to Subaccount

This is also an automation task.
Kindly execute the automation and complete the task, similar to the [Create Subaccount](#task-create-subaccount) task.

# Summary

You should be able to import a project from the S/4 HANA system to the Project Collaboration application that you setup



**Continue to - [Next Steps](../ex4/README.md)**
