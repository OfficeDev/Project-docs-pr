# PublishedTaskCollection class

Represents a collection of tasks in a published project.

## Syntax

### CSOM

```C#
class PublishedTaskCollection Inherits ClientObjectCollection(of PublishedTask)
```

### JSOM

```
PS.PublishedTaskCollection
```

### REST Interface

This resource supports GET HTTP command:

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Tasks
```

## Members

### Properties

<!-- The following table has left-aligned columns 1,5,6; and center-aligned columns 2,3,4. -->

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|item| |&#x2713;| |PublishedTask|Gets the current PublishedTask from the collection.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[GetById(string id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|PublishedTask|Gets a task in the collection with the Id value.|
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|PublishedTask|Gets a task in the collection with the specified GUID.|


## Method Details

### <a name="getbyid"></a>GetById(string id)

Gets a task in the collection with the Id value.

#### Syntax

```
GetById(string id)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| string|The string representation of the task GUID.

#### Return Value

PublishedTask<br />
The task in the published project.


### <a name="getbyguid"></a> GetByGuid(Guid uid)

Gets a task in the collection with the specified GUID.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|A guid value.

#### Return Value

PublishedTask<br />
The task in the published project.


