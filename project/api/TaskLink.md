[comment]: # (Name:TaskLink)
[comment]: # (Name:Microsoft.ProjectServer.TaskLink)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>TaskLink class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents the dependency relationship between the start and finish dates of two tasks.  Please reivew [DraftTaskLink](DraftTaskLink.md) and [PublishedTaskLink](PublishedTaskLink.md).

## <a name="syntax"></a>Syntax

### CSOM

```C#
class TaskLink 
```
### JSOM

```JavaScript
PS.TaskLink
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.TaskLink

http://<sitecollection>/<site>/_api/ProjectServer/?????
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the task link.|

## <a name="seeAlso"></a>See Also

[DraftTaskLink](DraftTaskLink.md)<br/>
[PublishedTaskLink](PublishedTaskLink.md)<br/>
