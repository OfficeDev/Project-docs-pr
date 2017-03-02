[comment]: # (Name:EventCollection)
[comment]: # (Name:Microsoft.ProjectServer.EventCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EventCollection class

inherits members from [ClientObjectCollection<Event>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [Event](Event.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EventCollection 
```
### JSOM

```javascript
PS.EventCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.EventCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Events
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[Event](Event.md)|Gets a [Event](Event.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[Event](Event.md)|Gets a [Event](Event.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
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
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [Event](Event.md).|

##### Return Value

[Event](Event.md)

#### <a name="GetByInt_Integer_id_"></a>GetByInt(Integer id)
 
Gets an event from the collection with the specified integer identifier.

##### Syntax

```
Event GetByInt(Integer id)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id|Integer|An integer identifier.|

##### Return Value

[Event](Event.md)

## <a name="seeAlso"></a>See Also

[Event](Event.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
