[comment]: # (Name:EnterpriseResourceCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.EnterpriseResourceCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EnterpriseResourceCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [EnterpriseResource](EnterpriseResource.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EnterpriseResourceCreationInformation 
```
### JSOM

```javascript
PS.EnterpriseResourceCreationInformation
```

### REST Interface

This resource supports POST HTTP commands.

```
PS.EnterpriseResourceCreationInformation

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/EnterpriseResources/Add
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
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
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
