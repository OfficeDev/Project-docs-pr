[comment]: # (Name:PublishedTaskLink)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PublishedTaskLink class

inherits members from [TaskLink](TaskLink.md)<br/>

<a name="description"></a>Represents a dependency relationship between the start and finish dates of two tasks.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class PublishedTaskLink 
```
### JSOM

```JavaScript
PS.PublishedTaskLink
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.PublishedTaskLink

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/TaskLinks('{linkid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="DependencyType"></a>DependencyType|&#x2713;|&#x2713;|&#x2713;|[DependencyType](DependencyType.md)|Gets the type of link relationship between two tasks.|
|<a name="End"></a>End|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets the task at the end of the link.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets the task at the start of the link.|

## <a name="seeAlso"></a>See Also

[PublishedTaskLinkCollection](PublishedTaskLinkCollection.md)<br/>
