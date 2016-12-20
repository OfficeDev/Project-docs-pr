[comment]: # (Name:PublishedTaskLinkCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# PublishedTaskLinkCollection

Represents a collection of task links in a published project.



## Syntax

### CSOM

```C#
Class PublishedTaskLinkCollection 
```
### JSOM

```
PS.PublishedTaskLinkCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/TaskLinks
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLink](PublishedTaskLink.md)|Gets a task link from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLink](PublishedTaskLink.md)|Returns a task link in the collection with the [Id](a4048967-b356-2376-6df1-a2beff00d6b8.md) value.|



## Method Details


### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a task link from the collection with the specified GUID.

#### Syntax

```
PublishedTaskLink GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[PublishedTaskLink](PublishedTaskLink.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Returns a task link in the collection with the [Id](a4048967-b356-2376-6df1-a2beff00d6b8.md) value.

#### Syntax

```
PublishedTaskLink GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the task link GUID.


#### Return Value

[PublishedTaskLink](PublishedTaskLink.md)


## See Also
