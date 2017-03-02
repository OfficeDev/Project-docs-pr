[comment]: # (Name:TimeSheet)
[comment]: # (Name:Microsoft.ProjectServer.TimeSheet)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheet class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Contains the methods and properties for managing a timesheet.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TimeSheet 
```
### JSOM

```javascript
PS.TimeSheet
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.TimeSheet

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Comments"></a>Comments|&#x2713;|&#x2713;|&#x2713;|String|Gets the timesheet comments.|
|<a name="Creator"></a>Creator|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the timesheet creator.|
|<a name="EntryMode"></a>EntryMode|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TimeSheetEntryMode](TimeSheetEntryMode.md)|Gets or sets the timesheet entry mode.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the time sheet.|
|<a name="IsControlledByOwner"></a>IsControlledByOwner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the timesheet is controlled by the owner.|
|<a name="IsProcessed"></a>IsProcessed|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the timesheet is finalized and should not be changed.|
|<a name="Lines"></a>Lines|&#x2713;|&#x2713;|&#x2713;|[TimeSheetLineCollection](TimeSheetLineCollection.md)|Gets the collection of lines in the timesheet.|
|<a name="Manager"></a>Manager|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the timesheet manager.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet name.|
|<a name="Period"></a>Period|&#x2713;|&#x2713;|&#x2713;|[TimeSheetPeriod](TimeSheetPeriod.md)|Gets the timesheet period.|
|<a name="Status"></a>Status|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TimeSheetStatus](TimeSheetStatus.md)|Gets or sets the timesheet line status.|
|<a name="TotalActualWork"></a>TotalActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet total actual work.|
|<a name="TotalActualWorkMilliseconds"></a>TotalActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the timesheet total actual work.|
|<a name="TotalActualWorkTimeSpan"></a>TotalActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the timesheet total actual work.|
|<a name="TotalNonBillableOvertimeWork"></a>TotalNonBillableOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet total non-billable overtime work.|
|<a name="TotalNonBillableOvertimeWorkMilliseconds"></a>TotalNonBillableOvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the timesheet total non-billable overtime work.|
|<a name="TotalNonBillableOvertimeWorkTimeSpan"></a>TotalNonBillableOvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the timesheet total non-billable overtime work.|
|<a name="TotalNonBillableWork"></a>TotalNonBillableWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet total non-billable work.|
|<a name="TotalNonBillableWorkMilliseconds"></a>TotalNonBillableWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the timesheet total non-billable work.|
|<a name="TotalNonBillableWorkTimeSpan"></a>TotalNonBillableWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the timesheet total non-billable work.|
|<a name="TotalOvertimeWork"></a>TotalOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet total overtime work.|
|<a name="TotalOvertimeWorkMilliseconds"></a>TotalOvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the timesheet total overtime work.|
|<a name="TotalOvertimeWorkTimeSpan"></a>TotalOvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the timesheet total overtime work.|
|<a name="TotalWork"></a>TotalWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet grand total of all work.|
|<a name="TotalWorkMilliseconds"></a>TotalWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the timesheet grand total of all work.|
|<a name="TotalWorkTimeSpan"></a>TotalWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the timesheet grand total of all work.|
|<a name="WeekStartsOn"></a>WeekStartsOn|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Byte|Gets or sets the day of the week on which the timesheet starts.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the time sheet object.|
|[Recall()](#Recall__)|&#x2713;|&#x2713;|&#x2713;|void|Recalls the timesheet.|
|[Submit(String comment)](#Submit_String_comment_)|&#x2713;|&#x2713;|&#x2713;|void|Submits the timesheet.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void|Saves changes in a new timesheet.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the time sheet object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

#### <a name="Recall__"></a>Recall()
 
Recalls the timesheet.

##### Syntax

```
void Recall()
```

##### Parameters

None

##### Return Value

void

#### <a name="Submit_String_comment_"></a>Submit(String comment)
 
Submits the timesheet.

##### Syntax

```
void Submit(String comment)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|comment|String|A comment on the timesheet.|

##### Return Value

void

#### <a name="Update__"></a>Update()
 
Saves changes in a new timesheet.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
[TimeSheetLine](TimeSheetLine.md)<br/>
[TimeSheetPeriod](TimeSheetPeriod.md)<br/>
