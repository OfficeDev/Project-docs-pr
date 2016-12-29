[comment]: # (Name:EnterpriseProjectTypeCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# <a name="name"></a>EnterpriseProjectTypeCreationInformation class

<a name="description"></a>Provides information for the creation of an enterprise project type (EPT).

## <a name="syntax"></a>Syntax

### CSOM

```C#
class EnterpriseProjectTypeCreationInformation 
```
### JSOM

```JavaScript
PS.EnterpriseProjectTypeCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.EnterpriseProjectTypeCreationInformation

http://<sitecollection>/<site>/api/ProjectServer/EnterpriseProjectTypes/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Description':'value', 
		'Id':'value', 
		'ImageUrl':'value', 
		'IsDefault':'value', 
		'IsManaged':'value', 
		'Name':'value', 
		'Order':'value', 
		'ProjectDetailPages':'value', 
		'ProjectPlanTemplateId':'value', 
		'WorkflowAssociationId':'value', 
		'WorkflowAssociationName':'value', 
		'WorkspaceTemplateName':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description for an EPT.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for an EPT.|
|<a name="ImageUrl"></a>ImageUrl|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the URL of an image that is associated with an EPT.|
|<a name="IsDefault"></a>IsDefault|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets whether an EPT is the type that all new projects should use by default.|
|<a name="IsManaged"></a>IsManaged|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets whether a project that an EPT creates is fully managed by Project Server, or is a SharePoint tasks list.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of an EPT.|
|<a name="Order"></a>Order|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets a value that indicates whether the user wants the enterprise project type to appear at the end of the list of EPTs, or whether the user wants to control where it is placed in the list.|
|<a name="ProjectDetailPages"></a>ProjectDetailPages|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|ReadOnlyCollection`1|Gets or sets the project detail page that is used as the first page in the workflow for an enterprise project type.|
|<a name="ProjectPlanTemplateId"></a>ProjectPlanTemplateId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project plan template that was created with an EPT.|
|<a name="WorkflowAssociationId"></a>WorkflowAssociationId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the workflow that is associated with an EPT.|
|<a name="WorkflowAssociationName"></a>WorkflowAssociationName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the workflow that is associated with an EPT.|
|<a name="WorkspaceTemplateName"></a>WorkspaceTemplateName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the project site template that is associated with an EPT.|

## <a name="seeAlso"></a>See Also

[EnterpriseProjectType](EnterpriseProjectType.md)<br/>
[EnterpriseProjectTypeCollection](EnterpriseProjectTypeCollection.md)<br/>
