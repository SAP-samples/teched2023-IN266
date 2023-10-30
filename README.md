[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2023-IN266)](https://api.reuse.software/info/github.com/SAP-samples/teched2023-IN266)

# IN266 - Take an Automated Approach to Configuring Integration Scenarios on SAP BTP

## Setting up Cloud for Projects using Cloud Integration Automation Service

This repository contains the material for the SAP TechEd 2023 session. 
__Session ID - IN266__

# Overview

This session introduces participants to the Cloud Integration Automation Service, and you will gain hands-on experience implementing an automated S/4HANA Cloud for Projects, Collaborative Project Management integration scenario. At the end of completing your integration configutration, you will be able to transfer a project created in SAP S/4HANA Cloud  to SAP Cloud for Projects BTP application. 

**<ins>Scenario Description</ins>**

SAP S/4HANA Cloud for projects, collaborative project management is a cloud-based solution for collaboration with all partners in projects. With SAP S/4HANA Cloud for projects, collaborative project management, you can share with all project partners crucial information and important documentation about the project.

![overview](/exercises/ex1/images/6jn.png)

**<ins>Configuration of the scenario with Cloud Integration Automation Service</ins>**

Cloud Integration Automation service eases the configuration setup in each of the target system and acts as the orchestrator for the end user. It provides a guided workflow based automated task execution. Once the configuration tasks are completed, then the you will be able to import projects from the S/4HANA Cloud to the SAP SAP Cloud for projects.

![cias_overview](/exercises/ex1/images/6jnoverview_cias.png)

## Requirements

Verify if you have access to the following systems:



- [x] __SAP S/4HANA :__ [SAP S/4HANA System](https://my407161.s4hana.cloud.sap/ui)

- [x] __SAP BTP :__ [SAP BTP System](https://emea.cockpit.btp.cloud.sap/cockpit?idp=tdct3ched2.accounts.ondemand.com#/globalaccount/afd3e49e-9bd3-41b8-ba49-ea7679f9e677/subaccount/576991fa-34c8-48a9-a661-6c278d2ed1db/subaccountoverview%20)

- [x] __CI :__ [Cloud Integration](https://in266-gkd289xc.integrationsuite.cfapps.eu10-002.hana.ondemand.com/)

- [x] __CIAS Application :__ [CIAS](https://cias-teched-b7x9jgv5.cias-preprod.cfapps.eu10.hana.ondemand.com)

## Exercises

List of steps to be followed in order to do the integration setup for Cloud for Projects

- [CIAS Overview](exercises/ex0/README.md)
- [Integration Scenario Overview](exercises/ex1/README.md)
- [Exercise 1 - Generation of workflow](exercises/ex2/README.md)
- [Exercise 2 - Configuration Setup](exercises/ex3/README.md)    
- [Next Steps](exercises/ex4/)


**IMPORTANT**

Your should login to the above application/tenants with the below user credentials assigned to you. 

For Example:
> _Username:_ IN266-0XX@education.cloud.sap
```
Note:
    - XX will the student code assigned to you during the hands on exercise
    - Password will be shared during the session 
```

## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
