[comment]: # (Name:EnterpriseProjectType)
[comment]: # (Name:Microsoft.ProjectServer.EnterpriseProjectType)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EnterpriseProjectType class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Creates an object that represents an enterprise project type.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EnterpriseProjectType 
```
### JSOM

```javascript
PS.EnterpriseProjectType
```
### REST Interface

Supported.

```
PS.EnterpriseProjectType

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/EnterpriseProjectTypes('{projecttypeid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of an enterprise project type.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the object identifier as a GUID.|
|<a name="ImageUrl"></a>ImageUrl|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the URL of an icon that is associated with the enterprise project type.|
|<a name="IsDefault"></a>IsDefault|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether this is the default enterprise project type for new projects.|
|<a name="IsManaged"></a>IsManaged|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether projects that are created with this enterprise project type should be in visibility mode or with full control by Project Server.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of an enterprise project type.|
|<a name="Order"></a>Order|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the position of an enterprise project type in a list of enterprise project types.|
|<a name="ProjectDetailPages"></a>ProjectDetailPages|&#x2713;|&#x2713;|&#x2713;|[ProjectDetailPageCollection](ProjectDetailPageCollection.md)|Gets the collection of enterprise project detail pages.|
|<a name="ProjectPlanTemplateId"></a>ProjectPlanTemplateId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project plan template that was created with an enterprise project type.|
|<a name="WorkflowAssociationId"></a>WorkflowAssociationId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the workflow that is associated with an enterprise project type.|
|<a name="WorkflowAssociationName"></a>WorkflowAssociationName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the workflow that is associated with an enterprise project type.|
|<a name="WorkspaceTemplateName"></a>WorkspaceTemplateName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the workspace template that is associated with an enterprise project type.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the enterprise project type object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the enterprise project type object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[EnterpriseProjectTypeCollection](EnterpriseProjectTypeCollection.md)<br/>
[EnterpriseProjectTypeCreationInformation](EnterpriseProjectTypeCreationInformation.md)<br/>
[Project](Project.md)<br/>
