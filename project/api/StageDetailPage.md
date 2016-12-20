[comment]: # (Name:StageDetailPage)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# StageDetailPage

Represents a project detail page (PDP) for a workflow stage.



## Syntax

### CSOM

```C#
Class StageDetailPage 
```
### JSOM

```
PS.StageDetailPage
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Stages('{stageid}')/ProjectDetailPages('{pageid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the PDP. Read-write String.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the PDP. Read-only Guid.|
|Page|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[ProjectDetailPage](ProjectDetailPage.md)|Gets or sets the PDP in a workflow stage. Read/write ProjectDetailPage.|
|Position|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the position of the PDP relative to the other PDPs that are displayed in the workflow stage.|
|RequiresAttention|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the PDP requires attention.|
|Stage|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets a link to the related workflow stage for the PDP. Read-only Stage. Read-only Stage.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the PDP for the workflow stage.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the PDP for the workflow stage.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
