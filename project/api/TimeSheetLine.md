[comment]: # (Name:TimeSheetLine)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# TimeSheetLine

Represents a line in a timesheet.



## Syntax

### CSOM

```C#
Class TimeSheetLine 
```
### JSOM

```
PS.TimeSheetLine
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines('{lineid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Assignment|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignment](PublishedAssignment.md)|Gets the assignment that is associated with the timesheet line.|
|Comment|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet line comment.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the timesheet line.|
|LineClass|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TimeSheetLineClass](TimeSheetLineClass.md)|Gets or sets the class of the timesheet line.|
|ProjectName|&#x2713;|&#x2713;|&#x2713;|String|Gets the timesheet line project name.|
|Status|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TimeSheetLineStatus](TimeSheetLineStatus.md)|Gets or sets the timesheet line status.|
|TaskName|&#x2713;|&#x2713;|&#x2713;|String|Gets the timesheet line task name.|
|TimeSheet|&#x2713;|&#x2713;|&#x2713;|[TimeSheet](TimeSheet.md)|Gets the timesheet that is associated with the timesheet line.|
|TotalWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total amount of work in a timesheet line.|
|TotalWorkMilliseconds||&#x2713;|&#x2713;|Integer||
|TotalWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total amount of work in a timesheet line.|
|ValidationType|&#x2713;|&#x2713;|&#x2713;|[ValidationType](ValidationType.md)|Gets the timesheet validation type.|
|Work|&#x2713;|&#x2713;|&#x2713;|[TimeSheetWorkCollection](TimeSheetWorkCollection.md)|Gets the actual work on the timesheet.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the TimeSheetLine object.|
|[Submit(String comment)](#Submit_String_comment_)|&#x2713;|&#x2713;|&#x2713;|void|Submits the time sheet line.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the TimeSheetLine object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void

### <a id="Submit_String_comment_"></a>Submit(String comment)
 
Submits the time sheet line.

#### Syntax

```
void Submit(String comment)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|comment| String | A comment about the timesheet line.


#### Return Value

void


## See Also
