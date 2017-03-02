[comment]: # (Name:Event)
[comment]: # (Name:Microsoft.ProjectServer.Event)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>Event class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents and identifies activity that occurs in Project Server when there are changes in business object data.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class Event 
```
### JSOM

```javascript
PS.Event
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.Event

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Events({id})
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="EventName"></a>EventName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of an event in Project Server.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the identifier of a Project Server event.|
|<a name="SourceName"></a>SourceName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of an event source.|

## <a name="seeAlso"></a>See Also

[EventCollection](EventCollection.md)<br/>
[EventHandler](EventHandler.md)<br/>
