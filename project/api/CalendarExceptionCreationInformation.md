[comment]: # (Name:CalendarExceptionCreationInformation)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# CalendarExceptionCreationInformation

Provides information for the creation of a calendar exception.



## Syntax

### CSOM

```C#
Class CalendarExceptionCreationInformation 
```
### JSOM

```
PS.CalendarExceptionCreationInformation
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/?????
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time that the calendar exception ends.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name given for the calendar exception, such as Vacation.|
|RecurrenceDays|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CalendarRecurrenceDays](CalendarRecurrenceDays.md)|Gets or sets a mask that represents the days of the week on which the calendar exception is effective.|
|RecurrenceFrequency|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the interval at which the calendar exception occurs.|
|RecurrenceMonth|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the month when setting a yearly recurrence.|
|RecurrenceMonthDay|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the day of the month when setting a yearly recurrence.|
|RecurrenceType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CalendarRecurrenceType](CalendarRecurrenceType.md)|Gets or sets the recurrence type for the calendar exception.|
|RecurrenceWeek|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CalendarRecurrenceWeek](CalendarRecurrenceWeek.md)|Gets or sets the week number of a monthly occurrence.|
|Shift1Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the first shift ends.|
|Shift1Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the first shift starts.|
|Shift2Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the second shift ends.|
|Shift2Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the second shift starts.|
|Shift3Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the third shift ends.|
|Shift3Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the third shift starts.|
|Shift4Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the fourth shift ends.|
|Shift4Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the fourth shift starts.|
|Shift5Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the fifth shift ends.|
|Shift5Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the minute of the day that the fifth shift starts.|
|Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time that the calendar exception starts.|






## See Also
