[comment]: # (Name:QueueJobCollection)
[comment]: # (Name:Microsoft.ProjectServer.QueueJobCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>QueueJobCollection class

inherits members from [ClientObjectCollection<QueueJob>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of QueueJob objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class QueueJobCollection 
```
### JSOM

```javascript
PS.QueueJobCollection
```
### REST Interface

Supported.

```
PS.QueueJobCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectid}')/QueueJobs
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[QueueJob](QueueJob.md)|Gets a [QueueJob](QueueJob.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[QueueJob](QueueJob.md)|Gets a [QueueJob](QueueJob.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{QueueJobId}&#39;](#&#39;{QueueJobId}&#39;)|||&#x2713;|[QueueJob](QueueJob.md)|Gets a [QueueJob](QueueJob.md) from the collection with the specified QueueJobId.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Gets a [QueueJob](QueueJob.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Gets a [QueueJob](QueueJob.md) from the collection with the Guid value.|

<br/>
#### Method Details

#### <a name="&#39;{QueueJobId}&#39;"></a>&#39;{QueueJobId}&#39;
 
Gets a [QueueJob](QueueJob.md) from the collection with the specified QueueJobId.

##### Syntax

```
QueueJob http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectid}')/QueueJobs('{QueueJobId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|QueueJobId|String|the id of the QueueJob|

##### Return Value

[QueueJob](QueueJob.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [QueueJob](QueueJob.md) from the collection with the Id value.

##### Syntax

```
QueueJob GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [QueueJob](QueueJob.md)|

##### Return Value

[QueueJob](QueueJob.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [QueueJob](QueueJob.md) from the collection with the Guid value.

##### Syntax

```
QueueJob GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [QueueJob](QueueJob.md).|

##### Return Value

[QueueJob](QueueJob.md)

## <a name="seeAlso"></a>See Also

[Project](Project.md)<br/>
[QueueJob](QueueJob.md)<br/>
