[comment]: # (Name:ProjectCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.ProjectCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a project.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectCreationInformation 
```
### JSOM

```javascript
PS.ProjectCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.ProjectCreationInformation

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Description':'value', 
		'EnterpriseProjectTypeId':'value', 
		'Id':'value', 
		'ListId':'value', 
		'Name':'value', 
		'Start':'value', 
		'WebId':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the project.|
|<a name="EnterpriseProjectTypeId"></a>EnterpriseProjectTypeId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the enterprise project type (EPT).|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project.|
|<a name="ListId"></a>ListId|||&#x2713;&#x02B7;|Guid|List Id on the web that the project is being created from. (Ideation Scenario)|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the project.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the start date of the project.|
|<a name="TaskList"></a>TaskList|&#x2713;&#x02B7;|&#x2713;&#x02B7;||SPList|Gets or sets the imported task list.|
|<a name="WebId"></a>WebId|||&#x2713;&#x02B7;|Guid|The Id of the web that contains the list where the project is being created from. (Ideation Scenario)|

## <a name="seeAlso"></a>See Also

[ProjectCollection](ProjectCollection.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
[SPList](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.splist.aspx)<br/>
