[comment]: # (Name:PlanAssignmentInterval)
[comment]: # (Name:Microsoft.ProjectServer.PlanAssignmentInterval)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PlanAssignmentInterval class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents the collection of time intervals for a project plan assignment.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PlanAssignmentInterval 
```
### JSOM

```javascript
PS.PlanAssignmentInterval
```
### REST Interface

Supported.

```
PS.PlanAssignmentInterval

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')/Assignments('{assignmentid}')/Intervals('{yyyy-MM-dd}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Duration"></a>Duration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timespan of the interval, expressed in a text string.|
|<a name="DurationMilliseconds"></a>DurationMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the plan assignment interval.|
|<a name="DurationTimeSpan"></a>DurationTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the length of time for the plan assignment interval, in units of time.|
|<a name="End"></a>End|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the end time of the plan assignment interval.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the plan assignment interval.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the start time of the plan assignment interval.|

## <a name="seeAlso"></a>See Also

[PlanAssignmentIntervalCollection](PlanAssignmentIntervalCollection.md)<br/>
