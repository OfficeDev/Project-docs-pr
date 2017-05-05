[comment]: # (Name:EventHandlerCollection)
[comment]: # (Name:Microsoft.ProjectServer.EventHandlerCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EventHandlerCollection class

inherits members from [ClientObjectCollection<EventHandler>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [EventHandler](EventHandler.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EventHandlerCollection 
```
### JSOM

```javascript
PS.EventHandlerCollection
```
### REST Interface

Supported.

```
PS.EventHandlerCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/EventHandlers
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[EventHandler](EventHandler.md)|Gets a [EventHandler](EventHandler.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[EventHandler](EventHandler.md)|Gets a [EventHandler](EventHandler.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{EventHandlerId}&#39;](#&#39;{EventHandlerId}&#39;)|||&#x2713;|[EventHandler](EventHandler.md)|Gets a [EventHandler](EventHandler.md) from the collection with the specified EventHandlerId.|
|[Add(EventHandlerCreationInformation parameters)](#Add_[EventHandlerCreationInformation]_EventHandlerCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[EventHandler](EventHandler.md)|Adds the [EventHandler](EventHandler.md) that is specified by the [EventHandlerCreationInformation](EventHandlerCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[EventHandler](EventHandler.md)|Gets a [EventHandler](EventHandler.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[EventHandler](EventHandler.md)|Gets a [EventHandler](EventHandler.md) from the collection with the Guid value.|
|[Remove(EventHandler handler)](#Remove_[EventHandler]_EventHandler.md__handler_)|&#x2713;|&#x2713;||Boolean|Removes the specified [EventHandler](EventHandler.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the event handler collection.|

<br/>
#### Method Details

#### <a name="&#39;{EventHandlerId}&#39;"></a>&#39;{EventHandlerId}&#39;
 
Gets a [EventHandler](EventHandler.md) from the collection with the specified EventHandlerId.

##### Syntax

```
EventHandler http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/EventHandlers('{EventHandlerId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|EventHandlerId|String|the id of the EventHandler|

##### Return Value

[EventHandler](EventHandler.md)

#### <a name="Add_[EventHandlerCreationInformation]_EventHandlerCreationInformation.md__parameters_"></a>Add([EventHandlerCreationInformation](EventHandlerCreationInformation.md) parameters)
 
Adds the [EventHandler](EventHandler.md) that is specified by the [EventHandlerCreationInformation](EventHandlerCreationInformation.md) object to the collection.

##### Syntax

```
EventHandler Add(EventHandlerCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[EventHandlerCreationInformation](EventHandlerCreationInformation.md)|The properties that can be set when creating a event handler.|

##### Return Value

[EventHandler](EventHandler.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [EventHandler](EventHandler.md) from the collection with the Id value.

##### Syntax

```
EventHandler GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [EventHandler](EventHandler.md)|

##### Return Value

[EventHandler](EventHandler.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [EventHandler](EventHandler.md) from the collection with the Guid value.

##### Syntax

```
EventHandler GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [EventHandler](EventHandler.md).|

##### Return Value

[EventHandler](EventHandler.md)

#### <a name="Remove_[EventHandler]_EventHandler.md__handler_"></a>Remove([EventHandler](EventHandler.md) handler)
 
Removes the specified [EventHandler](EventHandler.md) from the collection.

##### Syntax

```
Boolean Remove(EventHandler handler)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|handler|[EventHandler](EventHandler.md)|The [EventHandler](EventHandler.md) to remove.|

##### Return Value

Boolean

#### <a name="Update__"></a>Update()
 
Updates the event handler collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[EventHandler](EventHandler.md)<br/>
[EventHandlerCreationInformation](EventHandlerCreationInformation.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
