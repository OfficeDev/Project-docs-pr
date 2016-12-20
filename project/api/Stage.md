[comment]: # (Name:Stage)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# Stage

Represents a stage in a project workflow.



## Syntax

### CSOM

```C#
Class Stage 
```
### JSOM

```
PS.Stage
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Stages('{stageid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Behavior|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[StrategicImpactBehavior](StrategicImpactBehavior.md)|Gets or sets the Strategic Impact value for a stage; for example, Read Only.|
|CheckInRequired|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether project check in is required.|
|CustomFields|&#x2713;|&#x2713;|&#x2713;|[StageCustomFieldCollection](StageCustomFieldCollection.md)|Gets the collection of all custom field objects that have values set for the stage.|
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the stage description.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the stage.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the stage.|
|Phase|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[Phase](Phase.md)|Gets or sets the phase that contains the stage.|
|ProjectDetailPages|&#x2713;|&#x2713;|&#x2713;|[StageDetailPageCollection](StageDetailPageCollection.md)|Gets a collection of project detail pages that are associated with the stage.|
|SubmitDescription|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the stage description for submit.|
|WorkflowStatusPage|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[ProjectDetailPage](ProjectDetailPage.md)|Gets or sets the workflow status project detail page for the stage.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the Stage object.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the Stage object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
