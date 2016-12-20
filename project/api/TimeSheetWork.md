[comment]: # (Name:TimeSheetWork)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:23Z)

# TimeSheetWork

Represents the different types of work on a timesheet.



## Syntax

### CSOM

```C#
Class TimeSheetWork 
```
### JSOM

```
PS.TimeSheetWork
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines('{lineid}')/Work('{yyyy-MM-dd}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of actual work that is on a timesheet.|
|ActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|ActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of actual work that is on a timesheet.|
|Comment|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet work comment.|
|End|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the end time of the actual work that is on a timesheet.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the timesheet line that is associated with the work.|
|NonBillableOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of nonbillable overtime work that is on a timesheet.|
|NonBillableOvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|NonBillableOvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of nonbillable overtime work that is on a timesheet.|
|NonBillableWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of nonbillable work that is on a timesheet.|
|NonBillableWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|NonBillableWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of nonbillable work that is on a timesheet.|
|OvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of overtime work that is on a timesheet.|
|OvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|OvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of overtime work that is on a timesheet.|
|PlannedWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of planned work that is on a timesheet.|
|PlannedWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|PlannedWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of planned work that is on a timesheet.|
|Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the start time of the actual work that is on a timesheet.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the TimeSheetWork object.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the TimeSheetWork object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
