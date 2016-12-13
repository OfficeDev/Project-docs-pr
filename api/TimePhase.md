[comment]: # (Name:TimePhase)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# TimePhase

Represents assignment progress information that is distributed over time.



## Syntax

### CSOM

```C#
Class TimePhase 
```
### JSOM

```
PS.TimePhase
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/EnterpriseResources('{resourceid}')/Assignments/GetTimePhaseByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Assignments|&#x2713;|&#x2713;|&#x2713;|[StatusAssignmentCollection](StatusAssignmentCollection.md)|Gets the status of assignments associated with a timephase.|
|End|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the end date of a timephase period.|
|Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the start date of the timephase period.|






## See Also
