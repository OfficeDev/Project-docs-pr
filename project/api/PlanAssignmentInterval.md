[comment]: # (Name:PlanAssignmentInterval)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# PlanAssignmentInterval

Represents the collection of time intervals for a project plan assignment.



## Syntax

### CSOM

```C#
Class PlanAssignmentInterval 
```
### JSOM

```
PS.PlanAssignmentInterval
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')/Assignments('{assignmentid}')/Intervals('{yyyy-MM-dd}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Duration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timespan of the interval, expressed in a text string.|
|DurationMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|DurationTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the length of time for the plan assignment interval, in units of time.|
|End|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the end time of the plan assignment interval.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the plan assignment interval.|
|Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the start time of the plan assignment interval.|






## See Also
