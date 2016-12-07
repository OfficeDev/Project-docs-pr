# DraftTaskCollection class

Represents a collection of [DraftTask](DraftTask.md) objects.

## Syntax

### CSOM

```C#
class DraftTaskCollection Inherits ClientObjectCollection(of DraftTask)
```

### JSOM

```
PS.DraftTaskCollection
```

### REST Interface

This resource supports GET and POST HTTP commands:

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Draft/Tasks
```

## Members

### Properties

<!-- The following table has left-aligned columns 1,5,6; and center-aligned columns 2,3,4. -->

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|item| |&#x2713;| |DraftTask|Gets the current DraftTask from the collection.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[GetById(string id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|DraftTask|Gets a draft task from the collection with the Id value.|
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|DraftTask|Gets a draft task from the collection with the specified GUID.|
|[Add(TaskCreationInformation taskinfo)](#add)|&#x2713;|&#x2713;|&#x2713;|DraftTask|Adds the draft task that is specified by the TaskCreationInformation object to the collection.|
|[Remove(DraftTask task)](#remove)|&#x2713;|&#x2713;||Boolean|Removes the DraftTask from the collection. Returns true if successful.|


## Method Details

### <a name="getbyid"></a>GetById(string id)

Gets a draft task from the collection with the Id value.

#### Syntax

```
GetById(string id)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| string|The identifier of the referenced object.

#### Return Value

DraftTask<br />
The DraftTask with the specified ID.




### <a name="getbyguid"></a> GetByGuid(Guid uid)

Gets a draft task from the collection with the specified GUID.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|The guid that references the DraftTask.

#### Return Value

DraftTask<br />
The DraftTask with the specified guid.




### <a name="add"></a> Add(TaskCreationInformation taskinfo)

Adds the draft task that is specified by the TaskCreationInformation object to the collection.

#### Syntax

```
Add(TaskCreationInformation taskinfo)
```

#### Parameters


|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|taskinfo | TaskCreationInformation |Contains the properties that can be set when creating a task.|

#### Return Value

DraftTask<br />
The added task.


### <a name="remove"></a> Remove(DraftTask task)

Removes the DraftTask from the collection. Returns true if successful.

#### Syntax

```
Remove(DraftTask task)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|task | DraftTask |The project to remove from the collection.|

#### Return Value

Boolean<br />
Returns true if successful.

