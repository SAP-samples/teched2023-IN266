# Exercise 3 - Configuration Steps

In this exercise, we will execute the workflow tasks. Following are the tasks that you have to execute.

### Task 1: Disclaimer

The first task of the workflow is the **Disclaimer** task. Please read the instructions of the **Disclaimer** task and click on **I Agree** button to continue to the next task.

![disclaimer](/exercises/ex3/images/disclaimer.png)


### Task 2: Confirm Systems

The next task is the **Confirm System Components** task. In this task, we will confirm the system/tenant details that will be used to set up the integration scenario. You need to select the destination (**CI: Cloud Integration Destination**) for the **SAP Cloud Integration tenant** as shown in the image below (ℹ️). Once that is done, click on **Confirm Systems** as shown in the below diagram. 

> ℹ️ Automations for the SAP Cloud Integration are triggered via [Destinations](https://help.sap.com/docs/btp/sap-business-technology-platform/create-destination) in BTP Cloud Foundry. You DO NOT have to create a destination as it is already configured for you.

**NOTE:** Please **DO NOT** change any other system details that are already pre-filled.

![systems](/exercises/ex3/images/system.png)

### Task 3: Assign Users to required Roles

The next task is the **Assign Users to required Roles** task. In this task, you will assign the user to the roles that are required by the workflow. In the productive scenario, these users may be different. For example, in a customer environment, the BTP Administrator might be different from the S/4 Administrator. But for the hands-on session, kindly assign your user to all the roles.

**NOTE 4:** Click on the **Assign all roles to my user** (1) as shown below. It will automatically fill in your user details in the input fields (2) and proceed to the next task by clicking **Confirm Role Assignment** (3).

![roles](/exercises/ex3/images/roles2.png)


### Task 4: Create Subaccount [Automation Task]

Now you will be presented with the first task of the integration scenario - **Create Subaccount**. 

This is an **automation task**. For more details on the different kinds of tasks and how to identify them, kindly read this [section](https://github.com/SAP-samples/teched2023-IN266/blob/main/exercises/ex0/README.md#task-execution-in-inbox). There are two automation in this task - **Create Subaccount** and **Assign Subaccount Administrator**, which will create the BTP Subaccount and assign your user as the Subaccount Admin for the same.

The parameters required for this automation task are already filled out. You **DO NOT** have to change anything. Kindly execute the automation task by clicking on the **Execute** (1) button. The automation status (2) would be displayed near the parameters section. Kindly wait for the automation to complete (In progress status will change to Success)(4). Optionally, while the automation executes, you can also read the documentation (5), to better understand what is going on in the background.

![create_subaccount](/exercises/ex3/images/create_subaccount3.png)
![create_subaccount2](/exercises/ex3/images/create_subaccount4.png)

Once the automation is completed successfully, you can proceed to the next task by clicking on **Task Completed** button.

### Task 5: Assign Entitlement of SAP S/4HANA Cloud for Projects [Automation Task]

This is also an **automation** task. All the parameters will be already pre-filled.
Kindly execute the automation and complete the task, similar to the [Create Subaccount](#task-4-create-subaccount-automation-task) task.

### Task 6: Establish Trust with Identity Authentication [Manual Task]

This is a **manual** task.
This task makes use of **deep links** (1) to semi-automate and ease the manual configuration steps. In this task, kindly read the **Manual instructions** (2) section and perform the steps exactly as it is described in the section. Once all the steps are performed in the target system, click on **Task Completed** (3) button, to complete the task.

**NOTE**: If you fail to perform a particular step / do not perform at all, will lead to an erroneous situation later on. The integration setup will be incomplete. Hence, it is highly encouraged to perform the steps carefully and verify the expected result based on the **Results** section of the **Manual Instructions** documentation.

![create_subaccount2](/exercises/ex3/images/setup_trust.png)


### **Next steps...**

There are 14 remaining integration tasks (listed below) that need to be performed in order to achieve the integration. Kindly, follow the instructions for the same in the CLoud Integration Automation Service Inbox and complete the integration setup.

### Task 7: Subscribe to SAP S/4HANA Cloud for Projects [Automation Task]

### Task 8: Configuration in SAP S/4HANA Cloud [Manual Task]

### Task 9: Create Communication User [Manual Task]

### Task 10: Create Communication System [Manual Task]

### Task 11: Create Communication Arrangement [Manual Task]\

### Task 12: Configuration in SAP Cloud Integration [Manual Task]

### Task 13: Maintain Credentials of Technical User [Automation Task]

### Task 14: Copy Integration Package [Automation Task]

### Task 15: Configure Integration Flow [Automation Task]

### Task 16: Configuration in SAP BTP Cockpit [Manual Task]

### Task 17: Create Destination to SAP Cloud Integration [Automation Task]

### Task 18: Create and Import Projects from SAP S/4HANA Cloud to SAP Cloud for Projects [Manual Task]

### Task 19: Create Projects in S/4HANA Cloud [Manual Task]

### Task 20: Summary

Congratulations!
You have successfully completed the technical integration setup that was required to import project data from **SAP S/4HANA Cloud** to the **SAP Cloud for Projects BTP application**. Upon successful completion of all the steps, you will be able to see the project data created in **SAP S/4HANA Cloud**  in the **SAP Cloud for Projects BTP application**.

![Complete](/exercises/ex0/images/projects.gif)


# Feedback

Please provide your valuable feedback here : [Feedback](https://url.sap/bo4esn). Alternatively, you can also scan the following QR code to provide feedback: 

![qr code](/exercises/ex0/images/qr_code.png)


**Back to [Home page](../../README.md)**
