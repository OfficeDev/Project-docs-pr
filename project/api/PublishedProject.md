# PublishedProject 
Represents a project that is published on Project Server.

[PublishedProject](PublishedProject.md) inherits properties and methods from [Project](Project.md).

## Syntax

### CSOM

```
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

1. Use the **[PublishedProject](PublishedProject.md) [CheckOut](#checkout)** method.
2. Edit the **[DraftProject](DraftProject.md)** object.
3. Check in the edited project using the **[DraftProject](DraftProject.md) CheckIn** method.

## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Assignments|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignmentCollection](PublishedAssignmentCollection.md)|Gets the collection of assignments in the project.|
|Calendar|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets the project calendar. |
|CurrencyCode|&#x2713;|&#x2713;|&#x2713;|String|Gets the currency code of the project, as defined in ISO 4217. |
|CurrencyDigits|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the number of decimal digits in currency values. |
|CurrencyPosition|&#x2713;|&#x2713;|&#x2713;|[CurrencySymbolPosition](CurrencySymbolPosition.md)|Gets the placement of the currency symbol in relation to the currency value. |
|CurrencySymbol|&#x2713;|&#x2713;|&#x2713;|String|Gets the currency symbol that represents the type of currency that is used in the project. |
|CurrentDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the current date for the project. |
|DaysPerMonth|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the default number of working days per month. |
|DefaultEffortDriven|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the scheduling of new tasks is effort-driven. |
|DefaultEstimatedDuration|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether new tasks have estimated durations. |
|DefaultFixedCostAccrual|&#x2713;|&#x2713;|&#x2713;|[FixedCostAccrual](FixedCostAccrual.md)|Gets a value that indicates which default fixed-cost accrual method to use on new tasks. |
|DefaultOvertimeRate|&#x2713;|&#x2713;|&#x2713;|Double|Gets the default overtime rate for local resources. |
|DefaultStandardRate|&#x2713;|&#x2713;|&#x2713;|Double|Gets the default standard rate for local resources. |
|DefaultTaskType|&#x2713;|&#x2713;|&#x2713;|[TaskType](TaskType.md)|Gets the default type for tasks in the project. |
|DefaultWorkFormat|&#x2713;|&#x2713;|&#x2713;|[WorkFormat](WorkFormat.md)|Gets the default format for work duration. |
|Description|&#x2713;|&#x2713;|&#x2713;|String|Gets the project description. |
|Draft|&#x2713;|&#x2713;|&#x2713;|[DraftProject](DraftProject.md)|Gets a DraftProject object if it is not already checked out. |
|EnterpriseProjectTypeId|||&#x2713;|Guid|Gets the GUID of the enterprise project type.|
|EntityLinks|||&#x2713;|[EntityLinkCollection](EntityLinkCollection.md)||
|FieldValues|&#x2713;|&#x2713;|&#x2713;|Dictionary&lt;string, Object&gt;|Gets the custom field values for the published project. |
|FinishDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the project finish date. |
|FiscalYearStartMonth|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the number of the first month in the fiscal year. |
|IncludeCustomFields|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Gets a PublishedProject object that includes custom fields. |
|IsEnterpriseProject|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the published project is an enterprise project (managed by Project Server). |
|Item|&#x2713;&#x02B7;|&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the project. |
|MinutesPerDay|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the default number of minutes per day. |
|MinutesPerWeek|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the default number of minutes per week. |
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the project. |
|NewTasksAreManual|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether new tasks are manually scheduled. |
|NumberFiscalYearFromStart|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to use the project start year for fiscal year numbering. |
|Owner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the owner of the project. |
|ProjectIdentifier|&#x2713;|&#x2713;|&#x2713;|String|Gets the GUID of the project.|
|ProjectResources|&#x2713;|&#x2713;|&#x2713;|[PublishedProjectResourceCollection](PublishedProjectResourceCollection.md)|Gets the collection of resources for a project. |
|ProtectedActualsSynch|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets whether the project actuals are synchronized with the protected actuals. |
|ShowEstimatedDurations|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether a question mark is displayed after an estimated duration for a task. |
|StartDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the project start date. |
|StatusDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the status date for the project. |
|TaskLinks|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLinkCollection](PublishedTaskLinkCollection.md)|Gets the collection of task links for the project. |
|Tasks|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskCollection](PublishedTaskCollection.md)|Gets the collection of tasks for the project. |
|TrackingMode|&#x2713;|&#x2713;|&#x2713;|[TrackingMode](TrackingMode.md)|Gets the default tracking method for all assignments in the project. |
|UtilizationDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time of resource utilization for the current project.|
|UtilizationType|&#x2713;|&#x2713;|&#x2713;|[UtilizationType](UtilizationType.md)|Gets the derivation source(s) of the summary resource assignments of a project. Uses the UtilizationType enumeration.|
|WeekStartDay|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the day of the week on which a work week starts. |
|WinprojVersion|&#x2713;|&#x2713;|&#x2713;|Decimal|Gets the version of Project Professional that created the published project. |


### Methods

|**Name**|**CSOM** |**JSOM** |**REST** |**Return Type**|**Description**|
|:-----|:-----: |:-----: |:-----: |:-----|:-----|
|[CheckOut()](#checkout)|&#x2713; |&#x2713; |&#x2713; |[DraftProject](DraftProject.md)|Checks out the draft version of the project.|
|[CreateProjectSite(String siteName)](#createprojectsite)|&#x2713;|&#x2713;|&#x2713;|void|Creates a project site. |
|[DeleteObject()](#deleteobject)|&#x2713; |&#x2713; |&#x2713; |[QueueJob](QueueJob.md)|Deletes the [PublishedProject](PublishedProject.md) object.|
|[SubmitToWorkflow()](#submittoworkflow)|&#x2713; |&#x2713; |&#x2713; |void|Causes the workflow to run.|
|[UpdateVisibilityCustomFields()](#updatevisibilitycustomfields)|&#x2713; |&#x2713; |&#x2713; |[QueueJob](QueueJob.md)|Updates the custom fields for a project in visibility mode.|


## Method Details

### <a name="checkout "></a> CheckOut()

Checks out the draft version of the project.

#### Syntax

```
CheckOut()
```

#### Parameters

none

#### Return value

[DraftProject](DraftProject.md)<br />
The draft version of the project.




### <a id="createprojectsite"></a>CreateProjectSite(String siteName)

Creates a project site.

#### Syntax

```
void CreateProjectSite(String siteName)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|siteName| String |Name of the new project website. If empty, the website name will be the same as the project name.|


#### Return Value

void




### <a name="deleteobject"></a> DeleteObject()

Deletes the [PublishedProject](PublishedProject.md) object.

#### Syntax

```
DeleteObject()
```

#### Parameters

none

#### Return value

[QueueJob](QueueJob.md)<br />
A [QueueJob](QueueJob.md) object that contains information about the queued job.

#### Remarks

If the queue job is successful, the Project Server Queuing Service deletes the published version of the project. The draft version is also deleted.


### <a name="submittoworkflow"></a> SubmitToWorkflow()

Causes the workflow to run.

#### Syntax

```
SubmitToWorkflow()
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

[QueueJob](QueueJob.md)<br />
A [QueueJob](QueueJob.md) object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service saves the published version of the project.

## See Also

[Project class](Project.md) <br />
[DraftProject class](DraftProject.md)
