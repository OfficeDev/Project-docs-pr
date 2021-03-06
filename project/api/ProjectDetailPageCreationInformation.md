[comment]: # (Name:ProjectDetailPageCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.ProjectDetailPageCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectDetailPageCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [ProjectDetailPage](ProjectDetailPage.md) when creating a [EnterpriseProjectTypeCreationInformation](EnterpriseProjectTypeCreationInformation.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectDetailPageCreationInformation 
```
### JSOM

```javascript
PS.ProjectDetailPageCreationInformation
```
### REST Interface

Supported.

```
PS.ProjectDetailPageCreationInformation

```



POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Id':'value', 
		'IsCreate':'value', 
		'Position':'value'		
	}
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of a project detail page.|
|<a name="IsCreate"></a>IsCreate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a project detail page is created.|
|<a name="Position"></a>Position|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets a value that indicates the order of placement of a project detail page in a list of project detail pages.|

## <a name="seeAlso"></a>See Also

