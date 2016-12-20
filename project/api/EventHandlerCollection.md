[comment]: # (Name:EventHandlerCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# EventHandlerCollection

Represents a collection of [EventHandler](bf4842f3-2584-e397-7928-53344b68db86.md) objects.



## Syntax

### CSOM

```C#
Class EventHandlerCollection 
```
### JSOM

```
PS.EventHandlerCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/EventHandlers
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([EventHandlerCreationInformation](EventHandlerCreationInformation.md) parameters)](#Add_[EventHandlerCreationInformation]_EventHandlerCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[EventHandler](EventHandler.md)|Adds the event handler that is specified by the [EventHandlerCreationInformation](c026da35-57f5-7ca4-fd5e-e3f57a58e6a4.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[EventHandler](EventHandler.md)|Gets an event handler from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[EventHandler](EventHandler.md)|Get an event handler element from the collection using the object ID.|
|[Remove([EventHandler](EventHandler.md) handler)](#Remove_[EventHandler]_EventHandler.md__handler_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified event handler from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void|Updates the event handler collection.|



## Method Details


### <a id="Add_[EventHandlerCreationInformation]_EventHandlerCreationInformation.md__parameters_"></a>Add([EventHandlerCreationInformation](EventHandlerCreationInformation.md) parameters)
 
Adds the event handler that is specified by the [EventHandlerCreationInformation](c026da35-57f5-7ca4-fd5e-e3f57a58e6a4.md) object to the collection.

#### Syntax

```
EventHandler Add(EventHandlerCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [EventHandlerCreationInformation](EventHandlerCreationInformation.md) | The properties of the event handler to create.


#### Return Value

[EventHandler](EventHandler.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets an event handler from the collection with the specified GUID.

#### Syntax

```
EventHandler GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[EventHandler](EventHandler.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Get an event handler element from the collection using the object ID.

#### Syntax

```
EventHandler GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The object ID in string form.


#### Return Value

[EventHandler](EventHandler.md)

### <a id="Remove_[EventHandler]_EventHandler.md__handler_"></a>Remove([EventHandler](EventHandler.md) handler)
 
Removes the specified event handler from the collection.

#### Syntax

```
Boolean Remove(EventHandler handler)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|handler| [EventHandler](EventHandler.md) | The event handler to remove.


#### Return Value

Boolean

### <a id="Update__"></a>Update()
 
Updates the event handler collection.

#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
