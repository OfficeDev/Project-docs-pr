[comment]: # (Name:DraftProjectResource)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>DraftProjectResource class

inherits members from [ProjectResource](ProjectResource.md)<br/>

<a name="description"></a>Represents an enterprise resource in a checked-out project. A resource can be a work resource, a material resource, or a cost resource.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class DraftProjectResource 
```
### JSOM

```JavaScript
PS.DraftProjectResource
```

### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE,  and DELETE HTTP commands.

```
PS.DraftProjectResource

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Draft/ProjectResources('{resourceid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the project.|
|<a name="Assignments"></a>Assignments|&#x2713;|&#x2713;|&#x2713;|[DraftAssignmentCollection](DraftAssignmentCollection.md)|Gets the assignments that are associated with the resource.|
|<a name="CanLevel"></a>CanLevel|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether resource leveling can be performed on the resource.|
|<a name="Code"></a>Code|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets any code, abbreviation, or number that is entered as part of the information about the resource.|
|<a name="CostAccrual"></a>CostAccrual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[AccrueAt](AccrueAt.md)|Gets or sets a value that represents how and when to charge resource costs to the cost of a task.|
|<a name="CostCenter"></a>CostCenter|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets any code, abbreviation, or number that has been entered as part of the information about the resource.|
|<a name="CostPerUse"></a>CostPerUse|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the cost per use of the resource.|
|<a name="DefaultAssignmentOwner"></a>DefaultAssignmentOwner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets or sets the default assignment owner.|
|<a name="DefaultBookingType"></a>DefaultBookingType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[BookingType](BookingType.md)|Gets or sets the default booking type for the resource.|
|<a name="Email"></a>Email|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the email address of the resource.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the project resource.|
|<a name="Group"></a>Group|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of a group to which a project resource belongs.|
|<a name="Initials"></a>Initials|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the short name for the resource.|
|<a name="Item"></a>Item||&#x2713;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the project.|
|<a name="MaterialLabel"></a>MaterialLabel|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the unit of measure for supplies or other consumable items that are used in a project.|
|<a name="MaximumCapacity"></a>MaximumCapacity|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the percentage, or the number of units, that represent the maximum capacity for which the resource is available during the current time period.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the project resource.|
|<a name="OvertimeRate"></a>OvertimeRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the hourly rate of pay for overtime for the resource.|
|<a name="OvertimeRateUnits"></a>OvertimeRateUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[OvertimeRateFormat](OvertimeRateFormat.md)|Gets or sets the rate description format in which the overtime rate is displayed.|
|<a name="Phonetics"></a>Phonetics|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets phonetic information in either the Japanese Hiragana writing system or the Katakana writing system for resource names.|
|<a name="StandardRate"></a>StandardRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the rate of pay per hour for regular, non-overtime work that is performed by the resource.|
|<a name="StandardRateUnits"></a>StandardRateUnits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[StandardRateFormat](StandardRateFormat.md)|Gets or sets the rate description format in which the standard rate is displayed.|

### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the [DraftProjectResource](DraftProjectResource.md) object.|
|[SetCustomFieldValue(String fieldName, Object value)](#SetCustomFieldValue_String_fieldName,_Object_value_)|&#x2713;|&#x2713;||void|Sets a custom field on the project resource.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()

Deletes the [DraftProjectResource](DraftProjectResource.md) object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

#### <a name="SetCustomFieldValue_String_fieldName,_Object_value_"></a>SetCustomFieldValue(String fieldName, Object value)

Sets a custom field on the project resource.

##### Syntax

```
void SetCustomFieldValue(String fieldName, Object value)
```

##### Parameters
|**Name**|**Type**|**Description**|
|:-----|:-----|:-----|
|fieldName|String| The name of the custom field.|
|value|Object|The value to be set for the custom field.|

##### Return Value

void

## <a name="seeAlso"></a>See Also

[DraftAssignment](DraftAssignment.md)<br/>
[DraftProjectResourceCollection](DraftProjectResourceCollection.md)<br/>
[ProjectResourceCreationInformation](ProjectResourceCreationInformation.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
