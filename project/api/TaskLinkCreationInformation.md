[comment]: # (Name:TaskLinkCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.TaskLinkCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TaskLinkCreationInformation class

<a name="description"></a>Provides property settings and methods that are used to create a task link.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TaskLinkCreationInformation 
```
### JSOM

```javascript
PS.TaskLinkCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.TaskLinkCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectid}')/Draft/TaskLinks('{linkid}')/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'DependencyType':'value', 
		'EndId':'value', 
		'Id':'value', 
		'StartId':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="DependencyType"></a>DependencyType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[DependencyType](DependencyType.md)|Gets or sets the type of link relationship between two tasks.|
|<a name="EndId"></a>EndId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the task that is at the end of the link.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the task link.|
|<a name="StartId"></a>StartId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the task that is at the start of the link.|

## <a name="seeAlso"></a>See Also

[DraftTaskLink](DraftTaskLink.md)<br/>
[DraftTaskLinkCollection](DraftTaskLinkCollection.md)<br/>
