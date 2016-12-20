[comment]: # (Name:StageCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# StageCollection

Represents a collection of workflow [Stage](8ef9f206-088b-6ea9-0991-2b7a69de78af.md) objects.



## Syntax

### CSOM

```C#
Class StageCollection 
```
### JSOM

```
PS.StageCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Stages
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([StageCreationInformation](StageCreationInformation.md) parameters)](#Add_[StageCreationInformation]_StageCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Adds the workflow stage that is specified by the [StageCreationInformation](d0d8674b-6d31-a1b6-62a2-600612ab3a58.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets a workflow stage from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets a workflow stage from the collection with the [Id](936ed201-4f3e-e298-c362-b9d291d551bb.md) value.|
|[Remove([Stage](Stage.md) stage)](#Remove_[Stage]_Stage.md__stage_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified workflow stage from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void|Updates the workflow stage collection.|



## Method Details


### <a id="Add_[StageCreationInformation]_StageCreationInformation.md__parameters_"></a>Add([StageCreationInformation](StageCreationInformation.md) parameters)
 
Adds the workflow stage that is specified by the [StageCreationInformation](d0d8674b-6d31-a1b6-62a2-600612ab3a58.md) object to the collection.

#### Syntax

```
Stage Add(StageCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [StageCreationInformation](StageCreationInformation.md) | The properties of the workflow stage to create.


#### Return Value

[Stage](Stage.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a workflow stage from the collection with the specified GUID.

#### Syntax

```
Stage GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[Stage](Stage.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a workflow stage from the collection with the [Id](936ed201-4f3e-e298-c362-b9d291d551bb.md) value.

#### Syntax

```
Stage GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of a workflow stage GUID.


#### Return Value

[Stage](Stage.md)

### <a id="Remove_[Stage]_Stage.md__stage_"></a>Remove([Stage](Stage.md) stage)
 
Removes the specified workflow stage from the collection.

#### Syntax

```
Boolean Remove(Stage stage)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|stage| [Stage](Stage.md) | The workflow stage to remove.


#### Return Value

Boolean

### <a id="Update__"></a>Update()
 
Updates the workflow stage collection.

#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
