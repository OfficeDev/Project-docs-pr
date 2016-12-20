[comment]: # (Name:ProjectEngagementCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# ProjectEngagementCollection





## Syntax

### CSOM

```C#
Class ProjectEngagementCollection 
```
### JSOM

```
PS.ProjectEngagementCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Engagements
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md) parameters)](#Add_[ProjectEngagementCreationInformation]_ProjectEngagementCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[ProjectEngagement](ProjectEngagement.md)||
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[ProjectEngagement](ProjectEngagement.md)||
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[ProjectEngagement](ProjectEngagement.md)||
|[Remove([Engagement](Engagement.md) engagement)](#Remove_[Engagement]_Engagement.md__engagement_)|&#x2713;|&#x2713;||Boolean||
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void||



## Method Details


### <a id="Add_[ProjectEngagementCreationInformation]_ProjectEngagementCreationInformation.md__parameters_"></a>Add([ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md) parameters)
 


#### Syntax

```
ProjectEngagement Add(ProjectEngagementCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md) | 


#### Return Value

[ProjectEngagement](ProjectEngagement.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 


#### Syntax

```
ProjectEngagement GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | 


#### Return Value

[ProjectEngagement](ProjectEngagement.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 


#### Syntax

```
ProjectEngagement GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | 


#### Return Value

[ProjectEngagement](ProjectEngagement.md)

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
