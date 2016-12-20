[comment]: # (Name:PlanAssignmentCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# PlanAssignmentCollection

Represents a collection of plan assignment objects.



## Syntax

### CSOM

```C#
Class PlanAssignmentCollection 
```
### JSOM

```
PS.PlanAssignmentCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')/Assignments
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md) parameters)](#Add_[PlanAssignmentCreationInformation]_PlanAssignmentCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[PlanAssignment](PlanAssignment.md)|Adds a new plan assignment to the collection of plan assignments.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[PlanAssignment](PlanAssignment.md)|Gets a plan assignment from the collection, by using the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[PlanAssignment](PlanAssignment.md)|Gets a plan assignment from the collection, by using the specified object identifier.|
|[Remove([PlanAssignment](PlanAssignment.md) assignment)](#Remove_[PlanAssignment]_PlanAssignment.md__assignment_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified plan assignment from the collection of plan assignments.|



## Method Details


### <a id="Add_[PlanAssignmentCreationInformation]_PlanAssignmentCreationInformation.md__parameters_"></a>Add([PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md) parameters)
 
Adds a new plan assignment to the collection of plan assignments.

#### Syntax

```
PlanAssignment Add(PlanAssignmentCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md) | An object that contains information, for example name and GUID, about a new plan assignment.


#### Return Value

[PlanAssignment](PlanAssignment.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a plan assignment from the collection, by using the specified GUID.

#### Syntax

```
PlanAssignment GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[PlanAssignment](PlanAssignment.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a plan assignment from the collection, by using the specified object identifier.

#### Syntax

```
PlanAssignment GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | A string value that is the object identifier.


#### Return Value

[PlanAssignment](PlanAssignment.md)

### <a id="Remove_[PlanAssignment]_PlanAssignment.md__assignment_"></a>Remove([PlanAssignment](PlanAssignment.md) assignment)
 
Removes the specified plan assignment from the collection of plan assignments.

#### Syntax

```
Boolean Remove(PlanAssignment assignment)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|assignment| [PlanAssignment](PlanAssignment.md) | The PlanAssignment object to be removed.


#### Return Value

Boolean


## See Also
