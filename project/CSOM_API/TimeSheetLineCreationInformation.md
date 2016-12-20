[comment]: # (Name:TimeSheetLineCreationInformation)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:23Z)

# TimeSheetLineCreationInformation

Provides property settings and methods that are used to create a timesheet line.



## Syntax

### CSOM

```C#
Class TimeSheetLineCreationInformation 
```
### JSOM

```
PS.TimeSheetLineCreationInformation
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/?????
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|AssignmentId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the assignment that is associated with the timesheet line.|
|Comment|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the comment for the timesheet line.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the timesheet line.|
|LineClass|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TimeSheetLineClass](TimeSheetLineClass.md)|Gets or sets the line class type of the timesheet line.|
|ProjectId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project that is associated with the timesheet line.|
|TaskName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the time sheet line task name.|






## See Also
