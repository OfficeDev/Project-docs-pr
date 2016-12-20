# DraftProject 
Represents the draft version of a project that is either new, or a published project that is checked out for editing.

DraftProject inherits properties and methods from the [Project](Project.md) class.

## Syntax

### CSOM

```
Class DraftProject
```

### JSOM

```
PS.DraftProject
```

### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands:

```
http://<sitecollection> /<site> /_api/ProjectServer/Projects('projectid')/Draft
```

## Remarks

The **[DraftProject](DraftProject.md)** class and the **[PublishedProject](PublishedProject.md)** class derive from the **[Project](Project.md)** class. 

To set the value of properties in an existing project:

1. Use the **[PublishedProject](PublishedProject.md) CheckOut** method.
2. Edit the **[DraftProject](DraftProject.md)** object.
3. Check in the edited project using the **DraftProject [CheckIn](#checkin)** method.

## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Assignments|&#x2713;|&#x2713;|&#x2713;|[DraftAssignmentCollection](DraftAssignmentCollection.md)|Gets the collection of assignments in the project.|
|Calendar|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[Calendar](Calendar.md)|Gets or sets the project calendar. |
|CurrencyCode|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the currency code of the project, as defined in ISO 4217. |
|CurrencyDigits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the number of decimal digits in currency values. |
|CurrencyPosition|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CurrencySymbolPosition](CurrencySymbolPosition.md)|Gets or sets the placement of the currency symbol in relation to the currency value. |
|CurrencySymbol|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the currency symbol that represents the type of currency that is used in the project. |
|CurrentDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the current date for the project. |
|DaysPerMonth|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the default number of working days per month. |
|DefaultEffortDriven|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the scheduling of new tasks is effort-driven. |
|DefaultEstimatedDuration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether new tasks have estimated durations. |
|DefaultFixedCostAccrual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[FixedCostAccrual](FixedCostAccrual.md)|Gets or sets a value that indicates which default fixed-cost accrual method to use on new tasks. |
|DefaultOvertimeRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the default overtime rate for local resources. |
|DefaultStandardRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the default standard rate for local resources. |
|DefaultTaskType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TaskType](TaskType.md)|Gets or sets the default type for tasks in the project. |
|DefaultWorkFormat|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[WorkFormat](WorkFormat.md)|Gets or sets the default format for work duration. |
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the project description. |
|FieldValues|&#x2713;|&#x2713;|&#x2713;|Dictionary&lt;string, Object&gt;|Gets the custom field values for the [DraftProject](DraftProject.md). |
|FinishDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the project finish date. |
|FiscalYearStartMonth|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the number of the first month in the fiscal year. |
|IncludeCustomFields|&#x2713;|&#x2713;|&#x2713;|[DraftProject](DraftProject.md)|Gets a [DraftProject](DraftProject.md) object that includes custom fields. |
|Item|&#x2713;&#x02B7;|&#x2713;&#x02B7;||Object|Gets or sets an item in the project. |
|MinutesPerDay|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the default number of minutes per day. |
|MinutesPerWeek|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the default number of minutes per week. |
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the project. |
|NewTasksAreManual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether new tasks are manually scheduled. |
|NumberFiscalYearFromStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether to use the project start year for fiscal year numbering. |
|Owner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets or sets the owner of the project. |
|ProjectIdentifier|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the Project Id, represented as a string.|
|ProjectResources|&#x2713;|&#x2713;|&#x2713;|[DraftProjectResourceCollection](DraftProjectResourceCollection.md)|Gets the collection of resources for a project. |
|ProtectedActualsSynch|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets whether the project actuals are synchronized with the protected actuals. |
|ShowEstimatedDurations|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a question mark is displayed after an estimated duration for a task. |
|StartDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the project start date. |
|StatusDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the status date for the project. |
|TaskLinks|&#x2713;|&#x2713;|&#x2713;|[DraftTaskLinkCollection](DraftTaskLinkCollection.md)|Gets the collection of task links for the project. |
|Tasks|&#x2713;|&#x2713;|&#x2713;|[DraftTaskCollection](DraftTaskCollection.md)|Gets the collection of tasks for the project. |
|TrackingMode|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TrackingMode](TrackingMode.md)|Gets or sets the default tracking method for all assignments in the project. |
|UtilizationDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time of resource utilization for the current project.|
|UtilizationType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[UtilizationType](UtilizationType.md)|Gets or sets the derivation source(s) of the summary resource assignments of a project.|
|WeekStartDay|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the day of the week on which a work week starts. |
|WinprojVersion|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal|Gets or sets the version of Project Professional that created the published project. |


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[ChangeEnterpriseProjectType(Guid enterpriseProjectTypeUid)](#changeenterpriseprojecttype)|||&#x2713;|void|Changes or sets an [EnterpriseProjectType](EnterpriseProjectType.md) associated with a project.|
|[CheckIn(Boolean force)](#checkin)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Queues a check-in job for a draft project if it is still checked out.|
|[Publish(Boolean checkIn)](#publish)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Queues a publish job to get the changes from the draft project back to the published version.|
|[Update()](#update)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Saves changes in a new project or checked-out draft project back to Project Server.|
|[UpdateCustomFields(CustomFieldCollection customfielddictionary)](#updatecustomfields)|||&#x2713;|[QueueJob](QueueJob.md)|Updates the custom fields for a project in bulk.|
|[Validate()](#validate)|&#x2713;|&#x2713;|&#x2713;|void|Validates pending changes from all added or removed projects.|


## Method Details

### <a name="changeenterpriseprojecttype"></a> ChangeEnterpriseProjectType(Guid enterpriseProjectTypeUid )

Changes or sets an [EnterpriseProjectType](EnterpriseProjectType.md) associated with a project.

#### Syntax

```
ChangeEnterpriseProjectType(Guid enterpriseProjectTypeUid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|enterpriseProjectTypeUid| Guid|Id of the new [EnterpriseProjectType](EnterpriseProjectType.md).

#### Return value

void

### <a name="checkin"></a> CheckIn(Boolean force)

Queues a check-in job for a draft project if it is still checked out.

#### Syntax

```
QueueJob CheckIn(Boolean force)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|force | Boolean | True if the administrator or project owner forces check in of a project; otherwise, False.

#### Return value

[QueueJob](QueueJob.md) <br />
A queued job that will check in the draft version of the project.

### <a name="publish"></a> Publish(Boolean checkIn)

Queues a publish job to get the changes from the draft project back to the published version.

#### Syntax

```
Publish(Boolean checkIn)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|checkIn | Boolean | If True, check in the project after it is published; otherwise, False.

#### Return value

[QueueJob](QueueJob.md) <br />
A [QueueJob](QueueJob.md) object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service publishes the draft version of the project.

### <a name="update"></a> Update()

Saves changes in a new project or checked-out draft project back to Project Server.

#### Syntax

```
Update()
```

#### Parameters

none

#### Return value

[QueueJob](QueueJob.md) <br />
A [QueueJob](QueueJob.md) object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service saves the new or draft version of the project.

#### Remarks

The Update method cannot process a CSOM request greater than 2 MB in size.

### <a name="updatecustomfields"></a> UpdateCustomFields(CustomFieldCollection customfielddictionary)

Updates the custom fields for a project in bulk.

#### Syntax

```
UpdateCustomFields(CustomFieldCollection customfielddictionary)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|customfielddictionary| [CustomFieldCollection](CustomFieldCollection.md) | Collection of project custom fields that have values set for the project. 

#### Return Value

[QueueJob](QueueJob.md)<br />
A [QueueJob](QueueJob.md) object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service saves the new or draft version of the project.


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

