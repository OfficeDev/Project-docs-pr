[comment]: # (Name:TimeSheetLine)
[comment]: # (Name:Microsoft.ProjectServer.TimeSheetLine)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheetLine class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a line in a timesheet.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class TimeSheetLine 
```
### JSOM

```JavaScript
PS.TimeSheetLine
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.TimeSheetLine

http://<sitecollection>/<site>/api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines('{lineid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Assignment"></a>Assignment|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignment](PublishedAssignment.md)|Gets the assignment that is associated with the timesheet line.|
|<a name="Comment"></a>Comment|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet line comment.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the timesheet line.|
|<a name="LineClass"></a>LineClass|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TimeSheetLineClass](TimeSheetLineClass.md)|Gets or sets the class of the timesheet line.|
|<a name="ProjectName"></a>ProjectName|&#x2713;|&#x2713;|&#x2713;|String|Gets the timesheet line project name.|
|<a name="Status"></a>Status|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TimeSheetLineStatus](TimeSheetLineStatus.md)|Gets or sets the timesheet line status.|
|<a name="TaskName"></a>TaskName|&#x2713;|&#x2713;|&#x2713;|String|Gets the timesheet line task name.|
|<a name="TimeSheet"></a>TimeSheet|&#x2713;|&#x2713;|&#x2713;|[TimeSheet](TimeSheet.md)|Gets the timesheet that is associated with the timesheet line.|
|<a name="TotalWork"></a>TotalWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total amount of work in a timesheet line.|
|<a name="TotalWorkMilliseconds"></a>TotalWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets or sets the time interval, expressed in milliseconds, for the total amount of work in a timesheet line.|
|<a name="TotalWorkTimeSpan"></a>TotalWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total amount of work in a timesheet line.|
|<a name="ValidationType"></a>ValidationType|&#x2713;|&#x2713;|&#x2713;|[TimeSheetValidationType](TimeSheetValidationType.md)|Gets the timesheet validation type.|
|<a name="Work"></a>Work|&#x2713;|&#x2713;|&#x2713;|[TimeSheetWorkCollection](TimeSheetWorkCollection.md)|Gets the actual work on the timesheet.|

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the time sheet line object.|
|[Submit(String comment)](#Submit_String_comment_)|&#x2713;|&#x2713;|&#x2713;|void|Submits the time sheet line.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the time sheet line object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

#### <a name="Submit_String_comment_"></a>Submit(String comment)
 
Submits the time sheet line.

##### Syntax

```
void Submit(String comment)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|comment|String|A comment about the timesheet line.|

##### Return Value

void

## <a name="seeAlso"></a>See Also

[TimeSheetLineCollection](TimeSheetLineCollection.md)<br/>
[TimeSheetLineCreationInformation](TimeSheetLineCreationInformation.md)<br/>
