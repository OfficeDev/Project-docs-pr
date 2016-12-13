# DraftTaskCollection class

Represents a collection of [DraftTask](DraftTask.md) objects.

## Syntax

### CSOM

```
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
|item| |&#x2713;| |[DraftTask](DraftTask.md)|Gets the current draft task from the collection.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[Add(TaskCreationInformation taskinfo)](#add)|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Adds the draft task that is specified by the [TaskCreationInformation](TaskCreationInformation.md) object to the collection.||
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Gets a draft task from the collection with the specified GUID.|
|[GetById(String id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Gets a draft task from the collection with the Id value.|
|[Remove(DraftTask task)](#remove)|&#x2713;|&#x2713;||Boolean|Removes the draft task from the collection. Returns true if successful.|


## Method Details

### <a name="add"></a> Add(TaskCreationInformation taskinfo)

Adds the draft task that is specified by the [TaskCreationInformation](TaskCreationInformation.md) object to the collection.

#### Syntax

```
Add(TaskCreationInformation taskinfo)
```

#### Parameters


|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|taskinfo | TaskCreationInformation |Contains the properties that can be set when creating a task.|

#### Return Value

[DraftTask](DraftTask.md)<br />
The added task.



### <a name="getbyguid"></a> GetByGuid(Guid uid)

Gets a draft task from the collection with the specified GUID.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|The guid that references the [DraftTask](DraftTask.md).

#### Return Value

[DraftTask](DraftTask.md)<br />
The [DraftTask](DraftTask.md) with the specified guid.



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

[DraftTask](DraftTask.md)<br />
The [DraftTask](DraftTask.md) with the specified ID.





### <a name="remove"></a> Remove(DraftTask task)

Removes the specified draft task from the collection. Returns true if successful.

#### Syntax

```
Remove(DraftTask task)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|task | [DraftTask](DraftTask.md) |The draft task to remove from the collection.|

#### Return Value

Boolean<br />
Returns true if successful.

