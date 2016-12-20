[comment]: # (Name:EnterpriseProjectTypeCreationInformation)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# EnterpriseProjectTypeCreationInformation

Provides information for the creation of an enterprise project type (EPT).



## Syntax

### CSOM

```C#
Class EnterpriseProjectTypeCreationInformation 
```
### JSOM

```
PS.EnterpriseProjectTypeCreationInformation
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/?????
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description for an EPT.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for an EPT.|
|ImageUrl|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the URL of an image that is associated with an EPT.|
|IsDefault|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets whether an EPT is the type that all new projects should use by default.|
|IsManaged|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets whether a project that an EPT creates is fully managed by Project Server, or is a SharePoint tasks list.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of an EPT.|
|Order|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets a value that indicates whether the user wants the enterprise project type to appear at the end of the list of EPTs, or whether the user wants to control where it is placed in the list.|
|ProjectDetailPages|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|ReadOnlyCollection`1|Gets or sets the project detail page that is used as the first page in the workflow for an enterprise project type.|
|ProjectPlanTemplateId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project plan template that was created with an EPT.|
|WorkflowAssociationId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the workflow that is associated with an EPT.|
|WorkflowAssociationName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the workflow that is associated with an EPT.|
|WorkspaceTemplateName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the project site template that is associated with an EPT.|






## See Also
