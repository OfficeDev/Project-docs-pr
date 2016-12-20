[comment]: # (Name:AssignmentCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>AssignmentCreationInformation class
<a name="description"></a>Contains the properties that can be set when creating an [Assignment](Assignment.md).

## <a name="syntax"></a>Syntax

### CSOM

```C#
class AssignmentCreationInformation 
```

### JSOM

```
PS.AssignmentCreationInformation
```

### REST Interface

This resource supports POST commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/Draft/Assignments/Add
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Finish"></a>Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the assignment finish date and time.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the assignment.|
|<a name="Notes"></a>Notes|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the notes for the assignment.|
|<a name="ResourceId"></a>ResourceId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the resource for the assignment.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the assignment start date and time.|
|<a name="TaskId"></a>TaskId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the task for the assignment.|

## <a name="seeAlso"></a>See Also

[DraftAssignmentCollection](DraftAssignmentCollection.md)<br/>
