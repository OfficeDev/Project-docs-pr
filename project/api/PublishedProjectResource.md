[comment]: # (Name:PublishedProjectResource)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>PublishedProjectResource class

inherits members from [ProjectResource](ProjectResource.md)<br/>

<a name="description"></a>Represents an enterprise resource that is published on Project Server.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class PublishedProjectResource 
```
### JSOM

```JavaScript
PS.PublishedProjectResource
```

### REST Interface

This resource supports GET HTTP commands.

```
PS.PublishedProjectResource

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/ProjectResources('{resourceid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the published project resource.|
|<a name="Assignments"></a>Assignments|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignmentCollection](PublishedAssignmentCollection.md)|Gets the assignments that are associated with the resource.|
|<a name="CanLevel"></a>CanLevel|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether resource leveling can be performed on the resource.|
|<a name="Code"></a>Code|&#x2713;|&#x2713;|&#x2713;|String|Gets any code, abbreviation, or number that is entered as part of the information about the resource.|
|<a name="CostAccrual"></a>CostAccrual|&#x2713;|&#x2713;|&#x2713;|[AccrueAt](AccrueAt.md)|Gets a value that represents how and when to charge resource costs to the cost of a task.|
|<a name="CostCenter"></a>CostCenter|&#x2713;|&#x2713;|&#x2713;|String|Gets any code, abbreviation, or number that has been entered as part of the information about the resource.|
|<a name="CostPerUse"></a>CostPerUse|&#x2713;|&#x2713;|&#x2713;|Double|Gets the cost per use of the resource.|
|<a name="DefaultAssignmentOwner"></a>DefaultAssignmentOwner|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the default assignment owner.|
|<a name="DefaultBookingType"></a>DefaultBookingType|&#x2713;|&#x2713;|&#x2713;|[BookingType](BookingType.md)|Gets the default booking type for the resource.|
|<a name="Email"></a>Email|&#x2713;|&#x2713;|&#x2713;|String|Gets the email address of the resource.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the published project resource.|
|<a name="Group"></a>Group|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of a group to which a resource belongs.|
|<a name="Initials"></a>Initials|&#x2713;|&#x2713;|&#x2713;|String|Gets the short name for the resource.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the published project resource.|
|<a name="MaterialLabel"></a>MaterialLabel|&#x2713;|&#x2713;|&#x2713;|String|Gets the unit of measure for a material resource, which can be supplies or other consumable items that are used in a project.|
|<a name="MaximumCapacity"></a>MaximumCapacity|&#x2713;|&#x2713;|&#x2713;|Double|Gets the percentage, or the number of units, that represent the maximum capacity for which the resource is available during the current time period.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the project resource.|
|<a name="OvertimeRate"></a>OvertimeRate|&#x2713;|&#x2713;|&#x2713;|Double|Gets the hourly rate of pay for overtime for the resource.|
|<a name="OvertimeRateUnits"></a>OvertimeRateUnits|&#x2713;|&#x2713;|&#x2713;|[OvertimeRateFormat](OvertimeRateFormat.md)|Gets the rate description format in which the overtime rate is displayed.|
|<a name="Phonetics"></a>Phonetics|&#x2713;|&#x2713;|&#x2713;|String|Gets phonetic information in either the Japanese Hiragana writing system or the Katakana writing system for resource names.|
|<a name="StandardRate"></a>StandardRate|&#x2713;|&#x2713;|&#x2713;|Double|Gets the rate of pay per hour for regular, non-overtime work performed by the resource.|
|<a name="StandardRateUnits"></a>StandardRateUnits|&#x2713;|&#x2713;|&#x2713;|[StandardRateFormat](StandardRateFormat.md)|Gets the rate description format in which the standard rate is displayed.|

## <a name="seeAlso"></a>See Also

[PublishedAssignment](PublishedAssignment.md)<br/>
[PublishedProjectResourceCollection](PublishedProjectResourceCollection.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
