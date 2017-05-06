[comment]: # (Name:StageDetailPageCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.StageDetailPageCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StageDetailPageCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [StageDetailPage](StageDetailPage.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StageDetailPageCreationInformation 
```
### JSOM

```javascript
PS.StageDetailPageCreationInformation
```
### REST Interface

Supported.

```
PS.StageDetailPageCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Stages('{stageid}')/ProjectDetailPages/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Description':'value', 
		'Id':'value', 
		'Position':'value', 
		'RequiresAttention':'value'		
	}
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the stage PDP.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the PDP for the stage.|
|<a name="Position"></a>Position|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the position of a PDP relative to the other PDPs that are displayed in the stage.|
|<a name="RequiresAttention"></a>RequiresAttention|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the stage PDP requires attention.|

## <a name="seeAlso"></a>See Also

[StageDetailPage](StageDetailPage.md)<br/>
[StageDetailPageCollection](StageDetailPageCollection.md)<br/>
