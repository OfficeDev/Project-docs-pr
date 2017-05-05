[comment]: # (Name:TimeSheetWork)
[comment]: # (Name:Microsoft.ProjectServer.TimeSheetWork)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheetWork class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents the different types of work on a timesheet.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TimeSheetWork 
```
### JSOM

```javascript
PS.TimeSheetWork
```
### REST Interface

Supported.

```
PS.TimeSheetWork

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines('{lineid}')/Work('{yyyy-MM-dd}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="ActualWork"></a>ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of actual work that is on a timesheet.|
|<a name="ActualWorkMilliseconds"></a>ActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of actual work that is on a timesheet.|
|<a name="ActualWorkTimeSpan"></a>ActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of actual work that is on a timesheet.|
|<a name="Comment"></a>Comment|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet work comment.|
|<a name="End"></a>End|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the end time of the actual work that is on a timesheet.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the timesheet line that is associated with the work.|
|<a name="NonBillableOvertimeWork"></a>NonBillableOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of nonbillable overtime work that is on a timesheet.|
|<a name="NonBillableOvertimeWorkMilliseconds"></a>NonBillableOvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of nonbillable overtime work that is on a timesheet.|
|<a name="NonBillableOvertimeWorkTimeSpan"></a>NonBillableOvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of nonbillable overtime work that is on a timesheet.|
|<a name="NonBillableWork"></a>NonBillableWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of nonbillable work that is on a timesheet.|
|<a name="NonBillableWorkMilliseconds"></a>NonBillableWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of nonbillable work that is on a timesheet.|
|<a name="NonBillableWorkTimeSpan"></a>NonBillableWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of nonbillable work that is on a timesheet.|
|<a name="OvertimeWork"></a>OvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of overtime work that is on a timesheet.|
|<a name="OvertimeWorkMilliseconds"></a>OvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of overtime work that is on a timesheet.|
|<a name="OvertimeWorkTimeSpan"></a>OvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of overtime work that is on a timesheet.|
|<a name="PlannedWork"></a>PlannedWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of planned work that is on a timesheet.|
|<a name="PlannedWorkMilliseconds"></a>PlannedWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the time interval, expressed in milliseconds, for the amount of overtime work that is on a timesheet.|
|<a name="PlannedWorkTimeSpan"></a>PlannedWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of planned work that is on a timesheet.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the start time of the actual work that is on a timesheet.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the time sheet work object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the time sheet work object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[TimeSheetWorkCollection](TimeSheetWorkCollection.md)<br/>
[TimeSheetWorkCreationInformation](TimeSheetWorkCreationInformation.md)<br/>
