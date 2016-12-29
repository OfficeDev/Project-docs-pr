[comment]: # (Name:EntityTypes)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>EntityTypes class

<a name="description"></a>Represents the types of Project Server entities that are exposed through CSOM.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class EntityTypes 
```
### JSOM

```JavaScript
PS.EntityTypes
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.EntityTypes

http://<sitecollection>/<site>/_api/ProjectServer/EntityTypes
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="AssignmentEntity"></a>AssignmentEntity|&#x2713;|&#x2713;|&#x2713;|[Entity](Entity.md)|Gets an assignment entity type.|
|<a name="ProjectEntity"></a>ProjectEntity|&#x2713;|&#x2713;|&#x2713;|[Entity](Entity.md)|Gets a project entity type.|
|<a name="ResourceEntity"></a>ResourceEntity|&#x2713;|&#x2713;|&#x2713;|[Entity](Entity.md)|Gets a resource entity type.|
|<a name="TaskEntity"></a>TaskEntity|&#x2713;|&#x2713;|&#x2713;|[Entity](Entity.md)|Gets a task entity type.|

## <a name="seeAlso"></a>See Also

[ProjectContext](ProjectContext.md)<br/>
