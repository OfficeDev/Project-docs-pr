# Phase class

Represents a collection of stages that are grouped to identify a common set of activities in the project life cycle.

## Syntax

### CSOM

```
Class Phase 
```
### JSOM

```
PS.Phase
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Phases('{phaseid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets a phase description.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the object identifier as a GUID.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets a phase name.|
|Stages|&#x2713;|&#x2713;|&#x2713;|[StageCollection](StageCollection.md)|Gets a collection of stages for a phase.|




### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the Phase object.|



## Method Details


### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the Phase object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
