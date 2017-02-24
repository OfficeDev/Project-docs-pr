[comment]: # (Name:StageCustomFieldCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StageCustomFieldCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [StageCustomField](StageCustomField.md).

## <a name="syntax"></a>Syntax

### CSOM

```C#
class StageCustomFieldCreationInformation 
```
### JSOM

```JavaScript
PS.StageCustomFieldCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.StageCustomFieldCreationInformation

http://<sitecollection>/<site>/api/ProjectServer/Stages('{stageid}')/CustomFields/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Id':'value', 
		'ReadOnly':'value', 
		'Required':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the custom field.|
|<a name="ReadOnly"></a>ReadOnly|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the custom field is read-only in the stage.|
|<a name="Required"></a>Required|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the custom field is required in the stage.|

## <a name="seeAlso"></a>See Also

[StageCustomField](StageCustomField.md)<br/>
[StageCustomFieldCollection](StageCustomFieldCollection.md)<br/>
