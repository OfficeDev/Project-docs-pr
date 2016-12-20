[comment]: # (Name:CalendarCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# CalendarCollection

Represents a collection of calendars objects.



## Syntax

### CSOM

```C#
Class CalendarCollection 
```
### JSOM

```
PS.CalendarCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Calendars
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([CalendarCreationInformation](CalendarCreationInformation.md) parameters)](#Add_[CalendarCreationInformation]_CalendarCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Adds a new calendar to the collection of calendars.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets a calendar from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets a calendar from the collection with the [Id](d4353526-bcf6-628f-9cd0-97be882522ad.md) value.|
|[Remove([Calendar](Calendar.md) calendar)](#Remove_[Calendar]_Calendar.md__calendar_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified calendar from the collection of calendars.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void|Updates the calendar collection.|



## Method Details


### <a name="Add_[CalendarCreationInformation]_CalendarCreationInformation.md__parameters_"></a>Add([CalendarCreationInformation](CalendarCreationInformation.md) parameters)
 
Adds a new calendar to the collection of calendars.

#### Syntax

```
Calendar Add(CalendarCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [CalendarCreationInformation](CalendarCreationInformation.md) | An object that contains information, for example name and GUID, about a new calendar.


#### Return Value

[Calendar](Calendar.md)

### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a calendar from the collection with the specified GUID.

#### Syntax

```
Calendar GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A Guid value.


#### Return Value

[Calendar](Calendar.md)

### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a calendar from the collection with the [Id](d4353526-bcf6-628f-9cd0-97be882522ad.md) value.

#### Syntax

```
Calendar GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | A string value that represents a calendar identifier.


#### Return Value

[Calendar](Calendar.md)

### <a name="Remove_[Calendar]_Calendar.md__calendar_"></a>Remove([Calendar](Calendar.md) calendar)
 
Removes the specified calendar from the collection of calendars.

#### Syntax

```
Boolean Remove(Calendar calendar)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|calendar| [Calendar](Calendar.md) | The Calendar object to be removed.


#### Return Value

Boolean

### <a name="Update__"></a>Update()
 
Updates the calendar collection.

#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
