[comment]: # (Name:DraftTaskCollection)
[comment]: # (Name:Microsoft.ProjectServer.DraftTaskCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>DraftTaskCollection class

inherits members from [ClientObjectCollection<DraftTask>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [DraftTask](DraftTask.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class DraftTaskCollection 
```
### JSOM

```javascript
PS.DraftTaskCollection
```
### REST Interface

Supported.

```
PS.DraftTaskCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Draft/Tasks
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[DraftTask](DraftTask.md)|Gets a [DraftTask](DraftTask.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[DraftTask](DraftTask.md)|Gets a [DraftTask](DraftTask.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{DraftTaskId}&#39;](#&#39;{DraftTaskId}&#39;)|||&#x2713;|[DraftTask](DraftTask.md)|Gets a [DraftTask](DraftTask.md) from the collection with the specified DraftTaskId.|
|[Add(TaskCreationInformation parameters)](#Add_[TaskCreationInformation]_TaskCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Adds the [DraftTask](DraftTask.md) that is specified by the [TaskCreationInformation](TaskCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Gets a [DraftTask](DraftTask.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Gets a [DraftTask](DraftTask.md) from the collection with the Guid value.|
|[Remove(DraftTask task)](#Remove_[DraftTask]_DraftTask.md__task_)|&#x2713;|&#x2713;||Boolean|Removes the specified [DraftTask](DraftTask.md) from the collection.|

<br/>
#### Method Details

#### <a name="&#39;{DraftTaskId}&#39;"></a>&#39;{DraftTaskId}&#39;
 
Gets a [DraftTask](DraftTask.md) from the collection with the specified DraftTaskId.

##### Syntax

```
DraftTask http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Draft/Tasks('{DraftTaskId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|DraftTaskId|String|the id of the DraftTask|

##### Return Value

[DraftTask](DraftTask.md)

#### <a name="Add_[TaskCreationInformation]_TaskCreationInformation.md__parameters_"></a>Add([TaskCreationInformation](TaskCreationInformation.md) parameters)
 
Adds the [DraftTask](DraftTask.md) that is specified by the [TaskCreationInformation](TaskCreationInformation.md) object to the collection.

##### Syntax

```
DraftTask Add(TaskCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[TaskCreationInformation](TaskCreationInformation.md)|The properties that can be set when creating a draft task.|

##### Return Value

[DraftTask](DraftTask.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [DraftTask](DraftTask.md) from the collection with the Id value.

##### Syntax

```
DraftTask GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [DraftTask](DraftTask.md)|

##### Return Value

[DraftTask](DraftTask.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [DraftTask](DraftTask.md) from the collection with the Guid value.

##### Syntax

```
DraftTask GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [DraftTask](DraftTask.md).|

##### Return Value

[DraftTask](DraftTask.md)

#### <a name="Remove_[DraftTask]_DraftTask.md__task_"></a>Remove([DraftTask](DraftTask.md) task)
 
Removes the specified [DraftTask](DraftTask.md) from the collection.

##### Syntax

```
Boolean Remove(DraftTask task)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|task|[DraftTask](DraftTask.md)|The [DraftTask](DraftTask.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[DraftProject](DraftProject.md)<br/>
[DraftTask](DraftTask.md)<br/>
[TaskCreationInformation](TaskCreationInformation.md)<br/>
