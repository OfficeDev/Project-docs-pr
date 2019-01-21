[comment]: # (Name:StatusAssignmentCollection)
[comment]: # (Name:Microsoft.ProjectServer.StatusAssignmentCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StatusAssignmentCollection class

inherits members from [ClientObjectCollection<StatusAssignment>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [StatusAssignment](StatusAssignment.md) objects, which are assignments in a status update.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StatusAssignmentCollection 
```
### JSOM

```javascript
PS.StatusAssignmentCollection
```
### REST Interface

Supported.

```
PS.StatusAssignmentCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Assignments
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[StatusAssignment](StatusAssignment.md)|Gets a [StatusAssignment](StatusAssignment.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[StatusAssignment](StatusAssignment.md)|Gets a [StatusAssignment](StatusAssignment.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{StatusAssignmentId}&#39;](#&#39;{StatusAssignmentId}&#39;)|||&#x2713;|[StatusAssignment](StatusAssignment.md)|Gets a [StatusAssignment](StatusAssignment.md) from the collection with the specified StatusAssignmentId.|
|[Add(StatusAssignmentCreationInformation parameters)](#Add_[StatusAssignmentCreationInformation]_StatusAssignmentCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[StatusAssignment](StatusAssignment.md)|Adds the [StatusAssignment](StatusAssignment.md) that is specified by the [StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[StatusAssignment](StatusAssignment.md)|Gets a [StatusAssignment](StatusAssignment.md) from the collection with the Guid value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[StatusAssignment](StatusAssignment.md)|Gets a [StatusAssignment](StatusAssignment.md) from the collection with the Id value.|
|[GetTimePhase(DateTime start, DateTime end)](#GetTimePhase_DateTime_start,_DateTime_end_)|&#x2713;|&#x2713;||[TimePhase](TimePhase.md)|Reads the timephased data for assignments that are within the specified start date and end date.|
|[GetTimePhaseByUrl(String start, String end)](#GetTimePhaseByUrl_String_start,_String_end_)|||&#x2713;|[TimePhase](TimePhase.md)||
|[Remove(StatusAssignment assignment)](#Remove_[StatusAssignment]_StatusAssignment.md__assignment_)|&#x2713;|&#x2713;||Boolean|Removes the specified [StatusAssignment](StatusAssignment.md) from the collection.|
|[SubmitAllStatusUpdates(String comment)](#SubmitAllStatusUpdates_String_comment_)|&#x2713;|&#x2713;|&#x2713;|void|Submit all updates to assignments in the StatusAssignmentCollection for approval.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the status assignment collection.|

<br/>
#### Method Details

#### <a name="&#39;{StatusAssignmentId}&#39;"></a>&#39;{StatusAssignmentId}&#39;
 
Gets a [StatusAssignment](StatusAssignment.md) from the collection with the specified StatusAssignmentId.

##### Syntax

```
StatusAssignment http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Assignments('{StatusAssignmentId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|StatusAssignmentId|String|the id of the StatusAssignment|

##### Return Value

[StatusAssignment](StatusAssignment.md)

#### <a name="Add_[StatusAssignmentCreationInformation]_StatusAssignmentCreationInformation.md__parameters_"></a>Add([StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md) parameters)
 
Adds the [StatusAssignment](StatusAssignment.md) that is specified by the [StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md) object to the collection.

##### Syntax

```
StatusAssignment Add(StatusAssignmentCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md)|The properties that can be set when creating a status assignment.|

##### Return Value

[StatusAssignment](StatusAssignment.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [StatusAssignment](StatusAssignment.md) from the collection with the Guid value.

##### Syntax

```
StatusAssignment GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [StatusAssignment](StatusAssignment.md)|

##### Return Value

[StatusAssignment](StatusAssignment.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [StatusAssignment](StatusAssignment.md) from the collection with the Id value.

##### Syntax

```
StatusAssignment GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [StatusAssignment](StatusAssignment.md).|

##### Return Value

[StatusAssignment](StatusAssignment.md)

#### <a name="GetTimePhase_DateTime_start,_DateTime_end_"></a>GetTimePhase(DateTime start, DateTime end)
 
Reads the timephased data for assignments that are within the specified start date and end date.

##### Syntax

```
TimePhase GetTimePhase(DateTime start, DateTime end)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start|DateTime|The start date.|
|end|DateTime|The end date.|

##### Return Value

[TimePhase](TimePhase.md)

#### <a name="GetTimePhaseByUrl_String_start,_String_end_"></a>GetTimePhaseByUrl(String start, String end)
 
Reads the timephased data for assignments that are within the specified start date and end date. 

##### Syntax

```
TimePhase GetTimePhaseByUrl(String start, String end)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start|DateTime|The start date.|
|end|DateTime|The end date.|

##### Return Value

[TimePhase](TimePhase.md)

#### <a name="Remove_[StatusAssignment]_StatusAssignment.md__assignment_"></a>Remove([StatusAssignment](StatusAssignment.md) assignment)
 
Removes the specified [StatusAssignment](StatusAssignment.md) from the collection.

##### Syntax

```
Boolean Remove(StatusAssignment assignment)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|assignment|[StatusAssignment](StatusAssignment.md)|The [StatusAssignment](StatusAssignment.md) to remove.|

##### Return Value

Boolean

#### <a name="SubmitAllStatusUpdates_String_comment_"></a>SubmitAllStatusUpdates(String comment)
 
Submit all updates to assignments in the StatusAssignmentCollection for approval.

##### Syntax

```
void SubmitAllStatusUpdates(String comment)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|comment|String|The text comment for the status submission.|

##### Return Value

void

#### <a name="Update__"></a>Update()
 
Updates the status assignment collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[EnterpriseResource](EnterpriseResource.md)<br/>
[StatusAssignment](StatusAssignment.md)<br/>
[StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md)<br/>
[TimePhase](TimePhase.md)<br/>
