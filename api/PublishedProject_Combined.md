# PublishedProject 
Represents a project that is published on Project Server.

PublishedProject inherits properties and methods from Project.

## Syntax

### CSOM

```C#
Public Class PublishedProject
```

### JSOM

```
PS.PublishedProject
```

### REST Interface

This resource supports GET and DELETE HTTP commands.

```
http://<sitecollection> /<site> /_api/ProjectServer/Projects('projectid')
```

## Remarks

To set the value of properties in an existing project:

1. Use the **PublishedProject CheckOut** method.
2. Edit the **DraftProject** object.
3. Check in the edited project using the **DraftProject CheckIn** method.

## Members

### Properties

|**Name**|**CSOM** |**JSOM** |**REST** |**Data Type**|**Description**|
|:-----|:-----: |:-----: |:-----: |:-----|:-----|
|Assignments|&#x2713; |&#x2713; |&#x2713; |PublishedAssignmentCollection|Gets the collection of assignments in the project.|
|Calendar|&#x2713; |&#x2713; |&#x2713; |Calendar|Gets the project calendar. |
|CurrencyCode|&#x2713; |&#x2713; |&#x2713; |String|Gets the currency code of the project, as defined in ISO 4217. |
|CurrencyDigits|&#x2713; |&#x2713; |&#x2713; |Integer|Gets the number of decimal digits in currency values. |
|CurrencyPosition|&#x2713; |&#x2713; |&#x2713; |Enumerated value|Gets the placement of the currency symbol in relation to the currency value. |
|CurrencySymbol|&#x2713; |&#x2713; |&#x2713; |String|Gets the currency symbol that represents the type of currency that is used in the project. |
|CurrentDate|&#x2713; |&#x2713; |&#x2713; |DateTime|Gets the current date for the project. |
|DaysPerMonth|&#x2713; |&#x2713; |&#x2713; |short integer|Gets the default number of working days per month. |
|DefaultEffortDriven|&#x2713; |&#x2713; |&#x2713; |Boolean|Gets a value that indicates whether the scheduling of new tasks is effort-driven. |
|DefaultEstimatedDuration|&#x2713; |&#x2713; |&#x2713; |Boolean|Gets a value that indicates whether new tasks have estimated durations. |
|DefaultFixedCostAccrual|&#x2713; |&#x2713; |&#x2713; |Enumerated value|Gets a value that indicates which default fixed-cost accrual method to use on new tasks. |
|DefaultOvertimeRate|&#x2713; |&#x2713; |&#x2713; |Double|Gets the default overtime rate for local resources. |
|DefaultStandardRate|&#x2713; |&#x2713; |&#x2713; |Double|Gets the default standard rate for local resources. |
|DefaultTaskType|&#x2713; |&#x2713; |&#x2713; |Enumerated value|Gets the default type for tasks in the project. |
|DefaultWorkFormat|&#x2713; |&#x2713; |&#x2713; |Enumerated value|Gets the default format for work duration. |
|Description|&#x2713; |&#x2713; |&#x2713; |String|Gets the project description. |
|Draft|&#x2713; |&#x2713; |&#x2713; |DraftProject|Gets a DraftProject object if it is not already checked out. |
|enterpriseProjectTypeId| | |&#x2713; |Guid||
|entityLinks| | |&#x2713; |EntityLinkCollection||
|FieldValues|&#x2713; |&#x2713; | |Dictionary/JSON list of key-value pairs|Gets the custom field values for the published project. |
|FinishDate|&#x2713; |&#x2713; |&#x2713; |DateTime|Gets the project finish date. |
|FiscalYearStartMonth|&#x2713; |&#x2713; |&#x2713; |short integer|Gets the number of the first month in the fiscal year. |
|IncludeCustomFields|&#x2713; |&#x2713; |&#x2713; |PublishedProject|Gets a PublishedProject object that includes custom fields. |
|IsEnterpriseProject|&#x2713; $|&#x2713; $|&#x2713; $|Boolean|Gets or sets a value that indicates whether the published project is an enterprise project (managed by Project Server). |
|Item|&#x2713; $|&#x2713; $| |Object|Gets or sets an item in the project. |
|MinutesPerDay|&#x2713; |&#x2713; |&#x2713; |Integer|Gets the default number of minutes per day. |
|MinutesPerWeek|&#x2713; |&#x2713; |&#x2713; |Integer|Gets the default number of minutes per week. |
|Name|&#x2713; |&#x2713; |&#x2713; |String|Gets the name of the project. |
|NewTasksAreManual|&#x2713; |&#x2713; |&#x2713; |Boolean|Gets a value that indicates whether new tasks are manually scheduled. |
|NumberFiscalYearFromStart|&#x2713; |&#x2713; |&#x2713; |Boolean|Gets a value that indicates whether to use the project start year for fiscal year numbering. |
|Owner|&#x2713; $|&#x2713; $|&#x2713; $|User|Gets the owner of the project. |
|ProjectIdentifier|&#x2713; &#x22C6;|&#x2713; &#x22C6;|&#x2713; &#x22C6;|Integer||
|ProjectResources|&#x2713; |&#x2713; |&#x2713; |PublishedProjectResourceCollection|Gets the collection of resources for a project. |
|ProtectedActualsSynch|&#x2713; |&#x2713; |&#x2713; |Boolean|Gets whether the project actuals are synchronized with the protected actuals. |
|ShowEstimatedDurations|&#x2713; |&#x2713; |&#x2713; |Boolean|Gets a value that indicates whether a question mark is displayed after an estimated duration for a task. |
|StartDate|&#x2713; |&#x2713; |&#x2713; |DateTime|Gets the project start date. |
|StatusDate|&#x2713; |&#x2713; |&#x2713; |DateTime|Gets the status date for the project. |
|TaskLinks|&#x2713; |&#x2713; |&#x2713; |PublishedTaskLinkCollection|Gets the collection of task links for the project. |
|Tasks|&#x2713; |&#x2713; |&#x2713; |PublishedTaskCollection|Gets the collection of tasks for the project. |
|TrackingMode|&#x2713; |&#x2713; |&#x2713; |Enumerated value |Gets the default tracking method for all assignments in the project. |
|UtilizationDate|&#x2713; &#x22C6;|&#x2713; &#x22C6;|&#x2713; &#x22C6;|DateTime| |
|UtilizationType|&#x2713; &#x22C6;|&#x2713; &#x22C6;|&#x2713; &#x22C6;|Integer| |
|WeekStartDay|&#x2713; |&#x2713; |&#x2713; |Short integer|Gets the day of the week on which a work week starts. |
|WinprojVersion|&#x2713; |&#x2713; |&#x2713; |Decimal|Gets the version of Project Professional that created the published project. |


