[comment]: # (Name:EnterpriseProjectType)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# EnterpriseProjectType

Creates an object that represents an enterprise project type.



## Syntax

### CSOM

```C#
Class EnterpriseProjectType 
```
### JSOM

```
PS.EnterpriseProjectType
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/EnterpriseProjectTypes('{projecttypeid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of an enterprise project type.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the object identifier as a GUID.|
|ImageUrl|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the URL of an icon that is associated with the enterprise project type.|
|IsDefault|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether this is the default enterprise project type for new projects.|
|IsManaged|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether projects that are created with this enterprise project type should be in visibility mode or with full control by Project Server.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of an enterprise project type.|
|Order|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the position of an enterprise project type in a list of enterprise project types.|
|ProjectDetailPages|&#x2713;|&#x2713;|&#x2713;|[ProjectDetailPageCollection](ProjectDetailPageCollection.md)|Gets the collection of enterprise project detail pages.|
|ProjectPlanTemplateId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project plan template that was created with an enterprise project type.|
|WorkflowAssociationId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the workflow that is associated with an enterprise project type.|
|WorkflowAssociationName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the workflow that is associated with an enterprise project type.|
|WorkspaceTemplateName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the workspace template that is associated with an enterprise project type.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the current EnterpriseProjectType object.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the current EnterpriseProjectType object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
