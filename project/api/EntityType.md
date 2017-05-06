[comment]: # (Name:EntityType)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>EntityType class

<a name="description"></a>Represents a type of Project Server entity.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class EntityType 
```
### JSOM

```JavaScript
PS.EntityType
```
### REST Interface

Supported.

```
PS.EntityType

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EntityTypes/AssignmentEntity
http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EntityTypes/ProjectEntity
http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EntityTypes/ResourceEntity
http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EntityTypes/TaskEntity
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="ID"></a>ID|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the entity type.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the entity type.|

## <a name="seeAlso"></a>See Also

[CustomField](CustomField.md)<br/>
[CustomFieldCreationInformation](CustomFieldCreationInformation.md)<br/>
[EntityTypes](EntityTypes.md)<br/>
