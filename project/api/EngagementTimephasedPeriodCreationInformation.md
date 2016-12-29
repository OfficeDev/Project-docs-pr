[comment]: # (Name:EngagementTimephasedPeriodCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>EngagementTimephasedPeriodCreationInformation class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```C#
class EngagementTimephasedPeriodCreationInformation 
```
### JSOM

```JavaScript
PS.EngagementTimephasedPeriodCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.EngagementTimephasedPeriodCreationInformation

http://<sitecollection>/<site>/_api/ProjectServer/?????
```
POST Example
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

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="End"></a>End|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="MaxUnits"></a>MaxUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double||
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="Work"></a>Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String||
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan||

## <a name="seeAlso"></a>See Also

