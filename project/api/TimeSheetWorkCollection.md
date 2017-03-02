[comment]: # (Name:TimeSheetWorkCollection)
[comment]: # (Name:Microsoft.ProjectServer.TimeSheetWorkCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheetWorkCollection class

inherits members from [ClientObjectCollection<TimeSheetWork>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Provides a collection of actual work entries for a timesheet.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TimeSheetWorkCollection 
```
### JSOM

```javascript
PS.TimeSheetWorkCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.TimeSheetWorkCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines('{lineid}')/Work
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[TimeSheetWork](TimeSheetWork.md)|Gets a [TimeSheetWork](TimeSheetWork.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[TimeSheetWork](TimeSheetWork.md)|Gets a [TimeSheetWork](TimeSheetWork.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add(TimeSheetWorkCreationInformation parameters)](#Add_[TimeSheetWorkCreationInformation]_TimeSheetWorkCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetWork](TimeSheetWork.md)|Adds the [TimeSheetWork](TimeSheetWork.md) that is specified by the [TimeSheetWorkCreationInformation](TimeSheetWorkCreationInformation.md) object to the collection.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetWork](TimeSheetWork.md)|Gets a [TimeSheetWork](TimeSheetWork.md) from the collection with the Guid value.|
|[GetByStartDate(DateTime start)](#GetByStartDate_DateTime_start_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetWork](TimeSheetWork.md)|Gets a timesheet actual work object from the collection with a specified start date.|
|[Remove(TimeSheetWork work)](#Remove_[TimeSheetWork]_TimeSheetWork.md__work_)|&#x2713;|&#x2713;||Boolean|Removes the specified [TimeSheetWork](TimeSheetWork.md) from the collection.|

<br/>
#### Method Details

#### <a name="Add_[TimeSheetWorkCreationInformation]_TimeSheetWorkCreationInformation.md__parameters_"></a>Add([TimeSheetWorkCreationInformation](TimeSheetWorkCreationInformation.md) parameters)
 
Adds the [TimeSheetWork](TimeSheetWork.md) that is specified by the [TimeSheetWorkCreationInformation](TimeSheetWorkCreationInformation.md) object to the collection.

##### Syntax

```
TimeSheetWork Add(TimeSheetWorkCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[TimeSheetWorkCreationInformation](TimeSheetWorkCreationInformation.md)|The properties that can be set when creating a time sheet work.|

##### Return Value

[TimeSheetWork](TimeSheetWork.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [TimeSheetWork](TimeSheetWork.md) from the collection with the Guid value.

##### Syntax

```
TimeSheetWork GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [TimeSheetWork](TimeSheetWork.md).|

##### Return Value

[TimeSheetWork](TimeSheetWork.md)

#### <a name="GetByStartDate_DateTime_start_"></a>GetByStartDate(DateTime start)
 
Gets a timesheet actual work object from the collection with a specified start date.

##### Syntax

```
TimeSheetWork GetByStartDate(DateTime start)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start|DateTime|The start date and time.|

##### Return Value

[TimeSheetWork](TimeSheetWork.md)

#### <a name="Remove_[TimeSheetWork]_TimeSheetWork.md__work_"></a>Remove([TimeSheetWork](TimeSheetWork.md) work)
 
Removes the specified [TimeSheetWork](TimeSheetWork.md) from the collection.

##### Syntax

```
Boolean Remove(TimeSheetWork work)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|work|[TimeSheetWork](TimeSheetWork.md)|The [TimeSheetWork](TimeSheetWork.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[TimeSheetLine](TimeSheetLine.md)<br/>
[TimeSheetWork](TimeSheetWork.md)<br/>
[TimeSheetWorkCreationInformation](TimeSheetWorkCreationInformation.md)<br/>
