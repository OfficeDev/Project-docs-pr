[comment]: # (Name:WorkflowDesignerField)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:23Z)

# WorkflowDesignerField

Represents a field that is created in a workflow designer.



## Syntax

### CSOM

```C#
Class WorkflowDesignerField 
```
### JSOM

```
PS.WorkflowDesignerField
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/?????
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|DisplayName|&#x2713;|&#x2713;|&#x2713;|String|Gets the workflow designer field display name|
|Id|&#x2713;|&#x2713;|&#x2713;|String|Gets the GUID of the workflow designer field.|
|IsLookupField|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the field uses a lookup table.|
|IsReadOnly|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the field is read-only.|
|LookupEntries|&#x2713;|&#x2713;|&#x2713;|[LookupEntryCollection](LookupEntryCollection.md)|Gets a collection of valid lookup table entries for the field.|
|SPFieldType|&#x2713;|&#x2713;|&#x2713;|SPFieldType|Gets the SPFieldType equivalent to the type of the Project Server field.|






## See Also
