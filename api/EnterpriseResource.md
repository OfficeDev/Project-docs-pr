# EnterpriseResource 

Represents a resource that is managed by Project Server in a project.

## Syntax

### CSOM

```C#
Class EnterpriseResource 
```

### JSOM

```
PS.EnterpriseResource
```

### REST Interface

This resource supports GET and DELETE HTTP commands:

```
http://<sitecollection> /<site> /_api/ProjectServer/EnterpriseResources('enterpriseresourceid')
```

## Remarks

Enterprise resources are part of an organization’s entire list of resources and can be shared across projects.

## Members

### Properties

<!-- The following table has left-aligned columns 1,5,6; and center-aligned columns 2,3,4. -->

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Assignments|&#x2713;|&#x2713;|&#x2713;|StatusAssignmentCollection|Gets a collection of status assignments for an enterprise resource. <br />Status assignment data reports on the status of assignments.|
|BaseCalendar|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Calendar|Gets or sets a base calendar for an enterprise resource.|
|CanLevel|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether resource leveling can be performed on an enterprise resource. <br />True if resource leveling can be performed on the resource; otherwise,False.|
|Code|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets any code, abbreviation, or number that is entered as part of the information about an enterprise resource.|
|CostAccrual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|AccrueAt (int32-std for enums)|Gets or sets a value that represents how and when to charge enterprise resource costs to the cost of a task.|
|CostCenter|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets any code, abbreviation, or number that is entered as cost center information for an enterprise resource.|
|Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when an enterprise resource was added to the project.|
|CustomFields|&#x2713;|&#x2713;|&#x2713;|CustomFieldCollection|Gets a collection of custom fields that have values set for an enterprise resource.|
|DefaultAssignmentOwner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|User(SP)|Gets the default name that is entered into the Assignment Owner field when an enterprise resource is assigned to a task.|
|DefaultBookingType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|BookingType  (int32-std for enums)|Gets or sets the default booking type for an enterprise resource.|
|Email|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the email address of an enterprise resource.|
|Engagements|&#x2713;|&#x2713;|&#x2713;|ResourceEngagementCollection||
|ExternalId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets any code, abbreviation, or number that is entered as an external identifier for an enterprise resource.|
|FieldValues|&#x2713;|&#x2713;||Dictionary<string,object>|Gets the collection of custom fields that have values set for an enterprise resource.|
|Group|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of a group to which an enterprise resource belongs.|
|HireDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time of hire for an enterprise resource.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the object identifier as a GUID.|
|Initials|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the abbreviation for the name of an enterprise resource.|
|IsActive|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether an enterprise resource has been made active or inactive.|
|IsBudget|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a Boolean value that indicates whether an enterprise resource is a budget resource.|
|IsCheckedOut|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether enterprise resource assignment data is currently available for updating or modification, or whether the enterprise resource is checked out.|
|IsGeneric|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a Boolean value that indicates whether an enterprise resource is generic.|
|IsTeam|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a Boolean value that indicates whether a resource is in a team assignment pool.|
|Item|&#x2713;&#x02B7;|&#x2713;&#x02B7;||Object|Gets or sets an enterprise resource in a project.|
|MaterialLabel|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the unit of measure that is entered for supplies or other consumable items that are used to complete tasks in a project.|
|Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the modified date and time.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of an enterprise resource.|
|Phonetics|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets phonetic information for resource names in either the Japanese Hiragana writing system or the Katakana writing system.|
|RequiresEngagements|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean||
|ResourceCalendarExceptions|&#x2713;|&#x2713;|&#x2713;|CalendarExceptionCollection |Gets a collection of exceptions to the base calendar that are specific to an enterprise resource.|
|ResourceType|&#x2713;|&#x2713;|&#x2713;|EnterpriseResourceType |Gets an enumerated value that represents the type of an enterprise resource.|
|Self|||&#x2713;|EnterpriseResource||
|TerminationDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time after which the resource can no longer be used.|
|TimesheetManager|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|User(SP)|Gets the manager who reviews and approves the timesheet of an enterprise resource.|
|User|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|User(SP)|Gets the SharePoint user that is linked to the Enterprise Resource.|
|UserPermissions|||&#x2713;|UserPermissions||



### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#deleteobject)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the EnterpriseResource object.|
|[ForceCheckin()](#forcecheckin)|&#x2713;|&#x2713;|&#x2713;|void|Forces a project to be checked in after it is left in a state of being checked out following the interruption or unexpected closing of Project Server.|
|[getSelf(context)](#getself)|&#x2713;|&#x2713;| |EnterpriseResource|Gets the currently logged-on user.|


## Method Details

### <a name="deleteobject"></a> DeleteObject()

Deletes the EnterpriseResource object.

#### Syntax

```
DeleteObject()
```

#### Parameters

none

#### Return Value

void

### <a name="forcecheckin"></a> ForceCheckIn()

Forces a project to be checked in after it is left in a state of being checked out following the interruption or unexpected closing of Project Server.

#### Syntax

```
ForceCheckIn()
```

#### Parameters

none

#### Return Value

void

### <a name="getself"></a>GetSelf(context ClientRuntimeContext)

Gets the currently logged-on user.

#### Syntax

```
GetSelf(context ClientRuntimeContext)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|context|ClientRuntimeContext|A ClientRuntimeContext.

#### Return Value

EnterpriseResource<br />
The EnterpriseResource who is currently logged on.


