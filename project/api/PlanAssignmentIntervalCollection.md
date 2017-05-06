[comment]: # (Name:PlanAssignmentIntervalCollection)
[comment]: # (Name:Microsoft.ProjectServer.PlanAssignmentIntervalCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PlanAssignmentIntervalCollection class

inherits members from [ClientObjectCollection<PlanAssignmentInterval>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of PlanAssignmentInterval objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PlanAssignmentIntervalCollection 
```
### JSOM

```javascript
PS.PlanAssignmentIntervalCollection
```
### REST Interface

Supported.

```
PS.PlanAssignmentIntervalCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')/Assignments('{assignmentid}')/Intervals
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[PlanAssignmentInterval](PlanAssignmentInterval.md)|Gets a [PlanAssignmentInterval](PlanAssignmentInterval.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[PlanAssignmentInterval](PlanAssignmentInterval.md)|Gets a [PlanAssignmentInterval](PlanAssignmentInterval.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetById(String id)](#GetById_String_id_)|&#x2713;|&#x2713;|&#x2713;|[PlanAssignmentInterval](PlanAssignmentInterval.md)|Gets a [PlanAssignmentInterval](PlanAssignmentInterval.md) from the collection with the Guid value.|
|[GetByStart(DateTime start)](#GetByStart_DateTime_start_)|&#x2713;|&#x2713;|&#x2713;|[PlanAssignmentInterval](PlanAssignmentInterval.md)|Gets a plan assignment interval from the collection of plan assignment intervals, with the specified start date.|

<br/>
#### Method Details

#### <a name="GetById_String_id_"></a>GetById(String id)
 
Gets a [PlanAssignmentInterval](PlanAssignmentInterval.md) from the collection with the Guid value.

##### Syntax

```
PlanAssignmentInterval GetById(String id)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id|String|The id of the [PlanAssignmentInterval](PlanAssignmentInterval.md).|

##### Return Value

[PlanAssignmentInterval](PlanAssignmentInterval.md)

#### <a name="GetByStart_DateTime_start_"></a>GetByStart(DateTime start)
 
Gets a plan assignment interval from the collection of plan assignment intervals, with the specified start date.

##### Syntax

```
PlanAssignmentInterval GetByStart(DateTime start)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start|DateTime|A start date.|

##### Return Value

[PlanAssignmentInterval](PlanAssignmentInterval.md)

## <a name="seeAlso"></a>See Also

[PlanAssignment](PlanAssignment.md)<br/>
[PlanAssignmentInterval](PlanAssignmentInterval.md)<br/>
