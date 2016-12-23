[comment]: # (Name:CalendarCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>CalendarCollection class

inherits members from [ClientObjectCollection<Calendar>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of calendars objects.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class CalendarCollection 
```
### JSOM

```JavaScript
PS.CalendarCollection
```
### REST Interface

This resource supports GET and POST HTTP commands.

```
PS.CalendarCollection

http://<sitecollection>/<site>/api/ProjectServer/Calendars
```

## <a name="members"></a>Members

### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{CalendarId}&#39;](#&#39;{CalendarId}&#39;)|||&#x2713;|[Calendar](Calendar.md)|Gets a [Calendar](Calendar.md) from the collection with the specified CalendarId.|
|[Add(CalendarCreationInformation parameters)](#Add_[CalendarCreationInformation]_CalendarCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Adds a new calendar to the collection of calendars.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets a calendar from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets a calendar from the collection with the Id value.|
|[Remove(Calendar calendar)](#Remove_[Calendar]_Calendar.md__calendar_)|&#x2713;|&#x2713;||Boolean|Removes the specified calendar from the collection of calendars.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the calendar collection.|

<br/>
#### Method Details

#### <a name="&#39;{CalendarId}&#39;"></a>&#39;{CalendarId}&#39;

 

Gets a [Calendar](Calendar.md) from the collection with the specified CalendarId.

##### Syntax

```

Calendar http://<sitecollection>/<site>/api/ProjectServer/Calendars('{CalendarId}')

```

##### Parameters

None

##### Return Value

[Calendar](Calendar.md)

#### <a name="Add_[CalendarCreationInformation]_CalendarCreationInformation.md__parameters_"></a>Add([CalendarCreationInformation](CalendarCreationInformation.md) parameters)



Adds a new calendar to the collection of calendars.

##### Syntax

```
Calendar Add(CalendarCreationInformation parameters)
```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [CalendarCreationInformation](CalendarCreationInformation.md) | An object that contains information, for example name and GUID, about a new calendar.

##### Return Value

[Calendar](Calendar.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)


 
Gets a calendar from the collection with the specified GUID.

##### Syntax

```
Calendar GetByGuid(Guid uid)
```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |

|uid| Guid | The calendar Guid to return.

##### Return Value

[Calendar](Calendar.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)


 
Gets a calendar from the collection with the Id value.

##### Syntax

```
Calendar GetById(String objectId)
```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | A string value that represents a calendar identifier.

##### Return Value

[Calendar](Calendar.md)

#### <a name="Remove_[Calendar]_Calendar.md__calendar_"></a>Remove([Calendar](Calendar.md) calendar)


 
Removes the specified calendar from the collection of calendars.

##### Syntax

```
Boolean Remove(Calendar calendar)
```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|calendar| [Calendar](Calendar.md) | The Calendar object to be removed.

##### Return Value

Boolean

#### <a name="Update__"></a>Update()


 
Updates the calendar collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[Calendar](Calendar.md)<br/>
[CalendarCreationInformation](CalendarCreationInformation.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
