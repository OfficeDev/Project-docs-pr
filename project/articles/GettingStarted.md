#From 0 to 60 with Project Online
####Developing Applications on Hosted Project
 
An application developer can customize a Project Online site (SharePoint hosted) using standalone applications and/or Project Add-ins. A wealth of applications is possible that range from addressing needs of those involved in a project to PMO support functions:

- Streamlined timecard data entry for workers
- Efficient timecard authorization for supervisors
- Oversight of permits (procurement and status) needed for a project
- Status/Health check of active projects
- Issues report
- Change Management Status report

Project Online includes API support to accommodate the following scenarios:

######Project (SharePoint) Hosted Add-In:

- Code (JavaScript, HTML, CSS) is hosted in Project Online
- Assets are downloaded to the browser and executed against SharePoint online
- Business logic is in JavaScript 
- Access data is in/stored in Project Online or SharePoint
  - Custom Fields
  - Lists 
  - etc.
 
  
######Project (SharePoint) Provider Hosted Add-In:

- Code exists on a site external to the Project Online site
- External site can be 
  - Another SharePoint site
  -	Web App/Service built on any platform
  - etc.
- External site contains business logic
- Browser is redirected from Project Online to external site with access tokens to Project Online
- External site can make calls to SharePoint and Project Online

######External/Standalone Add-in:

- User executes an application on their device
- Application authenticates and calls Project Online APIs directly



| Type of application |API |Target Environment|Application Examples
|:------|:------|:------|:------|
| Project Hosted| <ul><li>JSOM (JavaScript Object Model)</li><li>REST</li></ul> | Browser | <ul><li> Timecard entry</li><li>Timecard approval</li><li>Project Status</li><li>Issues Report</li></ul> |
| Project Provider Hosted | <ul><li>CSOM client library</li><li>REST</li></ul>  | Azure Website/App<br/> Non-Windows environment (LAMP, etc.) | <ul><li>External timesheet validator</li><li>>Project Importer</li></ul> |
| External/Standalone | <ul><li>CSOM client library</li><li>REST</li></ul> | <ul><li>CSOM – Any .NET supported platform</li><li>>REST – Any platform </li></ul>| <ul><li>Timecard entry</li><li>Migration of projects to a new site</li><li>Change Management Status</li></ul> |



## What does it take to start developing applications for Project Online?

The common items needed for developing Project Online applications are a Project Online account and test data--projects and project-related information that include assignments, tasks, resources, and custom fields. A development environment is needed as well, but specifics of the development environment depend on the type of application and the API interface needed for the application. The next few sections describe development needs for the three API interfaces.

The reference documentation describes the object model that is common for all three interfaces, as well as an entity map that shows relations among the object model components.

## Project Hosted Add-In development environment

An Hosted Add-in is an add-in that resides on the server and is downloaded to a browser for runtime execution. Hosted Add-ins can use the JSOM or REST interfaces and are written in JavaScript. Project Online provides references to the JSOM library for runtime execution. Assuming development is on a Windows platform, the needed resources follow:

-	Visual Studio 2015—preferred, or Visual Studio 2013 
-	Office development tools for Visual Studio
-	JavaScript language
-	Visit https://github.com/OfficeDev/Project-JSOM-Copy-Work-Packages  for a sample application. 
You can download and run the sample in a few easy steps:
  1.	Download and open the sample application
  2.	Update the siteURL in the Properties window <br />
       Project Online examines both the application scope of the Add-in and the user permissions to govern access to information on the Project Online host. If access is explicitly denied in either or both settings, Project Online denies access to the information. Otherwise, access is granted.
  3.	Enable sideloading on your site. See the "Configuring Project Online for App Development" article for more information. 
  4.	Build the project.
  5.	Run the project.

## Project Provider Hosted application development environment

Provider hosted add-ins  are applications written and residing on any web platform.  They can connect and perform data operations using the REST (or CSOM for Microsoft platforms) API. Any language and environment that supports the REST interface can be used for development. 

An example of the Windows development environment for this type of application includes the following items:

An example of the Windows development environment for this type of application includes the following items:

-	Visual Studio 2015 preferred, Visual Studio 2013 is supported as well
-	Microsoft Office Development Tools for Visual Studio (supplied with Visual Studio 2015 Professional and Enterprise editions)
-	.NET Framework 4.0 or newer
-	SharePointOnline CSOM package (for CSOM calls)
-	A programming language, such as C# 
-	Visit https://github.com/OfficeDev/Project-Add-in-REST-BasicDataOperations for working sample scripts. <br /> 
  You can run the sample in a few steps:
  1.	Download and open the sample application
  2.	Update the SiteURL in the Properties window <br /> 
     Project Online examines both the application scope of the Add-in and the user permissions to govern access to information on the Project Online host. If access is explicitly denied in either or both settings, Project Online denies access to the information. Otherwise, access is granted.
  3.	Enable sideloading on your site. See the Configuring Project Online for App Development article for more information. 
  4.	Build the project.
  5.	Run the project.

## External/standalone application development environment

A standalone application can call Project Online using the Client Side Object Model (CSOM) or REST to communicate with Project Online to create, retrieve, update, and delete information residing on the server. This is a standalone client application that depends on the user access level to run. 

An example of the Windows development environment for this type of application includes the following items:

- 	Visual Studio 2015 preferred, Visual Studio 2013 is supported as well
- 	Microsoft Office Development Tools for Visual Studio (supplied with Visual Studio 2015 Professional and Enterprise editions)
- 	.NET Framework 4.0 or newer
-	SharePointOnline CSOM package (for CSOM calls)
-	A programming language, such as C# 
-	Visit https://github.com/OfficeDev/Project-CSOM-Read-Enterprise-CustomFields for a sample application. 

    You can run the sample in a few steps:

  1.	Download the sample application
  2.	Make a couple of changes to access your Project Online site—the site name, user account, and password.<br />Ensure the user has access to all projects. Project Online uses user permissions to govern access to information in the data store.
  3.	Add the SharePoint assembly to the references using the Nuget Package Manager Console, available from the Tools menu.<br /> 
  Type in the following command in the Nuget console:

        Install-Package Microsoft.SharePointOnline.CSOM

  4.	Build the project.
  5.	Run the project.

# Next Steps

Each sample application has an article to explain the highlights of working with the individual Project API. The articles appear in the following list, along with a few articles that describe the entity relationships, information on the query system, and accessing Custom Fields. 

-	Developing a Project Online Application Using the Client Side Object Model
-	Developing a Project Online Add-in Using the JavaScript Object Model
-	Developing a Project Online Application Using the REST interface.
-	Custom Fields – How to navigate and access custom Fields
-	Planning User Access 



