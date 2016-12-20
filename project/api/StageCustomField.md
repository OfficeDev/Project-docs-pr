[comment]: # (Name:StageCustomField)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# StageCustomField

Represents a custom field for a project stage.



## Syntax

### CSOM

```C#
Class StageCustomField 
```
### JSOM

```
PS.StageCustomField
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Stages('{stageid}')/CustomFields('{fieldid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the stage custom field.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the custom field.|
|ReadOnly|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the customer field is read-only in the stage.|
|Required|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the custom field is required in the stage.|
|Stage|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets a link to the Stage entity.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the StageCustomField object.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the StageCustomField object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
