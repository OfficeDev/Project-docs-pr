

# DraftProjectResource

Represents an enterprise resource in a checked-out project. A resource can be a work resource, a material resource, or a cost resource.

[DraftProjectResource](DraftProjectResource.md) inherits from the [ProjectResource](ProjectResource.md) object. 

## Syntax

### CSOM

```
DraftProjectResource 
```

### JSOM

```
PS.DraftProjectResource
```

### REST Interface

This resource supports the DELETE, MERGE, and PUT HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Draft/ProjectResources('resourceid')
```

## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Assignments|&#x2713;|&#x2713;|&#x2713;|[DraftAssignmentCollection](DraftAssignmentCollection.md)|Gets the assignments that are associated with the resource.|
|CanLevel|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets a value that indicates whether resource leveling can be performed on the resource.|
|Code|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets any code, abbreviation, or number that is entered as part of the information about the resource.|
|CostAccrual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[AccrueAt](AccrueAt.md)|Gets a value that represents how and when to charge resource costs to the cost of a task.|
|CostCenter|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets any code, abbreviation, or number that has been entered as part of the information about the resource.|
|CostPerUse|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets the cost per use of the resource.|
|DefaultAssignmentOwner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the default assignment owner.|
|DefaultBookingType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[BookingType](BookingType.md)|Gets the default booking type for the resource.|
|Email|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the email address of the resource.|
|FieldValues|&#x2713;|&#x2713;||Dictionary<String,Object>|Gets the collection of custom fields that have values set for the project resource.|
|Group|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the name of a group to which a resource belongs.|
|Initials|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the short name for the resource.|
|Item|&#x2713;&#x02B7;|&#x2713;&#x02B7;||Dictionary<string, Object>|Gets a resource item in the published project.|
|MaterialLabel|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the unit of measure for a material resource, which can be supplies or other consumable items that are used in a project.|
|MaximumCapacity|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets the percentage, or the number of units, that represent the maximum capacity for which the resource is available during the current time period.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the name of the project resource.|
|OvertimeRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets the hourly rate of pay for overtime for the resource.|
|OvertimeRateUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[OvertimeRateFormat](OvertimeRateFormat.md)|Gets the rate description format in which the overtime rate is displayed.|
|Phonetics|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets phonetic information in either the Japanese Hiragana writing system or the Katakana writing system for resource names.|
|StandardRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets the rate of pay per hour for regular, non-overtime work performed by the resource.|
|StandardRateUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[StandardRateFormat](StandardRateFormat.md)|Gets the rate description format in which the standard rate is displayed.|

### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#deleteobject)|&#x2713;| &#x2713;|&#x2713;|void|Deletes the [DraftProjectResource](DraftProjectResource.md) object.|
|[SetCustomFieldValue(String fieldName, Object value)](#setcustomfieldvalue)|&#x2713;| &#x2713;| |void|Sets a custom field on the project resource.|


## Method Details

### <a name="deleteobject"></a> DeleteObject()

Deletes the [DraftProjectResource](DraftProjectResource.md) object.

#### Syntax

```
DeleteObject()
```

#### Parameters

none

#### Return value

void

### <a name="setcustomfieldvalue"></a> SetCustomFieldValue(String fieldName, Object value)

Sets a custom field on the project resource.

#### Syntax

```
SetCustomFieldValue(String fieldName, Object value)
```

#### Parameters

|**Name**|**Type**|**Description**|
|:-----|:-----|:-----|
|fieldName|String| The name of the custom field.|
|value |Object|The value to be set for the custom field.|


#### Return value

void


## See Also

[ProjectResource](ProjectResource.md)
