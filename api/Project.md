# Project 

Base project class that contains inheritable properties and methods common to draft and published projects.

## Syntax

### CSOM

```C#
Class Project
```

### JSOM

```
PS.Project
```

### REST Interface

This resource supports GET and DELETE HTTP commands:

```
http://<sitecollection> /<site> /_api/ProjectServer/Projects('projectid')
```

## Remarks

The **[DraftProject class](DraftProject.md)** class and the **[PublishedProject class](PublishedProject.md)** class derive from the **Project** class. 

To set the value of properties in an existing project:

1. Use the **[PublishedProject](PublishedProject.md) CheckOut** method.
2. Edit the **[DraftProject](DraftProject.md)** object.
3. Check in the edited project using the **[DraftProject](DraftProject.md) CheckIn** method.

## Members

### Properties

<!-- The following table has left-aligned columns 1,5,6; and center-aligned columns 2,3,4. -->

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ApprovedEnd|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the approved end date in the project portfolio planner.|
|ApprovedStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the approved start date in the project portfolio planner.|
|CalculateActualCosts|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project automatically calculates actual and remaining work and costs. |
|CalculatesActualCosts|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project always calculates actual costs. |
|CheckedOutBy|&#x2713;|&#x2713;|&#x2713;|User|Gets the enterprise resource who has the project checked out.|
|CheckedOutDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when project was checked out.|
|CheckOutDescription|&#x2713;|&#x2713;|&#x2713;|String|Gets the description of the current checkout action for the project.|
|CheckOutId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the session Guid that is associated with the current check out.|
|CreatedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the project was created.|
|CriticalSlackLimit|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the number of days that a task can go past its end date before the project marks that task as critical. |
|CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets the collection of project custom fields that have values set for the project.|
|DefaultFinishTime|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the default end time of a working day. |
|DefaultOvertimeRateUnits|&#x2713;|&#x2713;|&#x2713;|[OvertimeRateFormat](OvertimeRateFormat.md)|Gets the time unit for the default overtime rate.|
|DefaultStandardRateUnits|&#x2713;|&#x2713;|&#x2713;|[StandardRateFormat](StandardRateFormat.md)|Gets the time unit for the default standard rate.|
|DefaultStartTime|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the default start time of a working day. |
|Engagements|&#x2713;|&#x2713;|&#x2713;|[ProjectEngagementCollection](ProjectEngagementCollection.md)||
|EnterpriseProjectType|&#x2713;|&#x2713;|&#x2713;|[EnterpriseProjectType](EnterpriseProjectType.md)|Gets the enterprise project type for the project.|
|HasMppPendingImport|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether there is an mpp file waiting to be imported.|
|HonorConstraints|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether scheduling constraints take precedence over dependencies. |
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the Guid of the project.|
|IsCheckedOut|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project is checked out.|
|LastPublishedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the most recent date when the project was published.|
|LastSavedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the most recent date when the project was saved.|
|ListId|||&#x2713;|Guid|Gets the Id of the list that formed the basis of the project.|
|MoveActualIfLater|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the end date of completed parts forward to the status date, if the actual end date falls before the status date. |
|MoveActualToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the end date of completed parts back to the status date, if the actual end data falls after the status date. |
|MoveRemainingIfEarlier|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the start date of remaining parts forward to the status date, if the actual start date falls before the status date. |
|MoveRemainingToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the start date of the remaining parts back to the status date, if the actual start date falls after the status date. |
|MultipleCriticalPaths|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to calculate multiple critical paths. |
|OptimizerDecision|&#x2713;|&#x2713;|&#x2713;|[CommittedDecisionResult](CommittedDecisionResult.md)|Gets the result of the Optimizer in a project portfolio analysis.|
|PercentComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the percentage complete of the project summary task.|
|Phase|&#x2713;|&#x2713;|&#x2713;|[Phase](Phase.md)|Gets the current workflow phase of the project.|
|PlannerDecision|&#x2713;|&#x2713;|&#x2713;|[CommittedDecisionResult](CommittedDecisionResult.md)|Gets the result of the Planner in a project portfolio analysis.|
|ProjectSiteUrl|&#x2713;|&#x2713;|&#x2713;|String|Gets the URL of the project site.|
|ProjectSummaryTask|&#x2713;|&#x2713;|&#x2713;|[ProjectSummaryTask](ProjectSummaryTask.md)|Gets the summary task that represents the entire project.|
|ProjectType|&#x2713;|&#x2713;|&#x2713;|[ProjectType](ProjectType.md)|Gets the type of project (standard project, template, master project, or subproject).|
|QueueJobs|&#x2713;|&#x2713;|&#x2713;|[QueueJobCollection](QueueJobCollection.md)|Gets the collection of Project Server Queue Service jobs that are associated with the project.|
|ScheduledFromStart|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets whether the project is scheduled from the finish date instead of the start date. |
|SplitInProgress|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to split tasks that are in progress. |
|SpreadActualCostsToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether actual costs are spread to the status date or to the stop date. |
|SpreadPercentCompleteToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the percentage complete consideration period is spread to the status date or to the task finish date. |
|Stage|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets the current workflow stage of the project.|
|SummaryTaskId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the Guid for the hidden project summary task.|
|TaskListId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the Guid of the project's task list.|
|UserPermissions|||&#x2713;|UserPermissions||
|WebId|||&#x2713;|Guid|Gets a value that identifies the site that contains the project.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[EnterProjectStage(Stage stage)](#enterprojectstage)|&#x2713;|&#x2713;| |void|Switches the project to the specified stage in a Project Server workflow.|
|[GetResourcePlan(DateTime start, DateTime end, TimeScale timeScale)](#getresourceplan)|&#x2713;|&#x2713;||[ResourcePlan](ResourcePlan.md)|Gets resource plan data for a project by filtering project data with date range and timescale parameters.|
|[GetResourcePlanByUrl(String start, String end, String timeScale)](#getresourceplanbyurl)|||&#x2713;|[ResourcePlan](ResourcePlan.md)|Gets resource plan data for a project by filtering project data with date range and timescale parameters.|
|[LeaveProjectStage()](#leaveprojectstage)|&#x2713;|&#x2713;|&#x2713;|void|Sets the project complete and leaves the current workflow stage.|
|[ReadyToLeaveProjectStage()](#readytoleaveprojectstage)|&#x2713;|&#x2713;|&#x2713;|[ReadyToLeaveProjectStageValue](ReadyToLeaveProjectStageValue.md)|Checks whether the current workflow stage requirements are met and the project is ready to move to the next stage.|
|[SetCustomFieldValue(String fieldName, Object value)](#setcustomfieldvalue)|&#x2713;|&#x2713;| |void|Sets a custom field on the project.|
|[UpdateIdeaListItemStatus(String status)](#updateidealistitemstatus)|&#x2713;|&#x2713;|&#x2713;|void|Updates the Project Server Status column in the idea list with a status message.|
|[UpdateProjectStageStatus(Stage stage, String statusInformation, UpdateProjectStageStatusFieldValue stageStatusValue, Boolean append)](#updateprojectstagestatus)|&#x2713;|&#x2713;| |void|Updates the status of a workflow stage for the project.|


## Method Details

### <a name="enterprojectstage"></a>EnterProjectStage(Stage stage)

Switches the project to the specified stage in a Project Server workflow.

#### Syntax

```
void EnterProjectStage(Stage stage)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|stage| [Stage](Stage.md)|The workflow stage.

#### Return Value

void



### <a name="getresourceplan"></a> GetResourcePlan(DateTime start, DateTime end, TimeScale timeScale)

Gets resource plan data for a project by filtering project data with date range and timescale parameters.

#### Syntax

```
GetResourcePlan(DateTime start, DateTime end, TimeScale timeScale)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| DateTime | The start date for the resource plan data.
|end| DateTime | The end date for the resource plan data.
|timeScale |[TimeScale](TimeScale.md)| An enumeration that represents a time scale (for example, days or weeks).

#### Return value

[ResourcePlan](ResourcePlan.md)<br />
A resource plan.

#### Remarks

A resource plan provides a way to estimate corporate resource capacity when some projects are in full execution and others are still in the proposal phase or planning phase.


###  <a name="getresourceplanbyurl"></a> GetResourcePlanByUrl(String start, String end, String timeScale)

Gets resource plan data for a project by filtering project data with date range and timescale parameters.

#### Syntax

```
GetResourcePlanByUrl(String start, String end, String timeScale)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| String | The start date for the resource plan data.
|end| String | The end date for the resource plan data.
|timeScale | String | An enumeration that represents a time scale (for example, days or weeks).

#### Return value

[ResourcePlan](ResourcePlan.md)<br />
A resource plan.

#### Remarks

A resource plan provides a way to estimate corporate resource capacity when some projects are in full execution and others are still in the proposal phase or planning phase.

### <a name="leaveprojectstage"></a> LeaveProjectStage()

Sets the project complete and leaves the current workflow stage.

#### Syntax

```
LeaveProjectStage()
```

#### Parameters

none

#### Return Value

void


### <a name="readytoleaveprojectstage"></a> ReadyToLeaveProjectStage()

Checks whether the current workflow stage requirements are met and the project is ready to move to the next stage.

#### Syntax

```
ReadyToLeaveProjectStage()
```

#### Parameters

none

#### Return value

[ReadyToLeaveProjectStageValue](ReadyToLeaveProjectStageValue.md)<br />
A collection of enumeration constants that describe which of the requirements are not met.


### <a name="setcustomfieldvalue"></a> SetCustomFieldValue(String fieldName, Object value)

Sets a custom field on the project.

#### Syntax

```
SetCustomFieldValue(String fieldName, Object value)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|fieldName | String | The name of the custom field.|
|value     | Object | The value to be set for the custom field.|


#### Return Value

void

### <a name="updateidealistitemstatus"></a> UpdateIdeaListItemStatus(String status)

Updates the Project Server Status column in the idea list with a status message.

#### Syntax

```
UpdateIdeaListItemStatus(String status)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----   |:------ |
|status  | String | The project status message.|

#### Return Value

void

### <a name="updateprojectstagestatus"></a> UpdateProjectStageStatus(Stage stage, String statusInformation, UpdateProjectStageStatusFieldValue stageStatusValue, Boolean append)

Updates the status of a workflow stage for the project.

#### Syntax

```
UpdateProjectStageStatus(Stage stage, String statusInformation, UpdateProjectStageStatusFieldValue stageStatusValue, Boolean append)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----   |:------ |
| stage | [Stage](Stage) | The workflow stage to be updated.|
| statusInformation | String | The status message.
| stageStatusValue | [UpdateProjectStageStatusFieldValue](UpdateProjectStageStatusFieldValue.md) | An enumeration constant that indicates the stage status. |
| append | Boolean | True if the status message is appended to the current stage status; False if the status message overwrites the current status.|

#### Return Value

void


## See Also

[DraftProject class](DraftProject.md) <br />
[PublishedProject class](PublishedProject.md)
