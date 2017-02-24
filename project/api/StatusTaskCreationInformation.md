[comment]: # (Name:StatusTaskCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.StatusTaskCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StatusTaskCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [StatusTask](StatusTask.md).

## <a name="syntax"></a>Syntax

### CSOM

```C#
class StatusTaskCreationInformation 
```
### JSOM

```JavaScript
PS.StatusTaskCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.StatusTaskCreationInformation

http://<sitecollection> /<site> /_api/ProjectServer/?????
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Finish':'value', 
		'Id':'value', 
		'Name':'value', 
		'ParentId':'value', 
		'Start':'value', 
		'Work':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Finish"></a>Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when a task is scheduled to be completed.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the status task object.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the status task object.|
|<a name="ParentId"></a>ParentId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the parent, or summary, task in a hierarchical task list.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when work on the task is scheduled to begin.|
|<a name="Work"></a>Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the planned work for the task.|

## <a name="seeAlso"></a>See Also

[StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md)<br/>
