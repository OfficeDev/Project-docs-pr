[comment]: # (Name:ResourceEngagement)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# ResourceEngagement





## Syntax

### CSOM

```C#
Class ResourceEngagement 
```
### JSOM

```
PS.ResourceEngagement
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/EnterpriseResources('{resourceid}')/Engagements('{engagementid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ApprovedFinish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|ApprovedMaxUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double||
|ApprovedStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|ApprovedWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String||
|ApprovedWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|ApprovedWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan||
|RequestedFinish|&#x2713;|&#x2713;|&#x2713;|DateTime||
|RequestedMaxUnits|&#x2713;|&#x2713;|&#x2713;|Double||
|RequestedStart|&#x2713;|&#x2713;|&#x2713;|DateTime||
|RequestedWork|&#x2713;|&#x2713;|&#x2713;|String||
|RequestedWorkMilliseconds||&#x2713;|&#x2713;|Integer||
|RequestedWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan||





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void||
|[GetTimephased(DateTime start, DateTime end, [TimeScale](TimeScale.md) timescale, [EngagementContourType](EngagementContourType.md) contourType)](#GetTimephased_DateTime_start,_DateTime_end,_[TimeScale]_TimeScale.md__timescale,_[EngagementContourType]_EngagementContourType.md__contourType_)|&#x2713;|&#x2713;||[ResourceEngagementTimephasedCollection](ResourceEngagementTimephasedCollection.md)||
|[GetTimephasedByUrl(String start, String end, String scale, String contourType)](#GetTimephasedByUrl_String_start,_String_end,_String_scale,_String_contourType_)|||&#x2713;|[ResourceEngagementTimephasedCollection](ResourceEngagementTimephasedCollection.md)||



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 


#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void

### <a id="GetTimephased_DateTime_start,_DateTime_end,_[TimeScale]_TimeScale.md__timescale,_[EngagementContourType]_EngagementContourType.md__contourType_"></a>GetTimephased(DateTime start, DateTime end, [TimeScale](TimeScale.md) timescale, [EngagementContourType](EngagementContourType.md) contourType)
 


#### Syntax

```
ResourceEngagementTimephasedCollection GetTimephased(DateTime start, DateTime end, TimeScale timescale, EngagementContourType contourType)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| DateTime | 
|end| DateTime | 
|timescale| [TimeScale](TimeScale.md) | 
|contourType| [EngagementContourType](EngagementContourType.md) | 


#### Return Value

[ResourceEngagementTimephasedCollection](ResourceEngagementTimephasedCollection.md)

### <a id="GetTimephasedByUrl_String_start,_String_end,_String_scale,_String_contourType_"></a>GetTimephasedByUrl(String start, String end, String scale, String contourType)
 


#### Syntax

```
ResourceEngagementTimephasedCollection GetTimephasedByUrl(String start, String end, String scale, String contourType)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| String | 
|end| String | 
|scale| String | 
|contourType| String | 


#### Return Value

[ResourceEngagementTimephasedCollection](ResourceEngagementTimephasedCollection.md)


## See Also
