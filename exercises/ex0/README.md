# Exercise 1: Getting Started

In this exercise, you will get an overview of the capabilities of CIAS which will be helpful for the successful completion of the hands-on exercise.

## Overiew

The Cloud Integration Automation Service homepage consists of three tiles -:

### 1. Plan for Integration

This section contains the integration scenarios that are onboarded into CIAS. You can choose based on the Cloud or Hybrid setup and generate a workflow. It has an integrated landscape discovery that prompts the customer to select the system that they own. In the case of a fully automated scenario, you can run the whole setup in the background mode as well.

![plan](/exercises/ex0/images/overview.png)

### 2. My Inbox

The Inbox feature in Cloud Integration Automation Service supports workflow execution by automatically delegating tasks based on user authorization and scope. Its integrated parameter management system minimizes errors and ensures seamless integration by pre-populating task parameters from preceding tasks. Furthermore, its automation capabilities, eliminate manual operations, thereby boosting efficiency and reducing potential human errors.

![inbox](/exercises/ex0/images/inbox.jpg)

#### <ins>Task Execution in Inbox</ins>

There are 2 kinds of workflow tasks that a user might encounter while executing a workflow in Inbox.

#### 1. Automation task

Automation tasks are those that perform the configuration automatically based on the parameters (1) that are provided. The easiest way to identify an automation task is to look for the **Execute Task** (2) button at the footer of the Inbox. To execute an automation task, please provide the parameters (if not pre-filled) and then press the **Execute Task** button. This will trigger the automation and the configuration will be performed. The successful completion of the configuration will be indicated by the Success badge (3) near the parameter section. The attached manual documentation at the bottom serves as an alternative to performing the automation manually. 

**For the hands-on session, in case of an error, please reach out to colleagues for support.**

![Automation task](/exercises/ex0/images/automation-task.png)


### 3. Scenario Monitoring

Scenario monitoring provides a comprehensive view of the current integration processes being executed within this tenant. It sytematically catalogues each integration scenario, detailing the tasks undertaken and the progress achieved for each. This feature, part of CIAS (Cloud Integration Automation Service), is crucial for maintaining visibility and control over integration operations.

![seo](/exercises/ex0/images/seo.png)

**Continue to - [Exercise 2 - Generate a workflow](../ex2/README.md)**
