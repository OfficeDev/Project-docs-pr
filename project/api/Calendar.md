[comment]: # (Name:Calendar)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# Calendar

Represents a Project Server calendar.



## Syntax

### CSOM

```C#
Class Calendar 
```
### JSOM

```
PS.Calendar
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Calendars('{calendarid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|BaseCalendarExceptions|&#x2713;|&#x2713;|&#x2713;|[CalendarExceptionCollection](CalendarExceptionCollection.md)|Gets the collection of exceptions to base calendars.|
|Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date that the calendar was created.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the calendar.|
|IsStandardCalendar|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the calendar is Gregorian.|
|Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date that the calendar was modified.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the calendar.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[CopyTo(String name)](#CopyTo_String_name_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Makes a copy of the calendar and gives the copy a new name.|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the Calendar object.|



## Method Details


### <a name="CopyTo_String_name_"></a>CopyTo(String name)
 
Makes a copy of the calendar and gives the copy a new name.

#### Syntax

```
Calendar CopyTo(String name)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|name| String | The name of the new calendar.


#### Return Value

[Calendar](Calendar.md)

### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the Calendar object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
