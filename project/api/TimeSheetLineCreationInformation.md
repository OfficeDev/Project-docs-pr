[comment]: # (Name:TimeSheetLineCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.TimeSheetLineCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheetLineCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [TimeSheetLine](TimeSheetLine.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TimeSheetLineCreationInformation 
```
### JSOM

```javascript
PS.TimeSheetLineCreationInformation
```
### REST Interface

Supported.

```
PS.TimeSheetLineCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'AssignmentId':'value', 
		'Comment':'value', 
		'Id':'value', 
		'LineClass':'value', 
		'ProjectId':'value', 
		'TaskName':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="AssignmentId"></a>AssignmentId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the assignment that is associated with the timesheet line.|
|<a name="Comment"></a>Comment|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the comment for the timesheet line.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the timesheet line.|
|<a name="LineClass"></a>LineClass|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TimeSheetLineClass](TimeSheetLineClass.md)|Gets or sets the line class type of the timesheet line.|
|<a name="ProjectId"></a>ProjectId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project that is associated with the timesheet line.|
|<a name="TaskName"></a>TaskName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the time sheet line task name.|

## <a name="seeAlso"></a>See Also

[TimeSheetLine](TimeSheetLine.md)<br/>
[TimeSheetLineCollection](TimeSheetLineCollection.md)<br/>
