[comment]: # (Name:EventHandlerCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.EventHandlerCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EventHandlerCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [EventHandler](EventHandler.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EventHandlerCreationInformation 
```
### JSOM

```javascript
PS.EventHandlerCreationInformation
```
### REST Interface

Supported.

```
PS.EventHandlerCreationInformation

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/EventHandlers/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'AssemblyName':'value', 
		'ClassName':'value', 
		'Description':'value', 
		'EndpointUrl':'value', 
		'EventId':'value', 
		'Id':'value', 
		'Name':'value', 
		'Order':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="AssemblyName"></a>AssemblyName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the assembly that is associated with the event handler.|
|<a name="ClassName"></a>ClassName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the class that is associated with the event handler.|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the event handler.|
|<a name="EndpointUrl"></a>EndpointUrl|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Uri|Gets or sets the network location of the event handler.|
|<a name="EventId"></a>EventId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the GUID of the event that triggers the event handler.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the event handler.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the event handler.|
|<a name="Order"></a>Order|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the order of placement of an event handler in a list of event handlers that are triggered by an event.|

## <a name="seeAlso"></a>See Also

[EventHandler](EventHandler.md)<br/>
[EventHandlerCollection](EventHandlerCollection.md)<br/>
