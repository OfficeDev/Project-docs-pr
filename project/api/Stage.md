[comment]: # (Name:Stage)
[comment]: # (Name:Microsoft.ProjectServer.Stage)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>Stage class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a stage in a project workflow.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class Stage 
```
### JSOM

```javascript
PS.Stage
```
### REST Interface

Supported.

```
PS.Stage

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Stages('{stageid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Behavior"></a>Behavior|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[StrategicImpactBehavior](StrategicImpactBehavior.md)|Gets or sets the Strategic Impact value for a stage; for example, Read Only.|
|<a name="CheckInRequired"></a>CheckInRequired|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether project check in is required.|
|<a name="CustomFields"></a>CustomFields|&#x2713;|&#x2713;|&#x2713;|[StageCustomFieldCollection](StageCustomFieldCollection.md)|Gets the collection of all custom field objects that have values set for the stage.|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the stage description.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the stage.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the stage.|
|<a name="Phase"></a>Phase|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[Phase](Phase.md)|Gets or sets the phase that contains the stage.|
|<a name="ProjectDetailPages"></a>ProjectDetailPages|&#x2713;|&#x2713;|&#x2713;|[StageDetailPageCollection](StageDetailPageCollection.md)|Gets a collection of project detail pages that are associated with the stage.|
|<a name="SubmitDescription"></a>SubmitDescription|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the stage description for submit.|
|<a name="WorkflowStatusPage"></a>WorkflowStatusPage|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[ProjectDetailPage](ProjectDetailPage.md)|Gets or sets the workflow status project detail page for the stage.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the stage object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the stage object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[Project](Project.md)<br/>
[StageCollection](StageCollection.md)<br/>
[StageCreationInformation](StageCreationInformation.md)<br/>
[StageCustomField](StageCustomField.md)<br/>
[StageDetailPage](StageDetailPage.md)<br/>
