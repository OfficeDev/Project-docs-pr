[comment]: # (Name:CalendarCollection)
[comment]: # (Name:Microsoft.ProjectServer.CalendarCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>CalendarCollection class

inherits members from [ClientObjectCollection<Calendar>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of calendars objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class CalendarCollection 
```
### JSOM

```javascript
PS.CalendarCollection
```
### REST Interface

Supported.

```
PS.CalendarCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Calendars
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[Calendar](Calendar.md)|Gets a [Calendar](Calendar.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[Calendar](Calendar.md)|Gets a [Calendar](Calendar.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{CalendarId}&#39;](#&#39;{CalendarId}&#39;)|||&#x2713;|[Calendar](Calendar.md)|Gets a [Calendar](Calendar.md) from the collection with the specified CalendarId.|
|[Add(CalendarCreationInformation parameters)](#Add_[CalendarCreationInformation]_CalendarCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Adds the [Calendar](Calendar.md) that is specified by the [CalendarCreationInformation](CalendarCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets a [Calendar](Calendar.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets a [Calendar](Calendar.md) from the collection with the Guid value.|
|[Remove(Calendar calendar)](#Remove_[Calendar]_Calendar.md__calendar_)|&#x2713;|&#x2713;||Boolean|Removes the specified [Calendar](Calendar.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the calendar collection.|

<br/>
#### Method Details

#### <a name="&#39;{CalendarId}&#39;"></a>&#39;{CalendarId}&#39;
 
Gets a [Calendar](Calendar.md) from the collection with the specified CalendarId.

##### Syntax

```
Calendar http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Calendars('{CalendarId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|CalendarId|String|the id of the Calendar|

##### Return Value

[Calendar](Calendar.md)

#### <a name="Add_[CalendarCreationInformation]_CalendarCreationInformation.md__parameters_"></a>Add([CalendarCreationInformation](CalendarCreationInformation.md) parameters)
 
Adds the [Calendar](Calendar.md) that is specified by the [CalendarCreationInformation](CalendarCreationInformation.md) object to the collection.

##### Syntax

```
Calendar Add(CalendarCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[CalendarCreationInformation](CalendarCreationInformation.md)|The properties that can be set when creating a calendar.|

##### Return Value

[Calendar](Calendar.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [Calendar](Calendar.md) from the collection with the Id value.

##### Syntax

```
Calendar GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [Calendar](Calendar.md)|

##### Return Value

[Calendar](Calendar.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [Calendar](Calendar.md) from the collection with the Guid value.

##### Syntax

```
Calendar GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [Calendar](Calendar.md).|

##### Return Value

[Calendar](Calendar.md)

#### <a name="Remove_[Calendar]_Calendar.md__calendar_"></a>Remove([Calendar](Calendar.md) calendar)
 
Removes the specified [Calendar](Calendar.md) from the collection.

##### Syntax

```
Boolean Remove(Calendar calendar)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|calendar|[Calendar](Calendar.md)|The [Calendar](Calendar.md) to remove.|

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
