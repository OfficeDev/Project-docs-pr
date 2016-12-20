[comment]: # (Name:DraftTaskLinkCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# DraftTaskLinkCollection

Represents a collection of [DraftTaskLink](756bdcf9-908a-bb46-fca9-b4ebbe6c67e4.md) objects.



## Syntax

### CSOM

```C#
Class DraftTaskLinkCollection 
```
### JSOM

```
PS.DraftTaskLinkCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Draft/TaskLinks
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([TaskLinkCreationInformation](TaskLinkCreationInformation.md) parameters)](#Add_[TaskLinkCreationInformation]_TaskLinkCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[DraftTaskLink](DraftTaskLink.md)|Adds the draft task link that is specified by the [TaskLinkCreationInformation](b04589c3-9d29-7802-a139-de60af117d85.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[DraftTaskLink](DraftTaskLink.md)|Gets a draft task link from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[DraftTaskLink](DraftTaskLink.md)|Gets a draft task link from the collection with the [Id](a4048967-b356-2376-6df1-a2beff00d6b8.md) value.|
|[Remove([DraftTaskLink](DraftTaskLink.md) TaskLink)](#Remove_[DraftTaskLink]_DraftTaskLink.md__TaskLink_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified draft task link from the collection.|



## Method Details


### <a id="Add_[TaskLinkCreationInformation]_TaskLinkCreationInformation.md__parameters_"></a>Add([TaskLinkCreationInformation](TaskLinkCreationInformation.md) parameters)
 
Adds the draft task link that is specified by the [TaskLinkCreationInformation](b04589c3-9d29-7802-a139-de60af117d85.md) object to the collection.

#### Syntax

```
DraftTaskLink Add(TaskLinkCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [TaskLinkCreationInformation](TaskLinkCreationInformation.md) | The properties of the draft task link to create.


#### Return Value

[DraftTaskLink](DraftTaskLink.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a draft task link from the collection with the specified GUID.

#### Syntax

```
DraftTaskLink GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[DraftTaskLink](DraftTaskLink.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a draft task link from the collection with the [Id](a4048967-b356-2376-6df1-a2beff00d6b8.md) value.

#### Syntax

```
DraftTaskLink GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the task link GUID.


#### Return Value

[DraftTaskLink](DraftTaskLink.md)

### <a id="Remove_[DraftTaskLink]_DraftTaskLink.md__TaskLink_"></a>Remove([DraftTaskLink](DraftTaskLink.md) TaskLink)
 
Removes the specified draft task link from the collection.

#### Syntax

```
Boolean Remove(DraftTaskLink TaskLink)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|TaskLink| [DraftTaskLink](DraftTaskLink.md) | The draft task link to remove.


#### Return Value

Boolean


## See Also
