[comment]: # (Name:CustomFieldCreationInformation)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# CustomFieldCreationInformation

Provides information that is used in the creation of a custom field.



## Syntax

### CSOM

```C#
Class CustomFieldCreationInformation 
```
### JSOM

```
PS.CustomFieldCreationInformation
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
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the custom field.|
|EntityType|&#x2713;&#x02B7;|&#x2713;&#x02B7;||[Entity](Entity.md)|Gets or sets the type of entity (project, task, or resource) for the custom field.|
|FieldType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[Type](Type.md)|Gets or sets the type of the custom field.|
|Formula|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the formula that calculates the value of a custom field.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the custom field.|
|IsEditableInVisibility|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether the custom field value can be edited in project site Visibility mode.|
|IsMultilineText|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether a text custom field can contain multiple lines.|
|IsRequired|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether a value for the custom field is required when the entity (project, resource, or task) is created.|
|IsWorkflowControlled|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether the custom field value is controlled by a workflow.|
|LookupAllowMultiSelect|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicate whether multiple lookup table values can be set for this custom field|
|LookupDefaultValue|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the default lookup table value.|
|LookupTable|&#x2713;&#x02B7;|&#x2713;&#x02B7;||[LookupTable](LookupTable.md)|Gets or sets the LookupTable object for a text custom field.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the custom field.|






## See Also
