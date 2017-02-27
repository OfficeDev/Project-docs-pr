[comment]: # (Name:DraftTaskLink)
[comment]: # (Name:Microsoft.ProjectServer.DraftTaskLink)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>DraftTaskLink class

inherits members from [TaskLink](TaskLink.md)<br/>

<a name="description"></a>Represents a task link in a checked-out project.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class DraftTaskLink 
```
### JSOM

```JavaScript
PS.DraftTaskLink
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.DraftTaskLink

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Draft/TaskLinks('{linkid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="DependencyType"></a>DependencyType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[DependencyType](DependencyType.md)|Gets or sets the type of link relationship between two tasks.|
|<a name="End"></a>End|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Gets the task at the end of the link.|
|<a name="EndId"></a>EndId|||&#x2713;|Guid|Gets the id of the task at the end of the link.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Gets the task at the start of the link.|
|<a name="StartId"></a>StartId|||&#x2713;|Guid|Gets the id of the at the start of the link.|

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the draft task link object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()

Deletes the draft task link object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[DraftTaskLinkCollection](DraftTaskLinkCollection.md)<br/>
[TaskLinkCreationInformation](TaskLinkCreationInformation.md)<br/>
