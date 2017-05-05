[comment]: # (Name:DraftAssignmentCollection)
[comment]: # (Name:Microsoft.ProjectServer.DraftAssignmentCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>DraftAssignmentCollection class

inherits members from [ClientObjectCollection<DraftAssignment>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [DraftAssignment](DraftAssignment.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class DraftAssignmentCollection 
```
### JSOM

```javascript
PS.DraftAssignmentCollection
```
### REST Interface

Supported.

```
PS.DraftAssignmentCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Draft/Assignments
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[DraftAssignment](DraftAssignment.md)|Gets a [DraftAssignment](DraftAssignment.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[DraftAssignment](DraftAssignment.md)|Gets a [DraftAssignment](DraftAssignment.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{DraftAssignmentId}&#39;](#&#39;{DraftAssignmentId}&#39;)|||&#x2713;|[DraftAssignment](DraftAssignment.md)|Gets a [DraftAssignment](DraftAssignment.md) from the collection with the specified DraftAssignmentId.|
|[Add(AssignmentCreationInformation parameters)](#Add_[AssignmentCreationInformation]_AssignmentCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[DraftAssignment](DraftAssignment.md)|Adds the [DraftAssignment](DraftAssignment.md) that is specified by the [AssignmentCreationInformation](AssignmentCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[DraftAssignment](DraftAssignment.md)|Gets a [DraftAssignment](DraftAssignment.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[DraftAssignment](DraftAssignment.md)|Gets a [DraftAssignment](DraftAssignment.md) from the collection with the Guid value.|
|[Remove(DraftAssignment assignment)](#Remove_[DraftAssignment]_DraftAssignment.md__assignment_)|&#x2713;|&#x2713;||Boolean|Removes the specified [DraftAssignment](DraftAssignment.md) from the collection.|

<br/>
#### Method Details

#### <a name="&#39;{DraftAssignmentId}&#39;"></a>&#39;{DraftAssignmentId}&#39;
 
Gets a [DraftAssignment](DraftAssignment.md) from the collection with the specified DraftAssignmentId.

##### Syntax

```
DraftAssignment http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Draft/Assignments('{DraftAssignmentId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|DraftAssignmentId|String|the id of the DraftAssignment|

##### Return Value

[DraftAssignment](DraftAssignment.md)

#### <a name="Add_[AssignmentCreationInformation]_AssignmentCreationInformation.md__parameters_"></a>Add([AssignmentCreationInformation](AssignmentCreationInformation.md) parameters)
 
Adds the [DraftAssignment](DraftAssignment.md) that is specified by the [AssignmentCreationInformation](AssignmentCreationInformation.md) object to the collection.

##### Syntax

```
DraftAssignment Add(AssignmentCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[AssignmentCreationInformation](AssignmentCreationInformation.md)|The properties that can be set when creating a draft assignment.|

##### Return Value

[DraftAssignment](DraftAssignment.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [DraftAssignment](DraftAssignment.md) from the collection with the Id value.

##### Syntax

```
DraftAssignment GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [DraftAssignment](DraftAssignment.md)|

##### Return Value

[DraftAssignment](DraftAssignment.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [DraftAssignment](DraftAssignment.md) from the collection with the Guid value.

##### Syntax

```
DraftAssignment GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [DraftAssignment](DraftAssignment.md).|

##### Return Value

[DraftAssignment](DraftAssignment.md)

#### <a name="Remove_[DraftAssignment]_DraftAssignment.md__assignment_"></a>Remove([DraftAssignment](DraftAssignment.md) assignment)
 
Removes the specified [DraftAssignment](DraftAssignment.md) from the collection.

##### Syntax

```
Boolean Remove(DraftAssignment assignment)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|assignment|[DraftAssignment](DraftAssignment.md)|The [DraftAssignment](DraftAssignment.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[AssignmentCreationInformation](AssignmentCreationInformation.md)<br/>
[DraftAssignment](DraftAssignment.md)<br/>
[DraftProject](DraftProject.md)<br/>
[DraftProjectResource](DraftProjectResource.md)<br/>
[DraftTask](DraftTask.md)<br/>
