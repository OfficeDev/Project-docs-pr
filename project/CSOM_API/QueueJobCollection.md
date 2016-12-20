[comment]: # (Name:QueueJobCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# QueueJobCollection

Represents a collection of QueueJob objects.



## Syntax

### CSOM

```C#
Class QueueJobCollection 
```
### JSOM

```
PS.QueueJobCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/QueueJobs
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Gets a queue job from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Gets a queue job from the collection with the [Id](6b36690a-0871-f067-635a-bc6b265e2e66.md) value.|



## Method Details


### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a queue job from the collection with the specified GUID.

#### Syntax

```
QueueJob GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[QueueJob](QueueJob.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a queue job from the collection with the [Id](6b36690a-0871-f067-635a-bc6b265e2e66.md) value.

#### Syntax

```
QueueJob GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the queue job GUID.


#### Return Value

[QueueJob](QueueJob.md)


## See Also
