[comment]: # (Name:EnterpriseResource)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>EnterpriseResource class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a resource that is managed by Project Service in a project.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class EnterpriseResource 
```
### JSOM

```JavaScript
PS.EnterpriseResource
```

### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.EnterpriseResource

http://<sitecollection>/<site>/api/ProjectServer/EnterpriseResources('{resourceid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the enterprise resource.|
|<a name="Assignments"></a>Assignments|&#x2713;|&#x2713;|&#x2713;|[StatusAssignmentCollection](StatusAssignmentCollection.md)|Gets a collection of status assignments for an enterprise resource.|
|<a name="BaseCalendar"></a>BaseCalendar|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[Calendar](Calendar.md)|Gets or sets a base calendar for an enterprise resource.|
|<a name="CanLevel"></a>CanLevel|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether resource leveling can be performed on an enterprise resource.|
|<a name="Code"></a>Code|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets any code, abbreviation, or number that is entered as part of the information about an enterprise resource.|
|<a name="CostAccrual"></a>CostAccrual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[AccrueAt](AccrueAt.md)|Gets or sets a value that represents how and when to charge enterprise resource costs to the cost of a task.|
|<a name="CostCenter"></a>CostCenter|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets any code, abbreviation, or number that is entered as cost center information for an enterprise resource.|
|<a name="Created"></a>Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when an enterprise resource was added to the project.|
|<a name="CustomFields"></a>CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets a collection of custom fields that have values set for an enterprise resource.|
|<a name="DefaultAssignmentOwner"></a>DefaultAssignmentOwner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the default name that is entered into the Assignment Owner field when an enterprise resource is assigned to a task.|
|<a name="DefaultBookingType"></a>DefaultBookingType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[BookingType](BookingType.md)|Gets or sets the default booking type for an enterprise resource.|
|<a name="Email"></a>Email|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the email address of an enterprise resource.|
|<a name="Engagements"></a>Engagements|&#x2713;|&#x2713;|&#x2713;|[ResourceEngagementCollection](ResourceEngagementCollection.md)||
|<a name="ExternalId"></a>ExternalId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets any code, abbreviation, or number that is entered as an external identifier for an enterprise resource.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the enterprise resource.|
|<a name="Group"></a>Group|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of a group to which an enterprise resource belongs.|
|<a name="HireDate"></a>HireDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time of hire for an enterprise resource.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the object identifier as a GUID.|
|<a name="Initials"></a>Initials|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the abbreviation for the name of an enterprise resource.|
|<a name="IsActive"></a>IsActive|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether an enterprise resource has been made active or inactive.|
|<a name="IsBudget"></a>IsBudget|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a Boolean value that indicates whether an enterprise resource is a budget resource.|
|<a name="IsCheckedOut"></a>IsCheckedOut|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether enterprise resource assignment data is currently available for updating or modification, or whether the enterprise resource is checked out.|
|<a name="IsGeneric"></a>IsGeneric|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a Boolean value that indicates whether an enterprise resource is generic.|
|<a name="IsTeam"></a>IsTeam|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a Boolean value that indicates whether a resource is in a team assignment pool.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the enterprise resource.|
|<a name="MaterialLabel"></a>MaterialLabel|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the unit of measure that is entered for supplies or other consumable items that are used to complete tasks in a project.|
|<a name="Modified"></a>Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the modified date and time.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of an enterprise resource.|
|<a name="Phonetics"></a>Phonetics|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets phonetic information for resource names in either the Japanese Hiragana writing system or the Katakana writing system.|
|<a name="RequiresEngagements"></a>RequiresEngagements|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean||
|<a name="ResourceCalendarExceptions"></a>ResourceCalendarExceptions|&#x2713;|&#x2713;|&#x2713;|[CalendarExceptionCollection](CalendarExceptionCollection.md)|Gets a collection of exceptions to the base calendar that are specific to an enterprise resource.|
|<a name="ResourceType"></a>ResourceType|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResourceType](EnterpriseResourceType.md)|Gets an enumerated value that represents the type of an enterprise resource.|
|<a name="Self"></a>Self|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets the currently logged-on user.|
|<a name="TerminationDate"></a>TerminationDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time after which the resource can no longer be used.|
|<a name="TimesheetManager"></a>TimesheetManager|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the manager who reviews and approves the timesheet of an enterprise resource.|
|<a name="User"></a>User|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the SharePoint user that is linked to the Enterprise Resource.|
|<a name="UserPermissions"></a>UserPermissions|||&#x2713;|[UserPermissionCollection](UserPermissionCollection.md)|Gets a UserPermissionCollection that represents the users and their permissions for the enterprise resource.|

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the enterprise resource object.|
|[ForceCheckIn()](#ForceCheckIn__)|&#x2713;|&#x2713;|&#x2713;|void|Forces a project to be checked in after it is left in a state of being checked out following the interruption or unexpected closing of Project Server.|
|[getSelf(ClientRuntimeContext context)](#getself)|&#x2713;|&#x2713;| |[EnterpriseResource](EnterpriseResource.md)|Gets the currently logged-on user.|
|[SetCustomFieldValue(String fieldName, Object value)](#SetCustomFieldValue_String_fieldName,_Object_value_)|&#x2713;|&#x2713;||void|Sets a custom field on the enterprise resource.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()

Deletes the enterprise resource object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

#### <a name="ForceCheckIn__"></a>ForceCheckIn()

Forces a project to be checked in after it is left in a state of being checked out following the interruption or unexpected closing of Project Server.

##### Syntax

```
void ForceCheckIn()
```

##### Parameters

None

##### Return Value

void

### <a name="getself"></a>GetSelf(ClientRuntimeContext context)

Gets the currently logged-on user.

#### Syntax

```
GetSelf(ClientRuntimeContext context)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|context|ClientRuntimeContext|The current client runtime context, example [ProjectContext](ProjectContext.md).


#### Return Value

[EnterpriseResource](EnterpriseResource.md)<br />
The [EnterpriseResource](EnterpriseResource.md) who is currently logged on.


#### <a name="SetCustomFieldValue_String_fieldName,_Object_value_"></a>SetCustomFieldValue(String fieldName, Object value)

Sets a custom field on the enterprise resource.

##### Syntax

```
void SetCustomFieldValue(String fieldName, Object value)
```

##### Parameters
|**Name**|**Type**|**Description**|
|:------ |:----|:------ |
|fieldName|String|The [InternalName](CustomField.md#InternalName) of the custom field to update.|
|value|Object|New value of the custom field.|

##### Return Value

void


## Remarks

Enterprise resources are usually part of an organization's entire list of resources and can be shared across projects.

## <a name="seeAlso"></a>See Also

[DraftProjectResourceCollection](DraftProjectResourceCollection.md)<br/>
[Engagement](Engagement.md)<br/>
[EnterpriseResourceCollection](EnterpriseResourceCollection.md)<br/>
[EnterpriseResourceCreationInformation](EnterpriseResourceCreationInformation.md)<br/>
[PlanAssignment](PlanAssignment.md)<br/>
[ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md)<br/>
[ProjectResource](ProjectResource.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
[StatusAssignment](StatusAssignment.md)<br/>

