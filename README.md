# Notes on Azure DevOps

## What is DevOps?
_DevOps_ is the combination of cultural philosophies, practices, and tools that increases an organization's ability to deliver applications and services at high velocity when compared to traritional development practices. [*Source*](https://aws.amazon.com/devops/what-is-devops/)
<br>
In traditional development approach, there are separate teams for development, testing, deployment and management of the application. And these teams were isolated from each other. But now in DevOps, all these teams work together resulting in faster development and better product.
Now the developers upload the code into source control and commit it, the testers build and test it. If there are eny defects/failed test cases, the developers can fix it and update the repository. The developers, testers and operations can work together as a team and efficiency is improved. 

## What is Azure?
Azure is a cloud computing platform from Microsoft. It is used by developers, IT professionals and companies to build, deploy, and manage applications.
It provides a wide range of services like building virtual machines, data storage, cloud hosting, version control, building, testing and deployment of applications to name a few.

### Features:

 1. **On demand provisoning**: Use a particular resource in the cloud as per requirement and setup takes only few seconds. Once resources are no longer needed, we can simply stop using them and there are no overheads.
 2. **Hassle-free scalibility**: Upscale or downscale our infrastructure as needed, we can increase the amount of resources takes a few minutes and we don't have to worry about additional setup. At the same time, when we have to downscale, there is no problem of wasted resources as they are returned to the provider.
 3. **Pay as you go**: If we need to use more resources (upscale) then we pay accordingly, but when we downscale, we need to pay for only what we are using. More over most cloud platforms require payment as per hourly/monthly basis, so we need to pay for only the length of time we use these services.
 4. **Abstract resources**: While working in Azure, we don't need to worry about the harware confguration, malfuntion, driver issues, security patches, server cooling, software updates as all these are managed by the Azure platform. All we need ti worry is about our project.
 5. **Flexible development**: There is no specific programming language/ development platform needed to work with Azure. We can use JAVA, maven, Python, Machine learning, JavaScript, etc to develop our application.
 6. **Usage is measurable**: Every thing used in Azure, like how usage time, computation, etc are measurable.

## Working on Azure Platform

Open [https://dev.azure.com](https://dev.azure.com) on your browser and log in with a microsoft account. Afte logging in the first thing we can do is create a new project, by clicking on the 'New Project' button. For first time users of Azure, we have to create an organization first. 
<br>
![new project by pritesh ranjan](resources/new_project.jpg?raw=true)

Now to create a new project, fill in the project name (any name of our choice) , an optional description and finally project visiiblity, that is public or private. There are some additional settings too, which allow us to select the version control type (default is git) and work item process like agile, etc.
After creating a new project, we can see buttons for Boards, Repos, Pipelines, Test Plans and Atrefacts. We will discuss this one by one and also do hands-on simultanously.
<br>
![image by pritesh ranjan](resources/inside_project.jpg?raw=true)

<br>
## Components of Azure DevOps

### Azure Boards <img style="float: left;" src="resources/boards-icon-80.png?raw=true">
 It is a Azure service where project managers and developers can create requiremnets, tasks and assign work for the software development projects.
 It has a rich set of capabilities including native support for Scrum and Kanban, customisable dashboards and integrated reporting.
 It can be used to create epics, features, product backlogs, report bugs, etc.
![image by pritesh ranjan](resources/azure_boards.jpg?raw=true)
As we can see in the image above, one can easily add/create epics, features, user stories, bugs, etc through simple clicks.

 **Key features:**
 1. *Work Items*: Used to track the progress of any work on Azure Boards
 2. *Boards*: Each project comes with a pre-configured Kanban board for managing the flow of the work. They are highly customizable and allow the addition of columns for each team and project.
 3. *Backlogs*: Helps understand the relationships between workitems and prioritize them accordingly
 4. *Sprints*: A sprint is a small-time window in which one can complete parts of the project, that is certain work items related to the project.
 5. *Dashboards*:  We can see and manage the current state and track the overall progress of our project.
 
### <img style="float: left;" src="resources/repos-icon-80.png?raw=true"> Azure Repos
This is line for azure repo. This is line for azure repo. This is line for azure repo. This is line for azure repo. 
This is line for azure repo. This is line for azure repo. This is line for azure repo. This is line for azure repo. 

### Azure Test Plans <img align="right" src="resources/test-plans-icon-80.png?raw=true">
This is line for azure repo. This is line for azure repo. This is line for azure repo. This is line for azure repo. 
This is line for azure repo. This is line for azure repo. This is line for azure repo. This is line for azure repo. 

### <img align="right" src="resources/artifacts-icon-72.png?raw=true"> Azure Artifacts
This is line for azure repo. This is line for azure repo. This is line for azure repo. This is line for azure repo. 
This is line for azure repo. This is line for azure repo. This is line for azure repo. This is line for azure repo. 

### Azure Pipelines



