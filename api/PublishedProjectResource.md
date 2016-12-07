# PublishedProjectResource

Represents an enterprise resource that is published on Project Server.

PublishedProjectResource inherits properties from the ProjectResource class.

## Syntax

### CSOM

```C#
PublishedProjectResource 
```

### JSOM

```
PS.PublishedProjectResource
```

### REST Interface

This resource supports the POST HTTP command.

```
http://<sitecollection> /<site> /_api/ProjectServer/PublicProjectResources('projectresourceid')
```

## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Assignments|&#x2713;|&#x2713;|&#x2713;|PublishedAssignmentCollection|Gets the assignments that are associated with the resource.|
|CanLevel|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether resource leveling can be performed on the resource.|
|Code|&#x2713;|&#x2713;|&#x2713;|String|Gets any code, abbreviation, or number that is entered as part of the information about the resource.|
|CostAccrual|&#x2713;|&#x2713;|&#x2713;|AccrueAt|Gets a value that represents how and when to charge resource costs to the cost of a task.|
|CostCenter|&#x2713;|&#x2713;|&#x2713;|String|Gets any code, abbreviation, or number that has been entered as part of the information about the resource.|
|CostPerUse|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the cost per use of the resource.|
|DefaultAssignmentOwner|&#x2713;|&#x2713;|&#x2713;|User (SP)|Gets the default assignment owner.|
|DefaultBookingType|&#x2713;|&#x2713;|&#x2713;|BookingType|Gets the default booking type for the resource.|
|Email|&#x2713;|&#x2713;|&#x2713;|String|Gets the email address of the resource.|
|FieldValues|&#x2713;|&#x2713;||Dictionary<String,Object>|Gets the collection of custom fields that have values set for the project resource.|
|Group|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of a group to which a resource belongs.|
|Initials|&#x2713;|&#x2713;|&#x2713;|String|Gets the short name for the resource.|
|Item|&#x2713;|&#x2713;||Object|Gets a resource item in the published project.|
|MaterialLabel|&#x2713;|&#x2713;|&#x2713;|String|Gets the unit of measure for a material resource, which can be supplies or other consumable items that are used in a project.|
|MaximumCapacity|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the percentage, or the number of units, that represent the maximum capacity for which the resource is available during the current time period.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the project resource.|
|OvertimeRate|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the hourly rate of pay for overtime for the resource.|
|OvertimeRateUnits|&#x2713;|&#x2713;|&#x2713;|OvertimeRateFormat|Gets the rate description format in which the overtime rate is displayed.|
|Phonetics|&#x2713;|&#x2713;|&#x2713;|String|Gets phonetic information in either the Japanese Hiragana writing system or the Katakana writing system for resource names.|
|StandardRate|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the rate of pay per hour for regular, non-overtime work performed by the resource.|
|StandardRateUnits|&#x2713;|&#x2713;|&#x2713;|StandardRateFormat|Gets the rate description format in which the standard rate is displayed.|


### Methods

The  **PublishedProjectResource** has no methods.

## See Also

[ProjectResource class](ProjectResource.md) <br />
[DraftProjectResource class](DraftProjectResource.md)

