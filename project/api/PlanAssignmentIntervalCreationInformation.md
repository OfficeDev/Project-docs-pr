[comment]: # (Name:PlanAssignmentIntervalCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PlanAssignmentIntervalCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [PlanAssignmentInterval](PlanAssignmentInterval.md).

## <a name="syntax"></a>Syntax

### CSOM

```C#
class PlanAssignmentIntervalCreationInformation 
```
### JSOM

```JavaScript
PS.PlanAssignmentIntervalCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.PlanAssignmentIntervalCreationInformation

http://<sitecollection>/<site>/_api/ProjectServer/?????
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Duration':'value', 
		'Interval':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Duration"></a>Duration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timespan of the plan assignment interval, expressed in a text string.|
|<a name="Interval"></a>Interval|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the timescale division that is used to measure the amount of work that is being done.|

## <a name="seeAlso"></a>See Also

[PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md)
