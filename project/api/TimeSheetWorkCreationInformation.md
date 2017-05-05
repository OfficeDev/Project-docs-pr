[comment]: # (Name:TimeSheetWorkCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.TimeSheetWorkCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheetWorkCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [TimeSheetWork](TimeSheetWork.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TimeSheetWorkCreationInformation 
```
### JSOM

```javascript
PS.TimeSheetWorkCreationInformation
```
### REST Interface

Supported.

```
PS.TimeSheetWorkCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines('{lineid}')/Work/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'ActualWork':'value', 
		'Comment':'value', 
		'End':'value', 
		'NonBillableOvertimeWork':'value', 
		'NonBillableWork':'value', 
		'OvertimeWork':'value', 
		'PlannedWork':'value', 
		'Start':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="ActualWork"></a>ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of actual work that is on a timesheet.|
|<a name="Comment"></a>Comment|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the timesheet work comment.|
|<a name="End"></a>End|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the end time of work that is on a timesheet.|
|<a name="NonBillableOvertimeWork"></a>NonBillableOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of non-billable overtime work that is on a timesheet.|
|<a name="NonBillableWork"></a>NonBillableWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of non-billable work that is on a timesheet.|
|<a name="OvertimeWork"></a>OvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of overtime work that is on a timesheet.|
|<a name="PlannedWork"></a>PlannedWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of planned work that is on a timesheet.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the start time of work that is on a timesheet.|

## <a name="seeAlso"></a>See Also

[TimeSheetWork](TimeSheetWork.md)<br/>
[TimeSheetWorkCollection](TimeSheetWorkCollection.md)<br/>
