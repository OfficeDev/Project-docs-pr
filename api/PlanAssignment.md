[comment]: # (Name:PlanAssignment)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# PlanAssignment

Provides information about an assignment in a project plan.



## Syntax

### CSOM

```C#
Class PlanAssignment 
```
### JSOM

```
PS.PlanAssignment
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')/Assignments('{assignmentid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|BookingType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[BookingType](BookingType.md)|Gets or sets the booking type for a plan assignment.|
|CanLevel|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether resource leveling can be performed on a plan assignment resource.|
|Code|&#x2713;|&#x2713;|&#x2713;|String|Gets any code, abbreviation, or number that is entered as custom information for a plan assignment.|
|CostCenter|&#x2713;|&#x2713;|&#x2713;|String|Gets any code, abbreviation, or number that is entered as custom cost center information for a plan assignment.|
|CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets the collection of custom fields that have values set for a plan assignment.|
|Email|&#x2713;|&#x2713;|&#x2713;|String|Gets the email address of the resource for a plan assignment.|
|FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for a plan assignment.|
|Group|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of a group to which a plan assignment resource belongs.|
|HireDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time that a plan assignment resource was hired.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of a plan assignment.|
|Intervals|&#x2713;|&#x2713;|&#x2713;|[PlanAssignmentIntervalCollection](PlanAssignmentIntervalCollection.md)|Gets the collection of plan assignment time intervals.|
|IsTeam|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether a plan assignment resource is in a team assignment pool.|
|Item|&#x2713;&#x02B7;|&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in a plan assignment.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the full name of a plan assignment resource.|
|Phonetics|&#x2713;|&#x2713;|&#x2713;|String|Gets phonetic information for resource names, in either the Japanese Hiragana writing system or the Katakana writing system.|
|Resource|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets a resource that is part of an organization's entire list of resources and that can be shared across projects.|
|ResourceType|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResourceType](EnterpriseResourceType.md)|Gets the type of a plan assignment resource.|
|TerminationDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time after which a plan assignment resource can no longer be used.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the PlanAssignment object.|
|[SetCustomFieldValue(String fieldName, Object value)](#SetCustomFieldValue_String_fieldName,_Object_value_)|&#x2713;|&#x2713;||void||



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the PlanAssignment object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void

### <a id="SetCustomFieldValue_String_fieldName,_Object_value_"></a>SetCustomFieldValue(String fieldName, Object value)
 


#### Syntax

```
void SetCustomFieldValue(String fieldName, Object value)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|fieldName| String | 
|value| Object | 


#### Return Value

void


## See Also
