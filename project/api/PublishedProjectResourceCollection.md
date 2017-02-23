[comment]: # (Name:PublishedProjectResourceCollection)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>PublishedProjectResourceCollection class

inherits members from [ClientObjectCollection<PublishedProjectResource>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of resources in a published project.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class PublishedProjectResourceCollection 
```

### JSOM

```JavaScript
PS.PublishedProjectResourceCollection
```

### REST Interface

This resource supports GET and POST HTTP commands:

```
PS.PublishedProjectResourceCollection

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/ProjectResources
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[PublishedProjectResource](PublishedProjectResource.md)|Gets a [PublishedProjectResource](PublishedProjectResource.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[PublishedProjectResource](PublishedProjectResource.md)|Gets a [PublishedProjectResource](PublishedProjectResource.md) from the collection at the specified index.|

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[&#39;{PublishedProjectResourceId}&#39;](#&#39;{PublishedProjectResourceId}&#39;)|||&#x2713;|[PublishedProjectResource](PublishedProjectResource.md)|Gets a [PublishedProjectResource](PublishedProjectResource.md) from the collection with the specified PublishedProjectResourceId.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[PublishedProjectResource](PublishedProjectResource.md)|Gets a [PublishedProjectResource](PublishedProjectResource.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[PublishedProjectResource](PublishedProjectResource.md)|Gets a [PublishedProjectResource](PublishedProjectResource.md) from the collection with the Guid value.|

<br/>
#### Method Details

#### <a name="&#39;{PublishedProjectResourceId}&#39;"></a>&#39;{PublishedProjectResourceId}&#39;
 
Gets a [PublishedProjectResource](PublishedProjectResource.md) from the collection with the specified PublishedProjectResourceId.

##### Syntax

```
PublishedProjectResource http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/ProjectResources('{PublishedProjectResourceId}')
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|PublishedProjectResourceId|String|the id of the PublishedProjectResource|

##### Return Value

[PublishedProjectResource](PublishedProjectResource.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)

Gets a [PublishedProjectResource](PublishedProjectResource.md) from the collection with the Id value.

##### Syntax

```
PublishedProjectResource GetByGuid(Guid uid)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [PublishedProjectResource](PublishedProjectResource.md)|

##### Return Value

[PublishedProjectResource](PublishedProjectResource.md)<br />
A [PublishedProjectResource](PublishedProjectResource.md) object.

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a [PublishedProjectResource](PublishedProjectResource.md) from the collection with the Guid value.

##### Syntax

```
PublishedProjectResource GetById(String objectId)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [PublishedProjectResource](PublishedProjectResource.md).|

##### Return Value

[PublishedProjectResource](PublishedProjectResource.md)

## <a name="seeAlso"></a>See Also

[PublishedProject](PublishedProject.md)<br/>
[PublishedProjectResource](PublishedProjectResource.md)<br />
