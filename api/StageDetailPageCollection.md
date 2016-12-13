[comment]: # (Name:StageDetailPageCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# StageDetailPageCollection

Represents a collection of project detail pages (PDPs) that are visible in a workflow stage.



## Syntax

### CSOM

```C#
Class StageDetailPageCollection 
```
### JSOM

```
PS.StageDetailPageCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Stages('{stageid}')/ProjectDetailPages
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([StageDetailPageCreationInformation](StageDetailPageCreationInformation.md) parameters)](#Add_[StageDetailPageCreationInformation]_StageDetailPageCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[StageDetailPage](StageDetailPage.md)|Adds a project detail page to the collection of PDPs that are visible in a workflow stage.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[StageDetailPage](StageDetailPage.md)|Gets a PDP object from the collection of PDPs that are associated with a workflow stage, by using the PDP GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[StageDetailPage](StageDetailPage.md)|Gets a PDP object from the collection of PDPs that are associated with a workflow stage, by using a string identifier.|
|[Remove([StageDetailPage](StageDetailPage.md) pdp)](#Remove_[StageDetailPage]_StageDetailPage.md__pdp_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified project detail page from the collection of PDPs that are visible in a workflow stage.|



## Method Details


### <a id="Add_[StageDetailPageCreationInformation]_StageDetailPageCreationInformation.md__parameters_"></a>Add([StageDetailPageCreationInformation](StageDetailPageCreationInformation.md) parameters)
 
Adds a project detail page to the collection of PDPs that are visible in a workflow stage.

#### Syntax

```
StageDetailPage Add(StageDetailPageCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [StageDetailPageCreationInformation](StageDetailPageCreationInformation.md) | A StagePDPCreationInformation object.


#### Return Value

[StageDetailPage](StageDetailPage.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a PDP object from the collection of PDPs that are associated with a workflow stage, by using the PDP GUID.

#### Syntax

```
StageDetailPage GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | The GUID of the PDP.


#### Return Value

[StageDetailPage](StageDetailPage.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a PDP object from the collection of PDPs that are associated with a workflow stage, by using a string identifier.

#### Syntax

```
StageDetailPage GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string identifier of a stage PDP.


#### Return Value

[StageDetailPage](StageDetailPage.md)

### <a id="Remove_[StageDetailPage]_StageDetailPage.md__pdp_"></a>Remove([StageDetailPage](StageDetailPage.md) pdp)
 
Removes the specified project detail page from the collection of PDPs that are visible in a workflow stage.

#### Syntax

```
Boolean Remove(StageDetailPage pdp)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|pdp| [StageDetailPage](StageDetailPage.md) | The project detail page to remove.


#### Return Value

Boolean


## See Also
