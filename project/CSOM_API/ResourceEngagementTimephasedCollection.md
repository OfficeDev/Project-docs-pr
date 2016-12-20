[comment]: # (Name:ResourceEngagementTimephasedCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# ResourceEngagementTimephasedCollection





## Syntax

### CSOM

```C#
Class ResourceEngagementTimephasedCollection 
```
### JSOM

```
PS.ResourceEngagementTimephasedCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/EnterpriseResources('{resourceid}')/Engagements('{engagementid}')/GetTimephasedByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}',contourType='{contourType}')
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetByStart(DateTime date)](#GetByStart_DateTime_date_)|&#x2713;|&#x2713;||[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)||
|[GetByStartUrl(String date)](#GetByStartUrl_String_date_)|||&#x2713;|[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)||



## Method Details


### <a id="GetByStart_DateTime_date_"></a>GetByStart(DateTime date)
 


#### Syntax

```
ResourceEngagementTimephasedPeriod GetByStart(DateTime date)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|date| DateTime | 


#### Return Value

[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)

### <a id="GetByStartUrl_String_date_"></a>GetByStartUrl(String date)
 


#### Syntax

```
ResourceEngagementTimephasedPeriod GetByStartUrl(String date)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|date| String | 


#### Return Value

[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)


## See Also
