[comment]: # (Name:TaskCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.TaskCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TaskCreationInformation class

<a name="description"></a>Provides property settings and methods that are used to create a task.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TaskCreationInformation 
```

### JSOM

```javascript
PS.TaskCreationInformation
```

### REST Interface

Supported.

```
PS.TaskCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectId}')/Draft/Tasks/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'AddAfterId':'value', 
		'Duration':'value', 
		'Finish':'value', 
		'Id':'value', 
		'IsManual':'value', 
		'Name':'value', 
		'Notes':'value', 
		'ParentId':'value', 
		'Start':'value', 
		'StatusManager':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="AddAfterId"></a>AddAfterId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID value of the task that specifies the insertion point.|
|<a name="Duration"></a>Duration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the task duration.|
|<a name="Finish"></a>Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the task finish date.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the task.|
|<a name="IsManual"></a>IsManual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the task is manually scheduled.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the task name.|
|<a name="Notes"></a>Notes|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets notes about the task.|
|<a name="ParentId"></a>ParentId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the parent task in a hierarchical task list.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the task start date.|
|<a name="StatusManager"></a>StatusManager|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets or sets the status manager of the task.|

## <a name="seeAlso"></a>See Also

[DraftTask](DraftTask.md)<br/>
[DraftTaskCollection](DraftTaskCollection.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
