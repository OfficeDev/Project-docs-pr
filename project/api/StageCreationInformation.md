[comment]: # (Name:StageCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.StageCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StageCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [Stage](Stage.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StageCreationInformation 
```
### JSOM

```javascript
PS.StageCreationInformation
```
### REST Interface

Supported.

```
PS.StageCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Stages/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Behavior':'value', 
		'CheckInRequired':'value', 
		'CustomFields':'value', 
		'Description':'value', 
		'Id':'value', 
		'Name':'value', 
		'PhaseId':'value', 
		'ProjectDetailPages':'value', 
		'SubmitDescription':'value', 
		'WorkflowStatusPageId':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Behavior"></a>Behavior|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[StrategicImpactBehavior](StrategicImpactBehavior.md)|Gets or sets the Strategic Impact value for a project stage; for example, Read Only.|
|<a name="CheckInRequired"></a>CheckInRequired|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether project check in is required.|
|<a name="CustomFields"></a>CustomFields|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CustomFieldCollection](CustomFieldCollection.md)|Gets or sets the collection of all the custom fields that have values set for the project stage.|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the stage description.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project stage.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the project stage.|
|<a name="PhaseId"></a>PhaseId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the phase that contains the project stage.|
|<a name="ProjectDetailPages"></a>ProjectDetailPages|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[ProjectDetailPageCollection](ProjectDetailPageCollection.md)|Gets or sets a collection of project detail pages for the project stage.|
|<a name="SubmitDescription"></a>SubmitDescription|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description for submit.|
|<a name="WorkflowStatusPageId"></a>WorkflowStatusPageId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the stage workflow status project detail page.|

## <a name="seeAlso"></a>See Also

[Stage](Stage.md)<br/>
[StageCollection](StageCollection.md)<br/>
