[comment]: # (Name:EventCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# EventCollection

Represents a collection of [Event](f3d3f501-e74a-639b-e673-095f6e3602e7.md) objects.



## Syntax

### CSOM

```C#
Class EventCollection 
```
### JSOM

```
PS.EventCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Events
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[Event](Event.md)|Gets an event from the collection with the [Id](90040226-8c75-0cef-04aa-09744b3bfcf9.md) value.|
|[GetByInt(Integer id)](#GetByInt_Integer_id_)|&#x2713;|&#x2713;|&#x2713;|[Event](Event.md)|Gets an event from the collection with the specified integer identifier.|



## Method Details


### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets an event from the collection with the [Id](90040226-8c75-0cef-04aa-09744b3bfcf9.md) value.

#### Syntax

```
Event GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the event GUID.


#### Return Value

[Event](Event.md)

### <a id="GetByInt_Integer_id_"></a>GetByInt(Integer id)
 
Gets an event from the collection with the specified integer identifier.

#### Syntax

```
Event GetByInt(Int32 id)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| Integer | An integer identifier.


#### Return Value

[Event](Event.md)


## See Also
