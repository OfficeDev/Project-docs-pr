[comment]: # (Name:EnterpriseResourceCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>EnterpriseResourceCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [EnterpriseResource](EnterpriseResource.md).

## <a name="syntax"></a>Syntax

### CSOM

```C#
class EnterpriseResourceCreationInformation 
```
### JSOM

```JavaScript
PS.EnterpriseResourceCreationInformation
```

### REST Interface

<!-- 
    This needs to be verified, then added to the document. 
    This resource supports GET HTTP command.

```
PS.EnterpriseResourceCreationInformation

http://<sitecollection>/<site>/api/ProjectServer/EnterpriseResources/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Id':'value', 
		'IsBudget':'value', 
		'IsGeneric':'value', 
		'IsInactive':'value', 
		'Name':'value', 
		'ResourceType':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the enterprise resource.|
|<a name="IsBudget"></a>IsBudget|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether this is a budget resource.|
|<a name="IsGeneric"></a>IsGeneric|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether this is a generic resource.|
|<a name="IsInactive"></a>IsInactive|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether this resource should be created in an inactive state.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the enterprise resource.|
|<a name="ResourceType"></a>ResourceType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[EnterpriseResourceType](EnterpriseResourceType.md)|Gets or sets a value that represents the resource type.|

## <a name="seeAlso"></a>See Also

[EnterpriseResource](EnterpriseResource.md)<br/>
[EnterpriseResourceCollection](EnterpriseResourceCollection.md)<br/>
