[comment]: # (Name:PhaseCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PhaseCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [Phase](Phase.md).

## <a name="syntax"></a>Syntax

### CSOM

```C#
class PhaseCreationInformation 
```
### JSOM

```JavaScript
PS.PhaseCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.PhaseCreationInformation

http://<sitecollection>/<site>/api/ProjectServer/Phases/Add
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

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the phase.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the phase.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the phase.|

## <a name="seeAlso"></a>See Also

[Phase](Phase.md)<br/>
[PhaseCollection](PhaseCollection.md)<br/>
