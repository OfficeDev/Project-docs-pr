[comment]: # (Name:EngagementTimephasedPeriodCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.EngagementTimephasedPeriodCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EngagementTimephasedPeriodCreationInformation class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EngagementTimephasedPeriodCreationInformation 
```
### JSOM

```javascript
PS.EngagementTimephasedPeriodCreationInformation
```
### REST Interface

Supported.

```
PS.EngagementTimephasedPeriodCreationInformation

```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'End':'value', 
		'MaxUnits':'value', 
		'Start':'value', 
		'Work':'value', 
		'WorkMilliseconds':'value', 
		'WorkTimeSpan':'value'		
	}
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="End"></a>End|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="MaxUnits"></a>MaxUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double||
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="Work"></a>Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String||
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan||

## <a name="seeAlso"></a>See Also

[EngagementCreationInformation](EngagementCreationInformation.md)<br/>