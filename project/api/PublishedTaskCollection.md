[comment]: # (Name:PublishedTaskCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PublishedTaskCollection class

inherits members from [ClientObjectCollection<PublishedTask>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of tasks in a published project.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class PublishedTaskCollection 
```

### JSOM

```JavaScript
PS.PublishedTaskCollection
```

### REST Interface

This resource supports GET HTTP command:

```
PS.PublishedTaskCollection

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Tasks
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[PublishedTask](PublishedTask.md)|Gets a [PublishedTask](PublishedTask.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[PublishedTask](PublishedTask.md)|Gets a [PublishedTask](PublishedTask.md) from the collection at the specified index.|

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{PublishedTaskId}&#39;](#&#39;{PublishedTaskId}&#39;)|||&#x2713;|[PublishedTask](PublishedTask.md)|Gets a [PublishedTask](PublishedTask.md) from the collection with the specified PublishedTaskId.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets a [PublishedTask](PublishedTask.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets a [PublishedTask](PublishedTask.md) from the collection with the Guid value.|

<br/>
#### Method Details

#### <a name="&#39;{PublishedTaskId}&#39;"></a>&#39;{PublishedTaskId}&#39;

Gets a [PublishedTask](PublishedTask.md) from the collection with the specified PublishedTaskId.

##### Syntax

```
PublishedTask http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Tasks('{PublishedTaskId}')
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|PublishedTaskId|String|the id of the PublishedTask|

##### Return Value

[PublishedTask](PublishedTask.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)

Gets a [PublishedTask](PublishedTask.md) from the collection with the Id value.

##### Syntax

```
PublishedTask GetByGuid(Guid uid)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [PublishedTask](PublishedTask.md)|

##### Return Value

[PublishedTask](PublishedTask.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a [PublishedTask](PublishedTask.md) from the collection with the Guid value.

##### Syntax

```
PublishedTask GetById(String objectId)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [PublishedTask](PublishedTask.md).|

##### Return Value
[PublishedTask](PublishedTask.md)<br />
The task in the published project.

## <a name="seeAlso"></a>See Also

[PublishedProject](PublishedProject.md)<br/>
[PublishedTask](PublishedTask.md)<br/>
