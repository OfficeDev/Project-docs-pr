[comment]: # (Name:CalendarExceptionCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# CalendarExceptionCollection

Represents a collection of calendar exceptions.



## Syntax

### CSOM

```C#
Class CalendarExceptionCollection 
```
### JSOM

```
PS.CalendarExceptionCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/?????
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md) parameters)](#Add_[CalendarExceptionCreationInformation]_CalendarExceptionCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[CalendarException](CalendarException.md)|Adds a calendar exception to the collection of calendar exceptions.|
|[GetById(Integer id)](#GetById_Integer_id_)|&#x2713;|&#x2713;|&#x2713;|[CalendarException](CalendarException.md)|Gets a calendar exception from the collection of exceptions with the specified object identifier.|
|[Remove([CalendarException](CalendarException.md) exception)](#Remove_[CalendarException]_CalendarException.md__exception_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified CalendarException object from the collection of calendar exceptions.|



## Method Details


### <a name="Add_[CalendarExceptionCreationInformation]_CalendarExceptionCreationInformation.md__parameters_"></a>Add([CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md) parameters)
 
Adds a calendar exception to the collection of calendar exceptions.

#### Syntax

```
CalendarException Add(CalendarExceptionCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md) | An object that contains information, for example start and finish times and dates, about a new calendar exception.


#### Return Value

[CalendarException](CalendarException.md)

### <a name="GetById_Integer_id_"></a>GetById(Integer id)
 
Gets a calendar exception from the collection of exceptions with the specified object identifier.

#### Syntax

```
CalendarException GetById(Int32 id)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| Integer | A calendar exception integer identifier.


#### Return Value

[CalendarException](CalendarException.md)

### <a name="Remove_[CalendarException]_CalendarException.md__exception_"></a>Remove([CalendarException](CalendarException.md) exception)
 
Removes the specified CalendarException object from the collection of calendar exceptions.

#### Syntax

```
Boolean Remove(CalendarException exception)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|exception| [CalendarException](CalendarException.md) | The CalendarException object to be removed.


#### Return Value

Boolean


## See Also
