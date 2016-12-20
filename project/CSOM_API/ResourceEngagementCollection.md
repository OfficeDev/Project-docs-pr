[comment]: # (Name:ResourceEngagementCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# ResourceEngagementCollection





## Syntax

### CSOM

```C#
Class ResourceEngagementCollection 
```
### JSOM

```
PS.ResourceEngagementCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/EnterpriseResources('{resourceid}')/Engagements
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[ResourceEngagement](ResourceEngagement.md)||
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[ResourceEngagement](ResourceEngagement.md)||
|[Remove([Engagement](Engagement.md) engagement)](#Remove_[Engagement]_Engagement.md__engagement_)|&#x2713;|&#x2713;||Boolean||
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void||



## Method Details


### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 


#### Syntax

```
ResourceEngagement GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | 


#### Return Value

[ResourceEngagement](ResourceEngagement.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 


#### Syntax

```
ResourceEngagement GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | 


#### Return Value

[ResourceEngagement](ResourceEngagement.md)

### <a id="Remove_[Engagement]_Engagement.md__engagement_"></a>Remove([Engagement](Engagement.md) engagement)
 


#### Syntax

```
Boolean Remove(Engagement engagement)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|engagement| [Engagement](Engagement.md) | 


#### Return Value

Boolean

### <a id="Update__"></a>Update()
 


#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
