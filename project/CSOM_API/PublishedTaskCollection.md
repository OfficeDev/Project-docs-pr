# PublishedTaskCollection class

Represents a collection of tasks in a published project.

## Syntax

### CSOM

```
class PublishedTaskCollection 
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
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets a task in the collection with the specified Guid.|
|[GetById(string id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets a task in the collection with the Id value.|


## Method Details

### <a name="getbyguid"></a> GetByGuid(Guid uid)

Gets a task in the collection with the specified Guid.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|A guid value.

#### Return Value

[PublishedTask](PublishedTask.md)<br />
The task in the published project.



### <a name="getbyid"></a>GetById(string id)

Gets a task in the collection with the Id value.

#### Syntax

```
GetById(string id)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| string|The string representation of the task Guid.

#### Return Value

[PublishedTask](PublishedTask.md)<br />
The task in the published project.



