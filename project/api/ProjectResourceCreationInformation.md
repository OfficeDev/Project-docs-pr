[comment]: # (Name:ProjectResourceCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.ProjectResourceCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectResourceCreationInformation class

<a name="description"></a>Provides property settings and methods for the creation of a project resource entity.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectResourceCreationInformation 
```
### JSOM

```javascript
PS.ProjectResourceCreationInformation
```

### REST Interface

Supported.

```
PS.ProjectResourceCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('projectid')/ProjectResources
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Account':'value', 
		'Email':'value', 
		'Id':'value', 
		'Name':'value', 
		'Notes':'value'		
	}
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Account"></a>Account|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the project resource account.|
|<a name="Email"></a>Email|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the email address of the project resource.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project resource.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the project resource name.|
|<a name="Notes"></a>Notes|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the notes about the project resource.|

## <a name="seeAlso"></a>See Also

[DraftProjectResource](DraftProjectResource.md)<br/>
[DraftProjectResourceCollection](DraftProjectResourceCollection.md)<br/>
