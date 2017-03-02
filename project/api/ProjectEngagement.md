[comment]: # (Name:ProjectEngagement)
[comment]: # (Name:Microsoft.ProjectServer.ProjectEngagement)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectEngagement class

inherits members from [Engagement](Engagement.md)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectEngagement 
```
### JSOM

```javascript
PS.ProjectEngagement
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.ProjectEngagement

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Engagements('{engagementid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="ApprovedFinish"></a>ApprovedFinish|&#x2713;|&#x2713;|&#x2713;|DateTime||
|<a name="ApprovedMaxUnits"></a>ApprovedMaxUnits|&#x2713;|&#x2713;|&#x2713;|Double||
|<a name="ApprovedStart"></a>ApprovedStart|&#x2713;|&#x2713;|&#x2713;|DateTime||
|<a name="ApprovedWork"></a>ApprovedWork|&#x2713;|&#x2713;|&#x2713;|String||
|<a name="ApprovedWorkMilliseconds"></a>ApprovedWorkMilliseconds||&#x2713;|&#x2713;|Integer||
|<a name="ApprovedWorkTimeSpan"></a>ApprovedWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan||
|<a name="HasUnsubmittedChanges"></a>HasUnsubmittedChanges|&#x2713;|&#x2713;|&#x2713;|Boolean||
|<a name="Project"></a>Project|&#x2713;|&#x2713;|&#x2713;|[Project](Project.md)||
|<a name="RequestedFinish"></a>RequestedFinish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="RequestedMaxUnits"></a>RequestedMaxUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double||
|<a name="RequestedStart"></a>RequestedStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="RequestedWork"></a>RequestedWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String||
|<a name="RequestedWorkMilliseconds"></a>RequestedWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|<a name="RequestedWorkTimeSpan"></a>RequestedWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan||

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the project engagement object.|
|[GetTimephased(DateTime start, DateTime end, TimeScale timescale, EngagementContourType contourType)](#GetTimephased_DateTime_start,_DateTime_end,_[TimeScale]_TimeScale.md__timescale,_[EngagementContourType]_EngagementContourType.md__contourType_)|&#x2713;|&#x2713;||[ProjectEngagementTimephasedCollection](ProjectEngagementTimephasedCollection.md)||
|[GetTimephasedByUrl(String start, String end, String scale, String contourType)](#GetTimephasedByUrl_String_start,_String_end,_String_scale,_String_contourType_)|||&#x2713;|[ProjectEngagementTimephasedCollection](ProjectEngagementTimephasedCollection.md)||

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the project engagement object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

#### <a name="GetTimephased_DateTime_start,_DateTime_end,_[TimeScale]_TimeScale.md__timescale,_[EngagementContourType]_EngagementContourType.md__contourType_"></a>GetTimephased(DateTime start, DateTime end, [TimeScale](TimeScale.md) timescale, [EngagementContourType](EngagementContourType.md) contourType)
 

##### Syntax

```
ProjectEngagementTimephasedCollection GetTimephased(DateTime start, DateTime end, TimeScale timescale, EngagementContourType contourType)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start|DateTime||
|end|DateTime||
|timescale|[TimeScale](TimeScale.md)||
|contourType|[EngagementContourType](EngagementContourType.md)||

##### Return Value

[ProjectEngagementTimephasedCollection](ProjectEngagementTimephasedCollection.md)

#### <a name="GetTimephasedByUrl_String_start,_String_end,_String_scale,_String_contourType_"></a>GetTimephasedByUrl(String start, String end, String scale, String contourType)
 

##### Syntax

```
ProjectEngagementTimephasedCollection GetTimephasedByUrl(String start, String end, String scale, String contourType)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start|String||
|end|String||
|scale|String||
|contourType|String||

##### Return Value

[ProjectEngagementTimephasedCollection](ProjectEngagementTimephasedCollection.md)

## <a name="seeAlso"></a>See Also

[ProjectEngagementCollection](ProjectEngagementCollection.md)<br/>
[ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md)<br/>
