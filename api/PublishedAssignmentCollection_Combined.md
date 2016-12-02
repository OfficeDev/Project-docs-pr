# PublishedAssignmentCollection class

Represents a collection of published assignments.

## Syntax

### CSOM

```C#
class PublishedAssignmentCollection Inherits ClientObjectCollection(of PublishedAssignment)
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
|item| |&#x2713;| |PublishedAssignment|Gets the current PublishedAssignment from the collection.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[GetById(string id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|PublishedAssignment|Gets a published assignment from the collection with the Id value.|
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|PublishedAssignment|Gets a published assignment from the collection with the specified GUID.|


## Method Details

### <a name="getbyid"></a>GetById(string id)

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

PublishedAssignment<br />
The assignment in the published project.


### <a name="getbyguid"></a> GetByGuid(Guid uid)

Gets a publisehd assignment from the collection with the specified GUID.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|A guid value.

#### Return Value

PublishedAssignment<br />
The assignment in the published project.


