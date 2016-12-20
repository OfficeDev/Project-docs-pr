[comment]: # (Name:PlanAssignmentIntervalCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# PlanAssignmentIntervalCollection

Represents a collection of PlanAssignmentInterval objects.



## Syntax

### CSOM

```C#
Class PlanAssignmentIntervalCollection 
```
### JSOM

```
PS.PlanAssignmentIntervalCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')/Assignments('{assignmentid}')/Intervals
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetById(String id)](#GetById_String_id_)|&#x2713;|&#x2713;|&#x2713;|[PlanAssignmentInterval](PlanAssignmentInterval.md)|Gets a plan assignment interval from the collection of plan assignment intervals, with the specified object identifier.|
|[GetByStart(DateTime start)](#GetByStart_DateTime_start_)|&#x2713;|&#x2713;|&#x2713;|[PlanAssignmentInterval](PlanAssignmentInterval.md)|Gets a plan assignment interval from the collection of plan assignment intervals, with the specified start date.|



## Method Details


### <a id="GetById_String_id_"></a>GetById(String id)
 
Gets a plan assignment interval from the collection of plan assignment intervals, with the specified object identifier.

#### Syntax

```
PlanAssignmentInterval GetById(String id)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| String | A string value that represents an identifier for a plan assignment interval object.


#### Return Value

[PlanAssignmentInterval](PlanAssignmentInterval.md)

### <a id="GetByStart_DateTime_start_"></a>GetByStart(DateTime start)
 
Gets a plan assignment interval from the collection of plan assignment intervals, with the specified start date.

#### Syntax

```
PlanAssignmentInterval GetByStart(DateTime start)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| DateTime | A start date.


#### Return Value

[PlanAssignmentInterval](PlanAssignmentInterval.md)


## See Also
