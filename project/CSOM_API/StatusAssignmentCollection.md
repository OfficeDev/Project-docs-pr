[comment]: # (Name:StatusAssignmentCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# StatusAssignmentCollection

Represents a collection of [StatusAssignment](StatusAssignment.md) objects that comprise the assignments in a status update.



## Syntax

### CSOM

```
Class StatusAssignmentCollection 
```
### JSOM

```
PS.StatusAssignmentCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/EnterpriseResources('{resourceid}')/Assignments
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md) parameters)](#Add_[StatusAssignmentCreationInformation]_StatusAssignmentCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[StatusAssignment](StatusAssignment.md)|Adds the assignment that is specified by the [StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[StatusAssignment](StatusAssignment.md)|Gets a status assignment object from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[StatusAssignment](StatusAssignment.md)|Gets a status assignment object from the collection with the Id value.|
|[GetTimePhase(DateTime start, DateTime end)](#GetTimePhase_DateTime_start,_DateTime_end_)|&#x2713;|&#x2713;||[TimePhase](TimePhase.md)|Reads the timephased data for assignments that are within the specified start date and end date.|
|[GetTimePhaseByUrl(String start, String end)](#GetTimePhaseByUrl_String_start,_String_end_)|||&#x2713;|[TimePhase](TimePhase.md)||
|[Remove([StatusAssignment](StatusAssignment.md) assignment)](#Remove_[StatusAssignment]_StatusAssignment.md__assignment_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified assignment from the collection.|
|[SubmitAllStatusUpdates(String comment)](#SubmitAllStatusUpdates_String_comment_)|&#x2713;|&#x2713;|&#x2713;|void|Submit all updates to assignments in the StatusAssignmentCollection for approval.|
|[Update()](#Update)|&#x2713;|&#x2713;|&#x2713;|void|Updates the status assignment collection and saves changes in the collection to Project Server.|



## Method Details


### <a id="Add_[StatusAssignmentCreationInformation]_StatusAssignmentCreationInformation.md__parameters_"></a>Add([StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md) parameters)
 
Adds the assignment that is specified by the [StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md) object to the collection.

#### Syntax

```
StatusAssignment Add(StatusAssignmentCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md) | The properties of the status assignment to create.


#### Return Value

[StatusAssignment](StatusAssignment.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a status assignment object from the collection with the specified Guid.

#### Syntax

```
StatusAssignment GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A Guid value.


#### Return Value

[StatusAssignment](StatusAssignment.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a status assignment object from the collection with the specified Id value.

#### Syntax

```
StatusAssignment GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the Guid for the status assignment.


#### Return Value

[StatusAssignment](StatusAssignment.md)

### <a id="GetTimePhase_DateTime_start,_DateTime_end_"></a>GetTimePhase(DateTime start, DateTime end)
 
Reads the timephased data for assignments that are within the specified start date and end date.

#### Syntax

```
TimePhase GetTimePhase(DateTime start, DateTime end)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| DateTime | The start date.
|end| DateTime | The end date.


#### Return Value

[TimePhase](TimePhase.md)

### <a id="GetTimePhaseByUrl_String_start,_String_end_"></a>GetTimePhaseByUrl(String start, String end)
 


#### Syntax

```
TimePhase GetTimePhaseByUrl(String start, String end)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| String | The start date.
|end| String | The end date.


#### Return Value

[TimePhase](TimePhase.md)

### <a id="Remove_[StatusAssignment]_StatusAssignment.md__assignment_"></a>Remove([StatusAssignment](StatusAssignment.md) assignment)
 
Removes the specified assignment from the collection.

#### Syntax

```
Boolean Remove(StatusAssignment assignment)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|assignment| [StatusAssignment](StatusAssignment.md) | The assignment to remove.


#### Return Value

Boolean

### <a id="SubmitAllStatusUpdates_String_comment_"></a>SubmitAllStatusUpdates(String comment)
 
Submit all updates to assignments in the [StatusAssignmentCollection](StatusAssignmentCollection.md) for approval.

#### Syntax

```
void SubmitAllStatusUpdates(String comment)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|comment| String | The text comment for the status submission.


#### Return Value

void

### <a id="Update"></a>Update()
 
Updates the status assignment collection and saves changes in the collection to Project Server.

#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
