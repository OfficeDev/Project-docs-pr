[comment]: # (Name:CalendarRecurrenceType)
[comment]: # (Name:Microsoft.Office.Project.Server.Library.CalendarConstants+CalendarRecurrenceType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>CalendarRecurrenceType enumeration

<a name="description"></a>Specifies the recurrence types for a calendar exception.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum CalendarRecurrenceType 
```
### JSOM

```javascript
PS.CalendarRecurrenceType
```
### REST Interface

CalendarRecurrenceType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="Daily"></a>Daily|0|Daily recurrence.|
|<a name="DailySkip"></a>DailySkip|1|Daily, with recurrence defined by skipping a set number of days.|
|<a name="Weekly"></a>Weekly|2|Weekly recurrence.|
|<a name="Monthly"></a>Monthly|3|Monthly recurrence.|
|<a name="Yearly"></a>Yearly|4|Yearly recurrence.|

## <a name="seeAlso"></a>See Also

[CalendarException](CalendarException.md)<br/>
[CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md)<br/>
