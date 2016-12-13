[comment]: # (Name:WorkflowDesignerFieldCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:23Z)

# WorkflowDesignerFieldCollection

Represents a filtered collection of enterprise project custom fields that can be used in a workflow designer.



## Syntax

### CSOM

```C#
Class WorkflowDesignerFieldCollection 
```
### JSOM

```
PS.WorkflowDesignerFieldCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/?????
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[WorkflowDesignerField](WorkflowDesignerField.md)|Gets a workflow designer field from the collection with the [Id](18d798a4-03d6-4b82-67c5-f6071edc6f6f.md) value.|



## Method Details


### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a workflow designer field from the collection with the [Id](18d798a4-03d6-4b82-67c5-f6071edc6f6f.md) value.

#### Syntax

```
WorkflowDesignerField GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the GUID for the workflow designer field.


#### Return Value

[WorkflowDesignerField](WorkflowDesignerField.md)


## See Also
