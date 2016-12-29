[comment]: # (Name:CalendarException)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>CalendarException class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a difference (an exception) from the base calendar.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class CalendarException 
```
### JSOM

```JavaScript
PS.CalendarException
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.CalendarException
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Calendar"></a>Calendar|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets the name of the calendar that is associated with the exception.|
|<a name="Finish"></a>Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time that the calendar exception ends.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the object identifier as an index into the collection of calendar exceptions.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the exception, such as Vacation.|
|<a name="RecurrenceDays"></a>RecurrenceDays|&#x2713;|&#x2713;|&#x2713;|[CalendarRecurrenceDays](CalendarRecurrenceDays.md)|Gets a mask that represents the days of the week on which the calendar exception is effective.|
|<a name="RecurrenceFrequency"></a>RecurrenceFrequency|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the interval at which the calendar exception occurs.|
|<a name="RecurrenceMonth"></a>RecurrenceMonth|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the month value when setting a yearly recurrence.|
|<a name="RecurrenceMonthDay"></a>RecurrenceMonthDay|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the day of the month when setting a yearly recurrence.|
|<a name="RecurrenceType"></a>RecurrenceType|&#x2713;|&#x2713;|&#x2713;|[CalendarRecurrenceType](CalendarRecurrenceType.md)|Gets the recurrence type for the calendar exception.|
|<a name="RecurrenceWeek"></a>RecurrenceWeek|&#x2713;|&#x2713;|&#x2713;|[CalendarRecurrenceWeek](CalendarRecurrenceWeek.md)|Gets the week number of a monthly occurrence.|
|<a name="Shift1Finish"></a>Shift1Finish|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the first shift ends.|
|<a name="Shift1Start"></a>Shift1Start|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the first shift starts.|
|<a name="Shift2Finish"></a>Shift2Finish|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the second shift ends.|
|<a name="Shift2Start"></a>Shift2Start|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the second shift starts.|
|<a name="Shift3Finish"></a>Shift3Finish|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the third shift ends.|
|<a name="Shift3Start"></a>Shift3Start|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the third shift starts.|
|<a name="Shift4Finish"></a>Shift4Finish|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the fourth shift ends.|
|<a name="Shift4Start"></a>Shift4Start|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the fourth shift starts.|
|<a name="Shift5Finish"></a>Shift5Finish|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the fifth shift ends.|
|<a name="Shift5Start"></a>Shift5Start|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the fifth shift starts.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the time and date of the start of the calendar exception.|

### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the calendar exception object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()

Deletes the calendar exception object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[BaseCalendarException](BaseCalendarException.md)<br/>
[CalendarExceptionCollection](CalendarExceptionCollection.md)<br/>
[CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md)<br/>
[ResourceCalendarException](ResourceCalendarException.md)<br/>
