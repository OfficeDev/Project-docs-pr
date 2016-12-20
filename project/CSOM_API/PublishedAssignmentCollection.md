# PublishedAssignmentCollection class

Represents a collection of published assignments.

## Syntax

### CSOM

```
class PublishedAssignmentCollection
```

### JSOM

```
PS.PublishedAssignmentCollection
```

### REST Interface

This resource supports GET HTTP command:

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Assignments
```

## Members

### Properties

<!-- The following table has left-aligned columns 1,5,6; and center-aligned columns 2,3,4. -->

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|item| |&#x2713;| |[PublishedAssignment](PublishedAssignment.md)|Gets the current PublishedAssignment from the collection.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignment](PublishedAssignment.md)|Gets a published assignment from the collection with the specified Guid.|
|[GetById(String id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignment](PublishedAssignment.md)|Gets a published assignment from the collection with the Id value.|


## Method Details

### <a name="getbyguid"></a> GetByGuid(Guid uid)

Gets a published assignment from the collection with the specified Guid.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|A Guid value.

#### Return Value

[PublishedAssignment](PublishedAssignment.md)<br />
The assignment in the published project.


### <a name="getbyid"></a>GetById(String id)

Gets a published assignment from the collection with the Id value.

#### Syntax

```
GetById(string id)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| string|The string representation of the published assignment GUID.

#### Return Value

[PublishedAssignment](PublishedAssignment.md)<br />
The assignment in the published project.

