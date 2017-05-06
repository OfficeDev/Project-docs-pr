[comment]: # (Name:TimeSheetStatus)
[comment]: # (Name:Microsoft.ProjectServer.TimeSheetStatus)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheetStatus enumeration

<a name="description"></a>Represents status settings that can be applied to a timesheet.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum TimeSheetStatus 
```
### JSOM

```javascript
PS.TimeSheetStatus
```
### REST Interface

TimeSheetStatus enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NotSpecified"></a>NotSpecified|0|Not specified.|
|<a name="InProgress"></a>InProgress|1|In progress.|
|<a name="Submitted"></a>Submitted|2|Submitted.|
|<a name="Acceptable"></a>Acceptable|3|Acceptable.|
|<a name="Approved"></a>Approved|4|Approved.|
|<a name="Rejected"></a>Rejected|5|Rejected.|
|<a name="PendingSubmit"></a>PendingSubmit|6|Pending submission; used when one or more timesheet lines are pending approval after a timesheet is submitted and project manager coordination is required.|

## <a name="seeAlso"></a>See Also

[TimeSheet](TimeSheet.md)<br/>
