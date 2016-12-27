[comment]: # (Name:DraftAssignmentCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>DraftAssignmentCollection class

inherits members from [ClientObjectCollection<DraftAssignment>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [DraftAssignment](DraftAssignment.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class DraftAssignmentCollection 
```

### JSOM

```JavaScript
PS.DraftAssignmentCollection
```

### REST Interface

This resource supports GET and POST HTTP commands.

```
PS.DraftAssignmentCollection

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Draft/Assignments
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties


|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[DraftAssignment](DraftAssignment.md)|Gets a [DraftAssignment](DraftAssignment.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[DraftAssignment](DraftAssignment.md)|Gets a [DraftAssignment](DraftAssignment.md) from the collection at the specified index.|

### <a name="methods"></a>Methods


|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[&#39;{DraftAssignmentId}&#39;](#&#39;{DraftAssignmentId}&#39;)|||&#x2713;|[DraftAssignment](DraftAssignment.md)|Gets a [DraftAssignment](DraftAssignment.md) from the collection with the specified DraftAssignmentId.|
|[Add(AssignmentCreationInformation parameters)](#Add_[AssignmentCreationInformation]_AssignmentCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[DraftAssignment](DraftAssignment.md)|Adds the draft assignment that is specified by the [AssignmentCreationInformation](AssignmentCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[DraftAssignment](DraftAssignment.md)|Gets a draft assignment from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[DraftAssignment](DraftAssignment.md)|Gets a draft assignment from the collection with the Id value.|
|[Remove(DraftAssignment assignment)](#Remove_[DraftAssignment]_DraftAssignment.md__assignment_)|&#x2713;|&#x2713;||Boolean|Removes the specified draft assignment from the collection.|

<br/>
#### Method Details

#### <a name="&#39;{DraftAssignmentId}&#39;"></a>&#39;{DraftAssignmentId}&#39;
 
Gets a [DraftAssignment](DraftAssignment.md) from the collection with the specified DraftAssignmentId.

##### Syntax

```
DraftAssignment http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Draft/Assignments('{DraftAssignmentId}')
```

##### Parameters

None

##### Return Value

[DraftAssignment](DraftAssignment.md)

#### <a name="Add_[AssignmentCreationInformation]_AssignmentCreationInformation.md__parameters_"></a>Add([AssignmentCreationInformation](AssignmentCreationInformation.md) parameters)

Adds the draft assignment that is specified by the [AssignmentCreationInformation](AssignmentCreationInformation.md) object to the collection.

##### Syntax

```
DraftAssignment Add(AssignmentCreationInformation parameters)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [AssignmentCreationInformation](AssignmentCreationInformation.md) | The properties of the draft assignment to create.

##### Return Value

[DraftAssignment](DraftAssignment.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)

Gets a draft assignment from the collection with the specified GUID.

##### Syntax

```
DraftAssignment GetByGuid(Guid uid)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.

##### Return Value

[DraftAssignment](DraftAssignment.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a draft assignment from the collection with the Id value.

##### Syntax

```
DraftAssignment GetById(String objectId)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the assignment GUID.

##### Return Value

[DraftAssignment](DraftAssignment.md)

#### <a name="Remove_[DraftAssignment]_DraftAssignment.md__assignment_"></a>Remove([DraftAssignment](DraftAssignment.md) assignment)

Removes the specified draft assignment from the collection.

##### Syntax

```
Boolean Remove(DraftAssignment assignment)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|assignment| [DraftAssignment](DraftAssignment.md) | The draft assignment to remove.

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[AssignmentCreationInformation](AssignmentCreationInformation.md)<br/>
[DraftAssignment](DraftAssignment.md)<br/>
[DraftProject](DraftProject.md)<br/>
[DraftProjectResource](DraftProjectResource.md)<br/>
[DraftTask](DraftTask.md)<br/>
