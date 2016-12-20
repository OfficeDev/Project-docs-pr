[comment]: # (Name:PhaseCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# PhaseCollection

Represents a collection of workflow [Phase](c5336e3c-52c9-ca7e-ee4e-b280ae5269e0.md) objects.



## Syntax

### CSOM

```C#
Class PhaseCollection 
```
### JSOM

```
PS.PhaseCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Phases
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([PhaseCreationInformation](PhaseCreationInformation.md) parameters)](#Add_[PhaseCreationInformation]_PhaseCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[Phase](Phase.md)|Adds the workflow phase that is specified by the [PhaseCreationInformation](1a586a4b-6841-374f-9feb-7972b32cf606.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[Phase](Phase.md)|Gets a workflow phase from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[Phase](Phase.md)|Gets a workflow phase from the collection with the [Id](77b63b1b-26e1-3b48-166f-389b9e603fcf.md) value.|
|[Remove([Phase](Phase.md) phase)](#Remove_[Phase]_Phase.md__phase_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified workflow phase from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void|Updates the workflow phase collection.|



## Method Details


### <a id="Add_[PhaseCreationInformation]_PhaseCreationInformation.md__parameters_"></a>Add([PhaseCreationInformation](PhaseCreationInformation.md) parameters)
 
Adds the workflow phase that is specified by the [PhaseCreationInformation](1a586a4b-6841-374f-9feb-7972b32cf606.md) object to the collection.

#### Syntax

```
Phase Add(PhaseCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [PhaseCreationInformation](PhaseCreationInformation.md) | The properties of the workflow phase to create.


#### Return Value

[Phase](Phase.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a workflow phase from the collection with the specified GUID.

#### Syntax

```
Phase GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[Phase](Phase.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a workflow phase from the collection with the [Id](77b63b1b-26e1-3b48-166f-389b9e603fcf.md) value.

#### Syntax

```
Phase GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the workflow phase GUID.


#### Return Value

[Phase](Phase.md)

### <a id="Remove_[Phase]_Phase.md__phase_"></a>Remove([Phase](Phase.md) phase)
 
Removes the specified workflow phase from the collection.

#### Syntax

```
Boolean Remove(Phase phase)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|phase| [Phase](Phase.md) | The workflow phase to remove.


#### Return Value

Boolean

### <a id="Update__"></a>Update()
 
Updates the workflow phase collection.

#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
