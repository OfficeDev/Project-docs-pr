[comment]: # (Name:CustomField)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# CustomField

Contains the properties and methods that are used to create an enterprise custom field.



## Syntax

### CSOM

```C#
Class CustomField 
```
### JSOM

```
PS.CustomField
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/CustomFields('{fieldid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|AppAlternateId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the alternate custom field GUID that is specified in an App package for Project Online.|
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the custom field.|
|EntityType|&#x2713;|&#x2713;|&#x2713;|[Entity](Entity.md)|Gets the type of entity (project, task, or resource) for the custom field.|
|FieldType|&#x2713;|&#x2713;|&#x2713;|[Type](Type.md)|Gets the type of the custom field.|
|Formula|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the formula that calculates the value of a custom field.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the custom field.|
|InternalName|&#x2713;|&#x2713;|&#x2713;|String|Gets the internal name of the custom field. Reserved for internal use.|
|IsEditableInVisibility|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the value is editable in project site visibility mode.|
|IsMultilineText|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a text custom field can contain multiple lines.|
|IsRequired|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a value for the custom field is required when the entity (project, resource, or task) is created.|
|IsWorkflowControlled|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the custom field value is controlled by a workflow.|
|LookupAllowMultiSelect|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether multiple lookup table values can be set for the custom field.|
|LookupDefaultValue|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the default value in a lookup table for a custom field.|
|LookupEntries|&#x2713;|&#x2713;|&#x2713;|[LookupEntryCollection](LookupEntryCollection.md)|Gets a collection of valid lookup table entries for this field.|
|LookupTable|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[LookupTable](LookupTable.md)|Gets or sets the LookupTable object for a text custom field.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the custom field.|
|RollsDownToAssignments|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a custom field is set to automatically become a part of the list of available fields for the Assignment cube dimension.|
|RollupType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CustomFieldRollupType](CustomFieldRollupType.md)|Gets or sets the way that the custom field rolls up to summary tasks.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the CustomField object.|



## Method Details


### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the CustomField object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
