[comment]: # (Name:TimeSheetLineClass)
[comment]: # (Name:Microsoft.Office.Project.Server.Library.TimeSheetLineClass)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheetLineClass enumeration

<a name="description"></a>Represents classifications that define the different uses of a timesheet line.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum TimeSheetLineClass 
```
### JSOM

```javascript
PS.TimeSheetLineClass
```
### REST Interface

TimeSheetLineClass enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="StandardLine"></a>StandardLine|0|The class of timesheet line that is used to record standard work time; the default class of timesheet line.|
|<a name="SickTimeLine"></a>SickTimeLine|1|The class of timesheet line that is used to record sick time.|
|<a name="VacationLine"></a>VacationLine|2|The class of timesheet line that is used to record vacation time.|
|<a name="AdministrativeLine"></a>AdministrativeLine|3|The class of timesheet line that is used to record administrative time.|

## <a name="seeAlso"></a>See Also

[TimeSheetLine](TimeSheetLine.md)<br/>
[TimeSheetLineCreationInformation](TimeSheetLineCreationInformation.md)<br/>