### Methods

|**Name**|**CSOM** |**JSOM** |**REST** |**Return Type**|**Description**|
|:-----|:-----: |:-----: |:-----: |:-----|:-----|
|[CheckOut](#checkout)|&#x2713; |&#x2713; |&#x2713; |DraftProject|Checks out the draft version of the project.|
|[DeleteObject](#deleteobject)|&#x2713; |&#x2713; |&#x2713; |QueueJob|Deletes the PublishedProject object.|
|[SubmitToWorkflow](#submittoworkflow)|&#x2713; |&#x2713; |&#x2713; |void|Causes the workflow to run.|
|[UpdateVisibilityCustomFields](#updatevisibilitycustomfields)|&#x2713; |&#x2713; |&#x2713; |QueueJob|Updates the custom fields for a project in visibility mode.|

## Remarks

The **PublishedProject** class and the **DraftProject** class derive from the **Project** class. 

To set the value of properties in an published project:

1. Use the **PublishedProject CheckOut** method.
2. Edit the **DraftProject** object.
3. Check in the edited project using the **DraftProject CheckIn** method.


## Method Details

### <a name="checkout "></a> CheckOut()

Checks out the draft version of the project.

#### Syntax

```
DraftProject CheckOut()
```

#### Parameters

none

#### Return value

Type: (DraftProject) The draft version of the project.

### <a name="deleteobject"></a> DeleteObject()

Deletes the PublishedProject object.

#### Syntax

```
QueueJob DeleteObject()
```

#### Parameters

none

#### Return value

Type: (QueueJob) A QueueJob object that contains information about the queued job.

#### Remarks

If the queue job is successful, the Project Server Queuing Service deletes the published version of the project. The draft version is also deleted.


### <a name="submittoworkflow"></a> SubmitToWorkflow()

Causes the workflow to run.

#### Syntax

```
void SubmitToWorkflow()
```

#### Parameters

none

#### Return Value

void


### <a name="updatevisibilitycustomfields"></a> UpdateVisibilityCustomFields()
Updates the custom fields for a project in visibility mode.

#### Syntax

```
QueueJob UpdateVisibilityCustomFields() 
```

#### Parameters

none

#### Return value

Type: (QueueJob) A QueueJob object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service saves the published version of the project.
