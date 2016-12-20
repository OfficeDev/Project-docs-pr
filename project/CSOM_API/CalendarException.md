[comment]: # (Name:CalendarException)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# CalendarException

Represents a difference (an exception) from the base calendar.



## Syntax

### CSOM

```C#
Class CalendarException 
```
### JSOM

```
PS.CalendarException
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
|Calendar|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets the name of the calendar that is associated with the exception.|
|Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time that the calendar exception ends.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the object identifier as an index into the collection of calendar exceptions.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the exception, such as Vacation.|
|RecurrenceDays|&#x2713;|&#x2713;|&#x2713;|[CalendarRecurrenceDays](CalendarRecurrenceDays.md)|Gets a mask that represents the days of the week on which the calendar exception is effective.|
|RecurrenceFrequency|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the interval at which the calendar exception occurs.|
|RecurrenceMonth|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the month value when setting a yearly recurrence.|
|RecurrenceMonthDay|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the day of the month when setting a yearly recurrence.|
|RecurrenceType|&#x2713;|&#x2713;|&#x2713;|[CalendarRecurrenceType](CalendarRecurrenceType.md)|Gets the recurrence type for the calendar exception.|
|RecurrenceWeek|&#x2713;|&#x2713;|&#x2713;|[CalendarRecurrenceWeek](CalendarRecurrenceWeek.md)|Gets the week number of a monthly occurrence.|
|Shift1Finish|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the first shift ends.|
|Shift1Start|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the first shift starts.|
|Shift2Finish|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the second shift ends.|
|Shift2Start|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the second shift starts.|
|Shift3Finish|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the third shift ends.|
|Shift3Start|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the third shift starts.|
|Shift4Finish|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the fourth shift ends.|
|Shift4Start|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the fourth shift starts.|
|Shift5Finish|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the fifth shift ends.|
|Shift5Start|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the minute of the day that the fifth shift starts.|
|Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the time and date of the start of the calendar exception.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the CalendarException object.|



## Method Details


### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the CalendarException object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
