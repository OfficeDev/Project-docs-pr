[comment]: # (Name:ResourceCalendarException)
[comment]: # (Name:Microsoft.ProjectServer.ResourceCalendarException)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ResourceCalendarException class

inherits members from [CalendarException](CalendarException.md)<br/>

<a name="description"></a>Represents a resource calendar exception.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ResourceCalendarException 
```
### JSOM

```javascript
PS.ResourceCalendarException
```
### REST Interface

Supported.

```
PS.ResourceCalendarException

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/ResourceCalendarExceptions({id})
```

## <a name="members"></a>Members

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the resource calendar exception object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the resource calendar exception object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[CalendarException](CalendarException.md)<br/>