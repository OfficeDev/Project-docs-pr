[comment]: # (Name:ProjectEngagement)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# ProjectEngagement





## Syntax

### CSOM

```C#
Class ProjectEngagement 
```
### JSOM

```
PS.ProjectEngagement
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Engagements('{engagementid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ApprovedFinish|&#x2713;|&#x2713;|&#x2713;|DateTime||
|ApprovedMaxUnits|&#x2713;|&#x2713;|&#x2713;|Double||
|ApprovedStart|&#x2713;|&#x2713;|&#x2713;|DateTime||
|ApprovedWork|&#x2713;|&#x2713;|&#x2713;|String||
|ApprovedWorkMilliseconds||&#x2713;|&#x2713;|Integer||
|ApprovedWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan||
|HasUnsubmittedChanges|&#x2713;|&#x2713;|&#x2713;|Boolean||
|Project|&#x2713;|&#x2713;|&#x2713;|[Project](Project.md)||
|RequestedFinish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|RequestedMaxUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double||
|RequestedStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|RequestedWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String||
|RequestedWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|RequestedWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan||





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void||
|[GetTimephased(DateTime start, DateTime end, [TimeScale](TimeScale.md) timescale, [EngagementContourType](EngagementContourType.md) contourType)](#GetTimephased_DateTime_start,_DateTime_end,_[TimeScale]_TimeScale.md__timescale,_[EngagementContourType]_EngagementContourType.md__contourType_)|&#x2713;|&#x2713;||[ProjectEngagementTimephasedCollection](ProjectEngagementTimephasedCollection.md)||
|[GetTimephasedByUrl(String start, String end, String scale, String contourType)](#GetTimephasedByUrl_String_start,_String_end,_String_scale,_String_contourType_)|||&#x2713;|[ProjectEngagementTimephasedCollection](ProjectEngagementTimephasedCollection.md)||



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
ProjectEngagementTimephasedCollection GetTimephased(DateTime start, DateTime end, TimeScale timescale, EngagementContourType contourType)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| DateTime | 
|end| DateTime | 
|timescale| [TimeScale](TimeScale.md) | 
|contourType| [EngagementContourType](EngagementContourType.md) | 


#### Return Value

[ProjectEngagementTimephasedCollection](ProjectEngagementTimephasedCollection.md)

### <a id="GetTimephasedByUrl_String_start,_String_end,_String_scale,_String_contourType_"></a>GetTimephasedByUrl(String start, String end, String scale, String contourType)
 


#### Syntax

```
ProjectEngagementTimephasedCollection GetTimephasedByUrl(String start, String end, String scale, String contourType)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| String | 
|end| String | 
|scale| String | 
|contourType| String | 


#### Return Value

[ProjectEngagementTimephasedCollection](ProjectEngagementTimephasedCollection.md)


## See Also
