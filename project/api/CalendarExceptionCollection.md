[comment]: # (Name:CalendarExceptionCollection)
[comment]: # (Name:Microsoft.ProjectServer.CalendarExceptionCollection)
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

```JavaScript
PS.CalendarExceptionCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.CalendarExceptionCollection
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
[!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[CalendarException](CalendarException.md)|Gets a [CalendarException](CalendarException.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[CalendarException](CalendarException.md)|Gets a [CalendarException](CalendarException.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
[!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add(CalendarExceptionCreationInformation parameters)](#Add_[CalendarExceptionCreationInformation]_CalendarExceptionCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[CalendarException](CalendarException.md)|Adds the [CalendarException](CalendarException.md) that is specified by the [CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md) object to the collection.|
|[GetById(Integer id)](#GetById_Integer_id_)|&#x2713;|&#x2713;|&#x2713;|[CalendarException](CalendarException.md)|Gets a [CalendarException](CalendarException.md) from the collection with the Guid value.|
|[Remove(CalendarException exception)](#Remove_[CalendarException]_CalendarException.md__exception_)|&#x2713;|&#x2713;||Boolean|Removes the specified [CalendarException](CalendarException.md) from the collection.|

<br/>
#### Method Details

#### <a name="Add_[CalendarExceptionCreationInformation]_CalendarExceptionCreationInformation.md__parameters_"></a>Add([CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md) parameters)

Adds the [CalendarException](CalendarException.md) that is specified by the [CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md) object to the collection.

##### Syntax

```
CalendarException Add(CalendarExceptionCreationInformation parameters)
```

##### Parameters
[!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md)|The properties that can be set when creating a calendar exception.|

##### Return Value

[CalendarException](CalendarException.md)

#### <a name="GetById_Integer_id_"></a>GetById(Integer id)

Gets a [CalendarException](CalendarException.md) from the collection with the Guid value.

##### Syntax

```

CalendarException GetById(Integer id)

```

##### Parameters
[!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id|Integer|The id of the [CalendarException](CalendarException.md).|

##### Return Value

[CalendarException](CalendarException.md)

#### <a name="Remove_[CalendarException]_CalendarException.md__exception_"></a>Remove([CalendarException](CalendarException.md) exception)

Removes the specified [CalendarException](CalendarException.md) from the collection.

##### Syntax

```

Boolean Remove(CalendarException exception)

```

##### Parameters
[!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|exception|[CalendarException](CalendarException.md)|The [CalendarException](CalendarException.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[Calendar](Calendar.md)<br/>
[CalendarException](CalendarException.md)<br/>
[CalendarExceptionCreationInformation](CalendarExceptionCreationInformation.md)<br/>
[EnterpriseResource](EnterpriseResource.md)<br/>
