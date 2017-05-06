[comment]: # (Name:EngagementCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.EngagementCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EngagementCreationInformation class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Contains the properties that can be set when creating a [Engagement](Engagement.md).  Please see [ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EngagementCreationInformation 
```
### JSOM

```javascript
PS.EngagementCreationInformation
```
### REST Interface

Supported.

```
PS.EngagementCreationInformation

```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Description':'value', 
		'Finish':'value', 
		'Id':'value', 
		'MaxUnits':'value', 
		'ResourceId':'value', 
		'Start':'value', 
		'TimephasedPeriodData':'value', 
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
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String||
|<a name="Finish"></a>Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid||
|<a name="MaxUnits"></a>MaxUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double||
|<a name="ResourceId"></a>ResourceId|||&#x2713;&#x02B7;|Guid||
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="TimephasedPeriodData"></a>TimephasedPeriodData|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Collection([EngagementTimephasedPeriodCreationInformation](EngagementTimephasedPeriodCreationInformation.md))||
|<a name="Work"></a>Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String||
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan||

## <a name="seeAlso"></a>See Also


[EngagementTimephasedPeriodCreationInformation](EngagementTimephasedPeriodCreationInformation.md)<br/>
[ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md)<br/>
