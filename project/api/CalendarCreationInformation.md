[comment]: # (Name:CalendarCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.CalendarCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>CalendarCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [Calendar](Calendar.md).

## <a name="syntax"></a>Syntax

### CSOM

```C#
class CalendarCreationInformation 
```
### JSOM

```JavaScript
PS.CalendarCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.CalendarCreationInformation

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Calendars/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Id':'value', 
		'Name':'value', 
		'OriginalId':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
[!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the new calendar.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the new calendar.|
|<a name="OriginalId"></a>OriginalId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the original GUID of the new calendar.|

## <a name="seeAlso"></a>See Also

[Calendar](Calendar.md)<br/>
[CalendarCollection](CalendarCollection.md)<br/>
