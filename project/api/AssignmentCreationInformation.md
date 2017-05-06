[comment]: # (Name:AssignmentCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.AssignmentCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>AssignmentCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating an [Assignment](Assignment.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class AssignmentCreationInformation 
```

### JSOM

```javascript
PS.AssignmentCreationInformation
```

### REST Interface

Supported.

```
PS.AssignmentCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Draft/Assignments/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Finish':'value', 
		'Id':'value', 
		'Notes':'value', 
		'ResourceId':'value', 
		'Start':'value', 
		'TaskId':'value'		
	}
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Finish"></a>Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the assignment finish date and time.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the assignment.|
|<a name="Notes"></a>Notes|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the notes for the assignment.|
|<a name="ResourceId"></a>ResourceId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the resource for the assignment.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the assignment start date and time.|
|<a name="TaskId"></a>TaskId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the task for the assignment.|

## <a name="seeAlso"></a>See Also

[DraftAssignment](DraftAssignment.md)<br/>
[DraftAssignmentCollection](DraftAssignmentCollection.md)<br/>
