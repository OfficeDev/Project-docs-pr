[comment]: # (Name:TimeSheetPeriodCollection)
[comment]: # (Name:Microsoft.ProjectServer.TimeSheetPeriodCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheetPeriodCollection class

inherits members from [ClientObjectCollection<TimeSheetPeriod>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of TimeSheetPeriod objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TimeSheetPeriodCollection 
```
### JSOM

```javascript
PS.TimeSheetPeriodCollection
```
### REST Interface

Supported.

```
PS.TimeSheetPeriodCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/TimeSheetPeriods
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[TimeSheetPeriod](TimeSheetPeriod.md)|Gets a [TimeSheetPeriod](TimeSheetPeriod.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[TimeSheetPeriod](TimeSheetPeriod.md)|Gets a [TimeSheetPeriod](TimeSheetPeriod.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{TimeSheetPeriodId}&#39;](#&#39;{TimeSheetPeriodId}&#39;)|||&#x2713;|[TimeSheetPeriod](TimeSheetPeriod.md)|Gets a [TimeSheetPeriod](TimeSheetPeriod.md) from the collection with the specified TimeSheetPeriodId.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetPeriod](TimeSheetPeriod.md)|Gets a [TimeSheetPeriod](TimeSheetPeriod.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetPeriod](TimeSheetPeriod.md)|Gets a [TimeSheetPeriod](TimeSheetPeriod.md) from the collection with the Guid value.|

<br/>
#### Method Details

#### <a name="&#39;{TimeSheetPeriodId}&#39;"></a>&#39;{TimeSheetPeriodId}&#39;
 
Gets a [TimeSheetPeriod](TimeSheetPeriod.md) from the collection with the specified TimeSheetPeriodId.

##### Syntax

```
TimeSheetPeriod http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/TimeSheetPeriods('{TimeSheetPeriodId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|TimeSheetPeriodId|String|the id of the TimeSheetPeriod|

##### Return Value

[TimeSheetPeriod](TimeSheetPeriod.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [TimeSheetPeriod](TimeSheetPeriod.md) from the collection with the Id value.

##### Syntax

```
TimeSheetPeriod GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [TimeSheetPeriod](TimeSheetPeriod.md)|

##### Return Value

[TimeSheetPeriod](TimeSheetPeriod.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [TimeSheetPeriod](TimeSheetPeriod.md) from the collection with the Guid value.

##### Syntax

```
TimeSheetPeriod GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [TimeSheetPeriod](TimeSheetPeriod.md).|

##### Return Value

[TimeSheetPeriod](TimeSheetPeriod.md)

## <a name="seeAlso"></a>See Also

[ProjectContext](ProjectContext.md)<br/>
[TimeSheetPeriod](TimeSheetPeriod.md)<br/>
