[comment]: # (Name:PlanAssignmentCollection)
[comment]: # (Name:Microsoft.ProjectServer.PlanAssignmentCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PlanAssignmentCollection class

inherits members from [ClientObjectCollection<PlanAssignment>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of plan assignment objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PlanAssignmentCollection 
```
### JSOM

```javascript
PS.PlanAssignmentCollection
```
### REST Interface

Supported.

```
PS.PlanAssignmentCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')/Assignments
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[PlanAssignment](PlanAssignment.md)|Gets a [PlanAssignment](PlanAssignment.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[PlanAssignment](PlanAssignment.md)|Gets a [PlanAssignment](PlanAssignment.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{PlanAssignmentId}&#39;](#&#39;{PlanAssignmentId}&#39;)|||&#x2713;|[PlanAssignment](PlanAssignment.md)|Gets a [PlanAssignment](PlanAssignment.md) from the collection with the specified PlanAssignmentId.|
|[Add(PlanAssignmentCreationInformation parameters)](#Add_[PlanAssignmentCreationInformation]_PlanAssignmentCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[PlanAssignment](PlanAssignment.md)|Adds the [PlanAssignment](PlanAssignment.md) that is specified by the [PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[PlanAssignment](PlanAssignment.md)|Gets a [PlanAssignment](PlanAssignment.md) from the collection with the Guid value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[PlanAssignment](PlanAssignment.md)|Gets a [PlanAssignment](PlanAssignment.md) from the collection with the Id value.|
|[Remove(PlanAssignment assignment)](#Remove_[PlanAssignment]_PlanAssignment.md__assignment_)|&#x2713;|&#x2713;||Boolean|Removes the specified [PlanAssignment](PlanAssignment.md) from the collection.|

<br/>
#### Method Details

#### <a name="&#39;{PlanAssignmentId}&#39;"></a>&#39;{PlanAssignmentId}&#39;
 
Gets a [PlanAssignment](PlanAssignment.md) from the collection with the specified PlanAssignmentId.

##### Syntax

```
PlanAssignment http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')/Assignments('{PlanAssignmentId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|PlanAssignmentId|String|the id of the PlanAssignment|

##### Return Value

[PlanAssignment](PlanAssignment.md)

#### <a name="Add_[PlanAssignmentCreationInformation]_PlanAssignmentCreationInformation.md__parameters_"></a>Add([PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md) parameters)
 
Adds the [PlanAssignment](PlanAssignment.md) that is specified by the [PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md) object to the collection.

##### Syntax

```
PlanAssignment Add(PlanAssignmentCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md)|The properties that can be set when creating a plan assignment.|

##### Return Value

[PlanAssignment](PlanAssignment.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [PlanAssignment](PlanAssignment.md) from the collection with the Guid value.

##### Syntax

```
PlanAssignment GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [PlanAssignment](PlanAssignment.md)|

##### Return Value

[PlanAssignment](PlanAssignment.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [PlanAssignment](PlanAssignment.md) from the collection with the Id value.

##### Syntax

```
PlanAssignment GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [PlanAssignment](PlanAssignment.md).|

##### Return Value

[PlanAssignment](PlanAssignment.md)

#### <a name="Remove_[PlanAssignment]_PlanAssignment.md__assignment_"></a>Remove([PlanAssignment](PlanAssignment.md) assignment)
 
Removes the specified [PlanAssignment](PlanAssignment.md) from the collection.

##### Syntax

```
Boolean Remove(PlanAssignment assignment)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|assignment|[PlanAssignment](PlanAssignment.md)|The [PlanAssignment](PlanAssignment.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[PlanAssignment](PlanAssignment.md)<br/>
[PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md)<br/>
[ResourcePlan](ResourcePlan.md)<br/>
