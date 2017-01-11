[comment]: # (Name:PlanAssignmentCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PlanAssignmentCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [PlanAssignment](PlanAssignment.md).

## <a name="syntax"></a>Syntax

### CSOM

```C#
class PlanAssignmentCreationInformation 
```
### JSOM

```JavaScript
PS.PlanAssignmentCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.PlanAssignmentCreationInformation

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')/Assignments/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'BookingType':'value', 
		'Id':'value', 
		'Intervals':'value', 
		'ResourceId':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="BookingType"></a>BookingType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[BookingType](BookingType.md)|Gets or sets the booking type of the assignment.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the plan assignment.|
|<a name="Intervals"></a>Intervals|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[	PlanAssignmentIntervalCollection](PlanAssignmentIntervalCollection.md)|Gets or sets an enumerator that iterates through a collection of time intervals.|
|<a name="ResourceId"></a>ResourceId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the resource.|

## <a name="seeAlso"></a>See Also

[PlanAssignment](PlanAssignment.md)<br/>
[PlanAssignmentCollection](PlanAssignmentCollection.md)<br/>
[PlanAssignmentIntervalCollection](PlanAssignmentIntervalCollection.md)
