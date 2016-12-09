# DraftAssignmentCollection class

Represents a collection of [DraftAssignment](DraftAssignment.md) objects.

## Syntax

### CSOM

```C#
class DraftAssignmentCollection Inherits ClientObjectCollection(of DraftAssignment)
```

### JSOM

```
PS.DraftAssignmentCollection
```

### REST Interface

This resource supports GET and POST HTTP commands:

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Draft/Assignments
```

## Members

### Properties

<!-- The following table has left-aligned columns 1,5,6; and center-aligned columns 2,3,4. -->

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|item| |&#x2713;| |[DraftAssignment](DraftAssignment.md)|Gets the current [DraftAssignment](DraftAssignment.md) from the collection.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[GetById(string id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|[DraftAssignment](DraftAssignment.md)|Gets a draft assignment from the collection with the Id value.|
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|[DraftAssignment](DraftAssignment.md)|Gets a draft assignment from the collection with the specified GUID.|
|[Add(AssignmentCreationInformation acinfo)](#add)|&#x2713;|&#x2713;|&#x2713;|[DraftAssignment](DraftAssignment.md)|Adds the draft assignment that is specified by the [AssignmentCreationInformation](AssignmentCreationInformation.md) object to the collection.|
|[Remove(DraftAssignment assignment)](#remove)|&#x2713;|&#x2713;||Boolean|Removes the specified draft assignment from the collection. Returns true if successful.|


## Method Details

### <a name="getbyid"></a>GetById(string oid)

Gets a draft assignment from the collection with the Id value.

#### Syntax

```
GetById(string oid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| string|The identifier of the referenced object.

#### Return Value

[DraftAssignment](DraftAssignment.md)<br />
The draft assignment with the specified ID.




### <a name="getbyguid"></a> GetByGuid(Guid uid)

Gets a draft assignment from the collection with the specified GUID.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|The guid that references the draft assignment.

#### Return Value

[DraftAssignment](DraftAssignment.md)<br />
The DraftAssignment with the specified guid.




### <a name="add"></a> Add(AssignmentCreationInformation acinfo)

Adds the draft assignment that is specified by the [AssignmentCreationInformation](AssignmentCreationInformation.md) object to the collection.

#### Syntax

```
Add(AssignmentCreationInformation Assignmentinfo)
```

#### Parameters


|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|acinfo | [AssignmentCreationInformation](AssignmentCreationInformation.md) |Contains the properties that can be set when creating a [Assignment](Assignment.md).|

#### Return Value

[DraftAssignment](DraftAssignment.md)<br />
The added Assignment.


### <a name="remove"></a> Remove(DraftAssignment assignment)

Removes the [DraftAssignment](DraftAssignment.md) from the collection. Returns true if successful.

#### Syntax

```
Remove(DraftAssignment Assignment))
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|assignment | [DraftAssignment](DraftAssignment.md) |The project to remove from the collection.|

#### Return Value

Boolean<br />
Returns true if successful.

