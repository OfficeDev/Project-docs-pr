[comment]: # (Name:PlanAssignment)
[comment]: # (Name:Microsoft.ProjectServer.PlanAssignment)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PlanAssignment class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Provides information about an assignment in a project plan.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PlanAssignment 
```
### JSOM

```javascript
PS.PlanAssignment
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.PlanAssignment

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')/Assignments('{assignmentid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the plan assignment.|
|<a name="BookingType"></a>BookingType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[BookingType](BookingType.md)|Gets or sets the booking type for a plan assignment.|
|<a name="CanLevel"></a>CanLevel|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether resource leveling can be performed on a plan assignment resource.|
|<a name="Code"></a>Code|&#x2713;|&#x2713;|&#x2713;|String|Gets any code, abbreviation, or number that is entered as custom information for a plan assignment.|
|<a name="CostCenter"></a>CostCenter|&#x2713;|&#x2713;|&#x2713;|String|Gets any code, abbreviation, or number that is entered as custom cost center information for a plan assignment.|
|<a name="CustomFields"></a>CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets the collection of custom fields that have values set for a plan assignment.|
|<a name="Email"></a>Email|&#x2713;|&#x2713;|&#x2713;|String|Gets the email address of the resource for a plan assignment.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the plan assignment.|
|<a name="Group"></a>Group|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of a group to which a plan assignment resource belongs.|
|<a name="HireDate"></a>HireDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time that a plan assignment resource was hired.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of a plan assignment.|
|<a name="Intervals"></a>Intervals|&#x2713;|&#x2713;|&#x2713;|[PlanAssignmentIntervalCollection](PlanAssignmentIntervalCollection.md)|Gets the collection of plan assignment time intervals.|
|<a name="IsTeam"></a>IsTeam|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether a plan assignment resource is in a team assignment pool.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the plan assignment.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the full name of a plan assignment resource.|
|<a name="Phonetics"></a>Phonetics|&#x2713;|&#x2713;|&#x2713;|String|Gets phonetic information for resource names, in either the Japanese Hiragana writing system or the Katakana writing system.|
|<a name="Resource"></a>Resource|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets a resource that is part of an organization's entire list of resources and that can be shared across projects.|
|<a name="ResourceType"></a>ResourceType|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResourceType](EnterpriseResourceType.md)|Gets the type of a plan assignment resource.|
|<a name="TerminationDate"></a>TerminationDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time after which a plan assignment resource can no longer be used.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the plan assignment object.|
|[SetCustomFieldValue(String fieldName, Object value)](#SetCustomFieldValue_String_fieldName,_Object_value_)|&#x2713;|&#x2713;||void|Sets a custom field on the plan assignment.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the plan assignment object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

#### <a name="SetCustomFieldValue_String_fieldName,_Object_value_"></a>SetCustomFieldValue(String fieldName, Object value)
 
Sets a custom field on the plan assignment.

##### Syntax

```
void SetCustomFieldValue(String fieldName, Object value)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|fieldName|String|The [InternalName](CustomField.md#InternalName) of the custom field to update.|
|value|Object|New value of the custom field.|

##### Return Value

void

## <a name="seeAlso"></a>See Also

[PlanAssignmentCollection](PlanAssignmentCollection.md)<br/>
[PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md)<br/>
