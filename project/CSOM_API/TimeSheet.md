[comment]: # (Name:TimeSheet)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# TimeSheet

Contains the methods and properties for managing a timesheet.



## Syntax

### CSOM

```C#
Class TimeSheet 
```
### JSOM

```
PS.TimeSheet
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Comments|&#x2713;|&#x2713;|&#x2713;|String|Gets the timesheet comments.|
|Creator|&#x2713;|&#x2713;|&#x2713;|SPUser|Gets the timesheet creator.|
|EntryMode|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TimeSheetEntryMode](TimeSheetEntryMode.md)|Gets or sets the timesheet entry mode.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the time sheet.|
|IsControlledByOwner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the timesheet is controlled by the owner.|
|IsProcessed|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the timesheet is finalized and should not be changed.|
|Lines|&#x2713;|&#x2713;|&#x2713;|[TimeSheetLineCollection](TimeSheetLineCollection.md)|Gets the collection of lines in the timesheet.|
|Manager|&#x2713;|&#x2713;|&#x2713;|SPUser|Gets the timesheet manager.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet name.|
|Period|&#x2713;|&#x2713;|&#x2713;|[TimeSheetPeriod](TimeSheetPeriod.md)|Gets the timesheet period.|
|Status|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TimeSheetStatus](TimeSheetStatus.md)|Gets or sets the timesheet line status.|
|TotalActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet total actual work.|
|TotalActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|TotalActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the timesheet total actual work.|
|TotalNonBillableOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet total non-billable overtime work.|
|TotalNonBillableOvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|TotalNonBillableOvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the timesheet total non-billable overtime work.|
|TotalNonBillableWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet total non-billable work.|
|TotalNonBillableWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|TotalNonBillableWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the timesheet total non-billable work.|
|TotalOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet total overtime work.|
|TotalOvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|TotalOvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the timesheet total overtime work.|
|TotalWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet grand total of all work.|
|TotalWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|TotalWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the timesheet grand total of all work.|
|WeekStartsOn|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Byte|Gets or sets the day of the week on which the timesheet starts.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the TimeSheet object.|
|[Recall()](#Recall__)|&#x2713;|&#x2713;|&#x2713;|void|Recalls the timesheet.|
|[Submit(String comment)](#Submit_String_comment_)|&#x2713;|&#x2713;|&#x2713;|void|Submits the timesheet.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void|Saves changes in a new timesheet.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the TimeSheet object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void

### <a id="Recall__"></a>Recall()
 
Recalls the timesheet.

#### Syntax

```
void Recall()
```

#### Parameters

None

#### Return Value

void

### <a id="Submit_String_comment_"></a>Submit(String comment)
 
Submits the timesheet.

#### Syntax

```
void Submit(String comment)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|comment| String | A comment on the timesheet.


#### Return Value

void

### <a id="Update__"></a>Update()
 
Saves changes in a new timesheet.

#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
