[comment]: # (Name:ProjectEngagementTimephasedCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# ProjectEngagementTimephasedCollection





## Syntax

### CSOM

```C#
Class ProjectEngagementTimephasedCollection 
```
### JSOM

```
PS.ProjectEngagementTimephasedCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Engagements('{engagementid}')/GetTimephasedByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}',contourType='{contourType}')
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetByStart(DateTime date)](#GetByStart_DateTime_date_)|&#x2713;|&#x2713;||[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)||
|[GetByStartUrl(String date)](#GetByStartUrl_String_date_)|||&#x2713;|[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)||



## Method Details


### <a id="GetByStart_DateTime_date_"></a>GetByStart(DateTime date)
 


#### Syntax

```
ProjectEngagementTimephasedPeriod GetByStart(DateTime date)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|date| DateTime | 


#### Return Value

[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)

### <a id="GetByStartUrl_String_date_"></a>GetByStartUrl(String date)
 


#### Syntax

```
ProjectEngagementTimephasedPeriod GetByStartUrl(String date)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|date| String | 


#### Return Value

[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)


## See Also
