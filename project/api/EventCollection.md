[comment]: # (Name:EventCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EventCollection class

inherits members from [ClientObjectCollection<Event>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [Event](Event.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class EventCollection 
```
### JSOM

```JavaScript
PS.EventCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.EventCollection

http://<sitecollection>/<site>/api/ProjectServer/Events
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[Event](Event.md)|Gets a [Event](Event.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[Event](Event.md)|Gets a [Event](Event.md) from the collection at the specified index.|

### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[Event](Event.md)|Gets a [Event](Event.md) from the collection with the Guid value.|
|[GetByInt(Integer id)](#GetByInt_Integer_id_)|&#x2713;|&#x2713;|&#x2713;|[Event](Event.md)|Gets an event from the collection with the specified integer identifier.|

<br/>
#### Method Details

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a [Event](Event.md) from the collection with the Guid value.

##### Syntax

```
Event GetById(String objectId)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [Event](Event.md)

##### Return Value

[Event](Event.md)

#### <a name="GetByInt_Integer_id_"></a>GetByInt(Integer id)
 
Gets an event from the collection with the specified integer identifier.

##### Syntax

```
Event GetByInt(Integer id)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| Integer | An integer identifier.

##### Return Value

[Event](Event.md)

## <a name="seeAlso"></a>See Also

[Event](Event.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
