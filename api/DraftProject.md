# DraftProject 
Represents the draft version of a project that is either new or a published project that is checked out for editing.

DraftProject inherits properties and methods from the Project class.

## Syntax

### CSOM

```C#
Class DraftProject
```

### JSOM

```
PS.DraftProject
```

### REST Interface

This resource supports MERGE and PUT HTTP commands:

```
http://<sitecollection> /<site> /_api/ProjectServer/Projects('projectid')/Draft
```

## Remarks

The **DraftProject** class and the **PublishedProject** class derive from the **Project** class. 

To set the value of properties in an existing project:

1. Use the **PublishedProject CheckOut** method.
2. Edit the **DraftProject** object.
3. Check in the edited project using the **DraftProject CheckIn** method.

## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Assignments|&#x2713;|&#x2713;|&#x2713;|PublishedAssignmentCollection|Gets the collection of assignments in the project.|
|Calendar|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Calendar|Gets the project calendar. |
|CurrencyCode|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the currency code of the project, as defined in ISO 4217. |
|CurrencyDigits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets the number of decimal digits in currency values. |
|CurrencyPosition|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Enumerated value|Gets the placement of the currency symbol in relation to the currency value. |
|CurrencySymbol|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the currency symbol that represents the type of currency that is used in the project. |
|CurrentDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets the current date for the project. |
|DaysPerMonth|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|short integer|Gets the default number of working days per month. |
|DefaultEffortDriven|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets a value that indicates whether the scheduling of new tasks is effort-driven. |
|DefaultEstimatedDuration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets a value that indicates whether new tasks have estimated durations. |
|DefaultFixedCostAccrual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Enumerated value|Gets a value that indicates which default fixed-cost accrual method to use on new tasks. |
|DefaultOvertimeRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets the default overtime rate for local resources. |
|DefaultStandardRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets the default standard rate for local resources. |
|DefaultTaskType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Enumerated value|Gets the default type for tasks in the project. |
|DefaultWorkFormat|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Enumerated value|Gets the default format for work duration. |
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the project description. |
|FieldValues|&#x2713;|&#x2713;|&#x2713;|Dictionary/JSON list of key-value pairs|Gets the custom field values for the published project. |
|FinishDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets the project finish date. |
|FiscalYearStartMonth|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|short integer|Gets the number of the first month in the fiscal year. |
|IncludeCustomFields|&#x2713;|&#x2713;|&#x2713;|PublishedProject|Gets a PublishedProject object that includes custom fields. |
|Item|&#x2713;&#x02B7;|&#x2713;&#x02B7;||Object|Gets or sets an item in the project. |
|MinutesPerDay|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets the default number of minutes per day. |
|MinutesPerWeek|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets the default number of minutes per week. |
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the name of the project. |
|NewTasksAreManual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets a value that indicates whether new tasks are manually scheduled. |
|NumberFiscalYearFromStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets a value that indicates whether to use the project start year for fiscal year numbering. |
|Owner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|User|Gets the owner of the project. |
|ProjectIdentifier|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|ProjectResources|&#x2713;|&#x2713;|&#x2713;|PublishedProjectResourceCollection|Gets the collection of resources for a project. |
|ProtectedActualsSynch|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets whether the project actuals are synchronized with the protected actuals. |
|ShowEstimatedDurations|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets a value that indicates whether a question mark is displayed after an estimated duration for a task. |
|StartDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets the project start date. |
|StatusDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets the status date for the project. |
|TaskLinks|&#x2713;|&#x2713;|&#x2713;|PublishedTaskLinkCollection|Gets the collection of task links for the project. |
|Tasks|&#x2713;|&#x2713;|&#x2713;|PublishedTaskCollection|Gets the collection of tasks for the project. |
|TrackingMode|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Enumerated value |Gets the default tracking method for all assignments in the project. |
|UtilizationDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|UtilizationType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets the derivation source(s) of the summary resource assignments of a project. Uses the UtilizationType enumeration.|
|WeekStartDay|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Short integer|Gets the day of the week on which a work week starts. |
|WinprojVersion|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal|Gets the version of Project Professional that created the published project. |


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[ChangeEnterpriseProjectType(enterpriseProjectTypeUid: Guid)](#changeenterpriseprojecttype)|||&#x2713;|void||
|[CheckIn(force: Boolean)](#checkin)|&#x2713;|&#x2713;|&#x2713;|QueueJob|Queues a check-in job for a draft project if it is still checked out.|
|[Publish(checkIn: Boolean)](#publish)|&#x2713;|&#x2713;|&#x2713;|QueueJob|Queues a publish job to get the changes from the draft project back to the published version.|
|[Update()](#update)|&#x2713;|&#x2713;|&#x2713;|QueueJob|Saves changes in a new project or checked-out draft project back to Project Server.|
|[UpdateCustomFields(customfielddictionary: CustomFieldCollection)](#updatecustomfields)|||&#x2713;|QueueJob||
|[Validate()](#validate)|&#x2713;|&#x2713;|&#x2713;|void|Validates pending changes from all added or removed projects.|


## Method Details

### <a name="changeenterpriseprojecttype"></a> ChangeEnterpriseProjectType(enterpriseProjectTypeUid: Guid)

<!-- Need a description here -->

#### Syntax

```
ChangeEnterpriseProjectType(enterpriseProjectTypeUid: Guid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|enterpriseProjectTypeUid| Guid|Id of the new enterprise project type.

#### Return value

void

### <a name="checkin"></a> CheckIn(force: Boolean)

Queues a check-in job for a draft project if it is still checked out.

#### Syntax

```
QueueJob CheckIn(force: Boolean)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|force | Boolean | True if the administrator or project owner forces check in of a project; otherwise, False.

#### Return value

QueueJob <br />
A queued job that will check in the draft version of the project.

### <a name="publish"></a> Publish(checkIn: Boolean)

Queues a publish job to get the changes from the draft project back to the published version.

#### Syntax

```
Publish(checkIn: Boolean)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|checkIn | Boolean | If True, check in the project should after it is published; otherwise, False.

#### Return value

QueueJob <br />
A QueueJob object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service publishes the draft version of the project.

### <a name="update"></a> Update()

Saves changes in a new project or checked-out draft project back to Project Server.

#### Syntax

```
Update()
```

#### Parameters

none

#### Return value

QueueJob <br />
A QueueJob object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service saves the new or draft version of the project.

#### Remarks

The Update method cannot process a CSOM request greater than 2 MB in size.

### <a name="updatecustomfields"></a> UpdateCustomFields(customfielddictionary: CustomFieldCollection)

Updates the custom fields associated with the project.

#### Syntax

```
UpdateCustomFields(customfielddictionary: CustomFieldCollection)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|customfielddictionary| CustomFieldCollection | Collection of project custom fields that have values set for the project. 

#### Return Value

QueueJob<br />
A QueueJob object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service saves the new or draft version of the project.


### <a name="validate"></a> Validate()
 
Validates pending changes from all added or removed projects.

#### Syntax

```
Validate()
```

#### Parameters

none
 
#### Return Value

void


## See Also

[Project class](Project.md) <br />
[PublishedProject class](PublishedProject.md)

