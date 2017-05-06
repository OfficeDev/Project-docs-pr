[comment]: # (Name:ResourceEngagement)
[comment]: # (Name:Microsoft.ProjectServer.ResourceEngagement)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ResourceEngagement class

inherits members from [Engagement](Engagement.md)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ResourceEngagement 
```
### JSOM

```javascript
PS.ResourceEngagement
```
### REST Interface

Supported.

```
PS.ResourceEngagement

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Engagements('{engagementid}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="ApprovedFinish"></a>ApprovedFinish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="ApprovedMaxUnits"></a>ApprovedMaxUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double||
|<a name="ApprovedStart"></a>ApprovedStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="ApprovedWork"></a>ApprovedWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String||
|<a name="ApprovedWorkMilliseconds"></a>ApprovedWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|<a name="ApprovedWorkTimeSpan"></a>ApprovedWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan||
|<a name="RequestedFinish"></a>RequestedFinish|&#x2713;|&#x2713;|&#x2713;|DateTime||
|<a name="RequestedMaxUnits"></a>RequestedMaxUnits|&#x2713;|&#x2713;|&#x2713;|Double||
|<a name="RequestedStart"></a>RequestedStart|&#x2713;|&#x2713;|&#x2713;|DateTime||
|<a name="RequestedWork"></a>RequestedWork|&#x2713;|&#x2713;|&#x2713;|String||
|<a name="RequestedWorkMilliseconds"></a>RequestedWorkMilliseconds||&#x2713;|&#x2713;|Integer||
|<a name="RequestedWorkTimeSpan"></a>RequestedWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan||

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the resource engagement object.|
|[GetTimephased(DateTime start, DateTime end, TimeScale timescale, EngagementContourType contourType)](#GetTimephased_DateTime_start,_DateTime_end,_[TimeScale]_TimeScale.md__timescale,_[EngagementContourType]_EngagementContourType.md__contourType_)|&#x2713;|&#x2713;||[ResourceEngagementTimephasedCollection](ResourceEngagementTimephasedCollection.md)||
|[GetTimephasedByUrl(String start, String end, String scale, String contourType)](#GetTimephasedByUrl_String_start,_String_end,_String_scale,_String_contourType_)|||&#x2713;|[ResourceEngagementTimephasedCollection](ResourceEngagementTimephasedCollection.md)||

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the resource engagement object.

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
ResourceEngagementTimephasedCollection GetTimephased(DateTime start, DateTime end, TimeScale timescale, EngagementContourType contourType)
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

[ResourceEngagementTimephasedCollection](ResourceEngagementTimephasedCollection.md)

#### <a name="GetTimephasedByUrl_String_start,_String_end,_String_scale,_String_contourType_"></a>GetTimephasedByUrl(String start, String end, String scale, String contourType)
 

##### Syntax

```
ResourceEngagementTimephasedCollection GetTimephasedByUrl(String start, String end, String scale, String contourType)
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

[ResourceEngagementTimephasedCollection](ResourceEngagementTimephasedCollection.md)

## <a name="seeAlso"></a>See Also

[ResourceEngagementCollection](ResourceEngagementCollection.md)<br/>
