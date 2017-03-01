[comment]: # (Name:CalendarExceptionCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.CalendarExceptionCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>CalendarExceptionCreationInformation class

<a name="description"></a>Provides information for the creation of a calendar exception.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class CalendarExceptionCreationInformation 
```
### JSOM

```JavaScript
PS.CalendarExceptionCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.CalendarExceptionCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Calendars('{calendarid}')/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Finish':'value', 
		'Name':'value', 
		'RecurrenceDays':'value', 
		'RecurrenceFrequency':'value', 
		'RecurrenceMonth':'value', 
		'RecurrenceMonthDay':'value', 
		'RecurrenceType':'value', 
		'RecurrenceWeek':'value', 
		'Shift1Finish':'value', 
		'Shift1Start':'value', 
		'Shift2Finish':'value', 
		'Shift2Start':'value', 
		'Shift3Finish':'value', 
		'Shift3Start':'value', 
		'Shift4Finish':'value', 
		'Shift4Start':'value', 
		'Shift5Finish':'value', 
		'Shift5Start':'value', 
		'Start':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
[!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Finish"></a>Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time that the calendar exception ends.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name given for the calendar exception, such as Vacation.|
|<a name="RecurrenceDays"></a>RecurrenceDays|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CalendarRecurrenceDays](CalendarRecurrenceDays.md)|Gets or sets a mask that represents the days of the week on which the calendar exception is effective.|
|<a name="RecurrenceFrequency"></a>RecurrenceFrequency|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the interval at which the calendar exception occurs.|
|<a name="RecurrenceMonth"></a>RecurrenceMonth|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the month when setting a yearly recurrence.|
|<a name="RecurrenceMonthDay"></a>RecurrenceMonthDay|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the day of the month when setting a yearly recurrence.|
|<a name="RecurrenceType"></a>RecurrenceType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CalendarRecurrenceType](CalendarRecurrenceType.md)|Gets or sets the recurrence type for the calendar exception.|
|<a name="RecurrenceWeek"></a>RecurrenceWeek|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CalendarRecurrenceWeek](CalendarRecurrenceWeek.md)|Gets or sets the week number of a monthly occurrence.|
|<a name="Shift1Finish"></a>Shift1Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the first shift ends.|
|<a name="Shift1Start"></a>Shift1Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the first shift starts.|
|<a name="Shift2Finish"></a>Shift2Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the second shift ends.|
|<a name="Shift2Start"></a>Shift2Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the second shift starts.|
|<a name="Shift3Finish"></a>Shift3Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the third shift ends.|
|<a name="Shift3Start"></a>Shift3Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the third shift starts.|
|<a name="Shift4Finish"></a>Shift4Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the fourth shift ends.|
|<a name="Shift4Start"></a>Shift4Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the fourth shift starts.|
|<a name="Shift5Finish"></a>Shift5Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the fifth shift ends.|
|<a name="Shift5Start"></a>Shift5Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the fifth shift starts.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time that the calendar exception starts.|

## <a name="seeAlso"></a>See Also

[CalendarException](CalendarException.md)<br/>
[CalendarExceptionCollection](CalendarExceptionCollection.md)<br/>
