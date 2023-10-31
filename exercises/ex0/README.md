# Exercise 1: Getting Started

In this exercise, you will get an overview of the capabilities of CIAS which will be helpful for the successful completion of the hands-on exercise.

## Overiew

The Cloud Integration Automation Service homepage consists of three tiles -:

### 1. Plan for Integration

This section contains the integration scenarios that are onboarded into CIAS. You can choose based on the Cloud or Hybrid setup and generate a workflow. It has an integrated landscape discovery that prompts the customer to select the system that they own. In the case of a fully automated scenario, you can run the whole setup in the background mode as well. 

**Note: In the next exercise, we will take a deeper look into the functions of the Planning app.**

![plan](/exercises/ex0/images/overview.png)

### 2. My Inbox

The Inbox feature in Cloud Integration Automation Service supports workflow execution by automatically delegating tasks based on user authorization and scope. Its integrated parameter management system minimizes errors and ensures seamless integration by pre-populating task parameters from preceding tasks. Furthermore, its automation capabilities, eliminate manual operations, thereby boosting efficiency and reducing potential human errors.

![inbox](/exercises/ex0/images/inbox.jpg)

The following are the different sections within the Inbox -
1. **Task Instructions** - This tab displays the documentation for the current task. It also contains parameters and the ability to execute automation.
2. **Task Overview** - This tab provides a hierarchical view of all the tasks and their documentation for the complete workflow. **Note:** This view is to be used only for reference. Current task instructions will be available in the **Task Instructions** tab only.
3. **Comments** - This tab provides the ability to add comments. Comments can be used as a medium to communicate with other workflow users (for the current workflow).
4. **System Access** - This tab provides information about the current system for which the task instructions are displayed in the **Task Instructions** tab.
5. **Assigned To** - This tab provides workflow user information for the current task.
6. **Support information** - This tab contains metadata information about the workflow.
7. **Logs** - In the case of automation tasks, after triggering the automation, the logs can be seen in the logs tab. Individual automation logs can be visualized from the log button next to individual parameter sections. For aggregate logs, please click the logs button at the top right of the screen.

![task overview](/exercises/ex0/images/task_overview.png)

#### <ins>Task Execution in Inbox</ins>

There are 2 kinds of workflow tasks that a user might encounter while executing a workflow in Inbox.

#### 1. Automation task

Automation tasks are those that perform the configuration automatically based on the parameters (1) that are provided. The easiest way to identify an automation task is to look for the **Execute Task** (2) button at the footer of the Inbox. To execute an automation task, please provide the parameters (if not pre-filled) and then press the **Execute Task** button. This will trigger the automation and the configuration will be performed. The successful completion of the configuration will be indicated by the Success badge (3) near the parameter section. The attached manual documentation at the bottom serves as an alternative to performing the automation manually.  After successful completion of the automation (Success badge), click on the **Task Completed** (4) button to proceed to the next task.

**For the hands-on session, in case of an error, please reach out to colleagues for support.**

![Automation task](/exercises/ex0/images/automation_task.png)

#### 2. Manual task

Manual tasks are those that require manual setup of the configuration steps. The easiest way to identify an automation task is to look for the absence of the **Execute Task** button at the footer of the inbox. The manual tasks may or may not contain a **parameter** (1) section. To successfully complete a manual task, please perform the configuration steps manually. There will be **deep links** (2) embedded in the documentation itself. You can click on the link and follow the documentation to complete the steps. In case of mandatory parameters that are not pre-filled, kindly fill the same after completing the configuration manually. After completion of the configuration, click on the **Task Completed** (3) button to proceed to the next task.

![Manual task](/exercises/ex0/images/manual_task.png)


### 3. Scenario Monitoring

Scenario monitoring provides a comprehensive view of the current integration processes being executed within this tenant. It systematically catalogs each integration scenario, detailing the tasks undertaken and the progress achieved for each. This feature, part of CIAS (Cloud Integration Automation Service), is crucial for maintaining visibility and control over integration operations.

![seo](/exercises/ex0/images/seo.png)

Let us now proceed to the next exercise, where we will generate the workflow.

**Continue to - [Exercise 2 - Generate a workflow](../ex2/README.md)**
