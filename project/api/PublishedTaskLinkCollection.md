[comment]: # (Name:PublishedTaskLinkCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PublishedTaskLinkCollection class

inherits members from [ClientObjectCollection<PublishedTaskLink>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of task links in a published project.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class PublishedTaskLinkCollection 
```
### JSOM

```JavaScript
PS.PublishedTaskLinkCollection
```
### REST Interface

This resource supports GET HTTP commands.

```
PS.PublishedTaskLinkCollection

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/TaskLinks
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[PublishedTaskLink](PublishedTaskLink.md)|Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[PublishedTaskLink](PublishedTaskLink.md)|Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection at the specified index.|

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{PublishedTaskLinkId}&#39;](#&#39;{PublishedTaskLinkId}&#39;)|||&#x2713;|[PublishedTaskLink](PublishedTaskLink.md)|Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the specified PublishedTaskLinkId.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLink](PublishedTaskLink.md)|Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLink](PublishedTaskLink.md)|Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the Guid value.|

<br/>
#### Method Details

#### <a name="&#39;{PublishedTaskLinkId}&#39;"></a>&#39;{PublishedTaskLinkId}&#39;
 
Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the specified PublishedTaskLinkId.

##### Syntax

```
PublishedTaskLink http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/TaskLinks('{PublishedTaskLinkId}')
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|PublishedTaskLinkId|String|the id of the PublishedTaskLink|

##### Return Value

[PublishedTaskLink](PublishedTaskLink.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the Id value.

##### Syntax

```
PublishedTaskLink GetByGuid(Guid uid)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [PublishedTaskLink](PublishedTaskLink.md)|

##### Return Value

[PublishedTaskLink](PublishedTaskLink.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the Guid value.

##### Syntax

```
PublishedTaskLink GetById(String objectId)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [PublishedTaskLink](PublishedTaskLink.md).|

##### Return Value

[PublishedTaskLink](PublishedTaskLink.md)

## <a name="seeAlso"></a>See Also

[PublishedProject](PublishedProject.md)<br/>
[PublishedTask](PublishedTask.md)<br/>
[PublishedTaskLink](PublishedTaskLink.md)<br/>
