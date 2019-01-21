[comment]: # (Name:DraftTaskLinkCollection)
[comment]: # (Name:Microsoft.ProjectServer.DraftTaskLinkCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>DraftTaskLinkCollection class

inherits members from [ClientObjectCollection<DraftTaskLink>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [DraftTaskLink](DraftTaskLink.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class DraftTaskLinkCollection 
```
### JSOM

```javascript
PS.DraftTaskLinkCollection
```
### REST Interface

Supported.

```
PS.DraftTaskLinkCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Draft/TaskLinks
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[DraftTaskLink](DraftTaskLink.md)|Gets a [DraftTaskLink](DraftTaskLink.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[DraftTaskLink](DraftTaskLink.md)|Gets a [DraftTaskLink](DraftTaskLink.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{DraftTaskLinkId}&#39;](#&#39;{DraftTaskLinkId}&#39;)|||&#x2713;|[DraftTaskLink](DraftTaskLink.md)|Gets a [DraftTaskLink](DraftTaskLink.md) from the collection with the specified DraftTaskLinkId.|
|[Add(TaskLinkCreationInformation parameters)](#Add_[TaskLinkCreationInformation]_TaskLinkCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[DraftTaskLink](DraftTaskLink.md)|Adds the [DraftTaskLink](DraftTaskLink.md) that is specified by the [TaskLinkCreationInformation](TaskLinkCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[DraftTaskLink](DraftTaskLink.md)|Gets a [DraftTaskLink](DraftTaskLink.md) from the collection with the Guid value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[DraftTaskLink](DraftTaskLink.md)|Gets a [DraftTaskLink](DraftTaskLink.md) from the collection with the Id value.|
|[Remove(DraftTaskLink TaskLink)](#Remove_[DraftTaskLink]_DraftTaskLink.md__TaskLink_)|&#x2713;|&#x2713;||Boolean|Removes the specified [DraftTaskLink](DraftTaskLink.md) from the collection.|

<br/>
#### Method Details

#### <a name="&#39;{DraftTaskLinkId}&#39;"></a>&#39;{DraftTaskLinkId}&#39;
 
Gets a [DraftTaskLink](DraftTaskLink.md) from the collection with the specified DraftTaskLinkId.

##### Syntax

```
DraftTaskLink http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Draft/TaskLinks('{DraftTaskLinkId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|DraftTaskLinkId|String|the id of the DraftTaskLink|

##### Return Value

[DraftTaskLink](DraftTaskLink.md)

#### <a name="Add_[TaskLinkCreationInformation]_TaskLinkCreationInformation.md__parameters_"></a>Add([TaskLinkCreationInformation](TaskLinkCreationInformation.md) parameters)
 
Adds the [DraftTaskLink](DraftTaskLink.md) that is specified by the [TaskLinkCreationInformation](TaskLinkCreationInformation.md) object to the collection.

##### Syntax

```
DraftTaskLink Add(TaskLinkCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[TaskLinkCreationInformation](TaskLinkCreationInformation.md)|The properties that can be set when creating a draft task link.|

##### Return Value

[DraftTaskLink](DraftTaskLink.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [DraftTaskLink](DraftTaskLink.md) from the collection with the Guid value.

##### Syntax

```
DraftTaskLink GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [DraftTaskLink](DraftTaskLink.md)|

##### Return Value

[DraftTaskLink](DraftTaskLink.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [DraftTaskLink](DraftTaskLink.md) from the collection with the Id value.

##### Syntax

```
DraftTaskLink GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [DraftTaskLink](DraftTaskLink.md).|

##### Return Value

[DraftTaskLink](DraftTaskLink.md)

#### <a name="Remove_[DraftTaskLink]_DraftTaskLink.md__TaskLink_"></a>Remove([DraftTaskLink](DraftTaskLink.md) TaskLink)
 
Removes the specified [DraftTaskLink](DraftTaskLink.md) from the collection.

##### Syntax

```
Boolean Remove(DraftTaskLink TaskLink)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|TaskLink|[DraftTaskLink](DraftTaskLink.md)|The [DraftTaskLink](DraftTaskLink.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[DraftProject](DraftProject.md)<br/>
[DraftTask](DraftTask.md)<br/>
[DraftTaskLink](DraftTaskLink.md)<br/>
[TaskLinkCreationInformation](TaskLinkCreationInformation.md)<br/>
