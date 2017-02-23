[comment]: # (Name:ResourceCalendarException)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ResourceCalendarException class

inherits members from [CalendarException](CalendarException.md)<br/>

<a name="description"></a>Represents a resource calendar exception.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class ResourceCalendarException 
```
### JSOM

```JavaScript
PS.ResourceCalendarException
```
### REST Interface

This resource supports POST and DELETE HTTP commands.

```
PS.ResourceCalendarException

http://<sitecollection>/<site>/api/ProjectServer/EnterpriseResources('{resourceid}')/ResourceCalendarExceptions({id})
```

## <a name="members"></a>Members

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
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