[comment]: # (Name:CustomFieldCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.CustomFieldCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>CustomFieldCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [CustomField](CustomField.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class CustomFieldCreationInformation 
```
### JSOM

```javascript
PS.CustomFieldCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.CustomFieldCreationInformation

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/CustomFields/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Description':'value', 
		'EntityTypeId':'value', 
		'FieldType':'value', 
		'Formula':'value', 
		'Id':'value', 
		'IsEditableInVisibility':'value', 
		'IsMultilineText':'value', 
		'IsRequired':'value', 
		'IsWorkflowControlled':'value', 
		'LookupAllowMultiSelect':'value', 
		'LookupDefaultValue':'value', 
		'LookupTableId':'value', 
		'Name':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the custom field.|
|<a name="EntityType"></a>EntityType|&#x2713;&#x02B7;|&#x2713;&#x02B7;||[EntityType](EntityType.md)|Gets or sets the type of entity (project, task, or resource) for the custom field.|
|<a name="EntityTypeId"></a>EntityTypeId|||&#x2713;&#x02B7;|Guid|Gets or sets the type of entity type id(project, task, or resource) for the custom field.|
|<a name="FieldType"></a>FieldType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CustomFieldType](CustomFieldType.md)|Gets or sets the type of the custom field.|
|<a name="Formula"></a>Formula|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the formula that calculates the value of a custom field.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the custom field.|
|<a name="IsEditableInVisibility"></a>IsEditableInVisibility|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether the custom field value can be edited in project site Visibility mode.|
|<a name="IsMultilineText"></a>IsMultilineText|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether a text custom field can contain multiple lines.|
|<a name="IsRequired"></a>IsRequired|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether a value for the custom field is required when the entity (project, resource, or task) is created.|
|<a name="IsWorkflowControlled"></a>IsWorkflowControlled|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether the custom field value is controlled by a workflow.|
|<a name="LookupAllowMultiSelect"></a>LookupAllowMultiSelect|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicate whether multiple lookup table values can be set for this custom field|
|<a name="LookupDefaultValue"></a>LookupDefaultValue|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the default lookup table value.|
|<a name="LookupTable"></a>LookupTable|&#x2713;&#x02B7;|&#x2713;&#x02B7;||[LookupTable](LookupTable.md)|Gets or sets the LookupTable object for a text custom field.|
|<a name="LookupTableId"></a>LookupTableId|||&#x2713;&#x02B7;|Guid|Gets or sets the LookupTable Id for a text custom field.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the custom field.|

## <a name="seeAlso"></a>See Also

[CustomField](CustomField.md)<br/>
[CustomFieldCollection](CustomFieldCollection.md)<br/>
