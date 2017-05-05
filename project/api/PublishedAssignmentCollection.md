[comment]: # (Name:PublishedAssignmentCollection)
[comment]: # (Name:Microsoft.ProjectServer.PublishedAssignmentCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PublishedAssignmentCollection class

inherits members from [ClientObjectCollection<PublishedAssignment>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of published assignments.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PublishedAssignmentCollection
```

### JSOM

```javascript
PS.PublishedAssignmentCollection
```

### REST Interface

Supported.

```
PS.PublishedAssignmentCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Assignments
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[PublishedAssignment](PublishedAssignment.md)|Gets a [PublishedAssignment](PublishedAssignment.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[PublishedAssignment](PublishedAssignment.md)|Gets a [PublishedAssignment](PublishedAssignment.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{PublishedAssignmentId}&#39;](#&#39;{PublishedAssignmentId}&#39;)|||&#x2713;|[PublishedAssignment](PublishedAssignment.md)|Gets a [PublishedAssignment](PublishedAssignment.md) from the collection with the specified PublishedAssignmentId.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignment](PublishedAssignment.md)|Gets a [PublishedAssignment](PublishedAssignment.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignment](PublishedAssignment.md)|Gets a [PublishedAssignment](PublishedAssignment.md) from the collection with the Guid value.|

<br/>
#### Method Details

#### <a name="&#39;{PublishedAssignmentId}&#39;"></a>&#39;{PublishedAssignmentId}&#39;
 
Gets a [PublishedAssignment](PublishedAssignment.md) from the collection with the specified PublishedAssignmentId.

##### Syntax

```
PublishedAssignment http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Assignments('{PublishedAssignmentId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|PublishedAssignmentId|String|the id of the PublishedAssignment|

##### Return Value

[PublishedAssignment](PublishedAssignment.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)

Gets a [PublishedAssignment](PublishedAssignment.md) from the collection with the Id value.

##### Syntax

```
PublishedAssignment GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [PublishedAssignment](PublishedAssignment.md)|

##### Return Value

[PublishedAssignment](PublishedAssignment.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a [PublishedAssignment](PublishedAssignment.md) from the collection with the Guid value.

##### Syntax

```
PublishedAssignment GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [PublishedAssignment](PublishedAssignment.md).|

##### Return Value

[PublishedAssignment](PublishedAssignment.md)

## <a name="seeAlso"></a>See Also

[PublishedAssignment](PublishedAssignment.md)<br />
[PublishedProject](PublishedProject.md)<br/>
[PublishedProjectResource](PublishedProjectResource.md)<br/>
[PublishedTask](PublishedTask.md)<br/>
