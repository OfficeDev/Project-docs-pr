[comment]: # (Name:CalendarExceptionCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>CalendarExceptionCollection class

inherits members from [ClientObjectCollection<CalendarException>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of calendar exceptions.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class CalendarExceptionCollection 
```
### JSOM

```
PS.CalendarExceptionCollection
```
### REST Interface

This resource supports GET and POST HTTP commands.

Supported.  See [BaseCalendarException](BaseCalendarException.md) or [ResourceCalendarException](ResourceCalendarException.md) for more REST details.


## <a name="members"></a>Members

### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add(CalendarExceptionCreationInformation parameters)](#Add_[CalendarExceptionCreationInformation]_CalendarExceptionCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[CalendarException](CalendarException.md)|Adds a calendar exception to the collection of calendar exceptions.|
|[GetById(Int32 id)](#GetById_Integer_id_)|&#x2713;|&#x2713;|&#x2713;|[CalendarException](CalendarException.md)|Gets a calendar exception from the collection of exceptions with the specified object identifier.|
|[Remove(CalendarException exception)](#Remove_[CalendarException]_CalendarException.md__exception_)|&#x2713;|&#x2713;||Boolean|Removes the specified CalendarException object from the collection of calendar exceptions.|

#### Method Details

#### <a name="Add_[CalendarExceptionCreationInformation]_CalendarExceptionCreationInformation.md__parameters_"></a>Add([CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md) parameters)



Adds a calendar exception to the collection of calendar exceptions.

##### Syntax

```
CalendarException Add(CalendarExceptionCreationInformation parameters)
```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md) | An object that contains information, for example start and finish times and dates, about a new calendar exception.

##### Return Value

[CalendarException](CalendarException.md)

#### <a name="GetById_Integer_id_"></a>GetById(Integer id)


 
Gets a calendar exception from the collection of exceptions with the specified object identifier.

##### Syntax

```
CalendarException GetById(Int32 id)
```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| Integer | A calendar exception integer identifier.

##### Return Value

[CalendarException](CalendarException.md)

#### <a name="Remove_[CalendarException]_CalendarException.md__exception_"></a>Remove([CalendarException](CalendarException.md) exception)


 
Removes the specified CalendarException object from the collection of calendar exceptions.

##### Syntax

```
Boolean Remove(CalendarException exception)
```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|exception| [CalendarException](CalendarException.md) | The CalendarException object to be removed.

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[Calendar](Calendar.md)<br/>
[CalendarException](CalendarException.md)<br/>
[CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md)<br/>
[EnterpriseResource](EnterpriseResource.md)<br/>
