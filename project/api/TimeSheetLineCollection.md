[comment]: # (Name:TimeSheetLineCollection)
[comment]: # (Name:Microsoft.ProjectServer.TimeSheetLineCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheetLineCollection class

inherits members from [ClientObjectCollection<TimeSheetLine>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of timesheet lines.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TimeSheetLineCollection 
```
### JSOM

```javascript
PS.TimeSheetLineCollection
```
### REST Interface

Supported.

```
PS.TimeSheetLineCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[TimeSheetLine](TimeSheetLine.md)|Gets a [TimeSheetLine](TimeSheetLine.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[TimeSheetLine](TimeSheetLine.md)|Gets a [TimeSheetLine](TimeSheetLine.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{TimeSheetLineId}&#39;](#&#39;{TimeSheetLineId}&#39;)|||&#x2713;|[TimeSheetLine](TimeSheetLine.md)|Gets a [TimeSheetLine](TimeSheetLine.md) from the collection with the specified TimeSheetLineId.|
|[Add(TimeSheetLineCreationInformation parameters)](#Add_[TimeSheetLineCreationInformation]_TimeSheetLineCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetLine](TimeSheetLine.md)|Adds the [TimeSheetLine](TimeSheetLine.md) that is specified by the [TimeSheetLineCreationInformation](TimeSheetLineCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetLine](TimeSheetLine.md)|Gets a [TimeSheetLine](TimeSheetLine.md) from the collection with the Guid value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetLine](TimeSheetLine.md)|Gets a [TimeSheetLine](TimeSheetLine.md) from the collection with the Id value.|
|[Remove(TimeSheetLine line)](#Remove_[TimeSheetLine]_TimeSheetLine.md__line_)|&#x2713;|&#x2713;||Boolean|Removes the specified [TimeSheetLine](TimeSheetLine.md) from the collection.|

<br/>
#### Method Details

#### <a name="&#39;{TimeSheetLineId}&#39;"></a>&#39;{TimeSheetLineId}&#39;
 
Gets a [TimeSheetLine](TimeSheetLine.md) from the collection with the specified TimeSheetLineId.

##### Syntax

```
TimeSheetLine http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines('{TimeSheetLineId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|TimeSheetLineId|String|the id of the TimeSheetLine|

##### Return Value

[TimeSheetLine](TimeSheetLine.md)

#### <a name="Add_[TimeSheetLineCreationInformation]_TimeSheetLineCreationInformation.md__parameters_"></a>Add([TimeSheetLineCreationInformation](TimeSheetLineCreationInformation.md) parameters)
 
Adds the [TimeSheetLine](TimeSheetLine.md) that is specified by the [TimeSheetLineCreationInformation](TimeSheetLineCreationInformation.md) object to the collection.

##### Syntax

```
TimeSheetLine Add(TimeSheetLineCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[TimeSheetLineCreationInformation](TimeSheetLineCreationInformation.md)|The properties that can be set when creating a time sheet line.|

##### Return Value

[TimeSheetLine](TimeSheetLine.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [TimeSheetLine](TimeSheetLine.md) from the collection with the Guid value.

##### Syntax

```
TimeSheetLine GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [TimeSheetLine](TimeSheetLine.md)|

##### Return Value

[TimeSheetLine](TimeSheetLine.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [TimeSheetLine](TimeSheetLine.md) from the collection with the Id value.

##### Syntax

```
TimeSheetLine GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [TimeSheetLine](TimeSheetLine.md).|

##### Return Value

[TimeSheetLine](TimeSheetLine.md)

#### <a name="Remove_[TimeSheetLine]_TimeSheetLine.md__line_"></a>Remove([TimeSheetLine](TimeSheetLine.md) line)
 
Removes the specified [TimeSheetLine](TimeSheetLine.md) from the collection.

##### Syntax

```
Boolean Remove(TimeSheetLine line)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|line|[TimeSheetLine](TimeSheetLine.md)|The [TimeSheetLine](TimeSheetLine.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[TimeSheet](TimeSheet.md)<br/>
[TimeSheetLine](TimeSheetLine.md)<br/>
[TimeSheetLineCreationInformation](TimeSheetLineCreationInformation.md)<br/>
