[comment]: # (Name:PhaseCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.PhaseCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PhaseCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [Phase](Phase.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PhaseCreationInformation 
```
### JSOM

```javascript
PS.PhaseCreationInformation
```
### REST Interface

Supported.

```
PS.PhaseCreationInformation

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Phases/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Description':'value', 
		'Id':'value', 
		'Name':'value'		
	}
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the phase.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the phase.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the phase.|

## <a name="seeAlso"></a>See Also

[Phase](Phase.md)<br/>
[PhaseCollection](PhaseCollection.md)<br/>
