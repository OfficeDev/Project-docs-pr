[comment]: # (Name:EventHandler)
[comment]: # (Name:Microsoft.ProjectServer.EventHandler)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EventHandler class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents the identification and location of a Project Server event handler.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EventHandler 
```
### JSOM

```javascript
PS.EventHandler
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.EventHandler

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/EventHandlers('{handlerid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="AssemblyName"></a>AssemblyName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the assembly that is associated with the event handler.|
|<a name="ClassName"></a>ClassName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the class that is associated with the event handler.|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the event handler.|
|<a name="EndpointUrl"></a>EndpointUrl|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Uri|Gets or sets the URL of the endpoint that is associated with the event handler.|
|<a name="Event"></a>Event|&#x2713;|&#x2713;|&#x2713;|[Event](Event.md)|Gets the event that triggers the event handler.|
|<a name="EventId"></a>EventId|||&#x2713;|Integer||
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the event handler.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the event handler.|
|<a name="Order"></a>Order|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the order of placement of the event handler in a list of event handlers that are associated with an event.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the event handler object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the event handler object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[EventHandlerCollection](EventHandlerCollection.md)<br/>
[EventHandlerCreationInformation](EventHandlerCreationInformation.md)<br/>
