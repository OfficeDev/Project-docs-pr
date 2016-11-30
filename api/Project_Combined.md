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

The **DraftProject** class and the **PublishedProject** class derive from the **Project** class. 

To set the value of properties in an existing project:

1. Use the **PublishedProject CheckOut** method.
2. Edit the **DraftProject** object.
3. Check in the edited project using the **DraftProject CheckIn** method.

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
|CheckOutId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the session GUID that is associated with the current check out.|
|CreatedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the project was created.|
|CriticalSlackLimit|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the number of days that a task can go past its end date before the project marks that task as critical. |
|CustomFields|&#x2713;|&#x2713;|&#x2713;|CustomFieldCollection class|Gets the collection of project custom fields that have values set for the project.|
|DefaultFinishTime|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the default end time of a working day. |
|DefaultOvertimeRateUnits|&#x2713;|&#x2713;|&#x2713;|Enumerated value|Gets the time unit for the default overtime rate that is stored by the DefaultOvertimeRate property.|
|DefaultStandardRateUnits|&#x2713;|&#x2713;|&#x2713;|Enumerated value|Gets the time unit for the default standard rate that is stored by the DefaultStandardRate property.|
|DefaultStartTime|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the default start time of a working day. |
|Engagements|&#x2713;|&#x2713;|&#x2713;|PS.ProjectEngagementCollection||
|EnterpriseProjectType|&#x2713;|&#x2713;|&#x2713;|EnterpriseProjectType|Gets the enterprise project type (EPT) for the project.|
|HasMppPendingImport|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether there is an mpp file waiting to be imported.|
|HonorConstraints|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether scheduling constraints take precedence over dependencies. |
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the project.|
|IsCheckedOut|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project is checked out.|
|LastPublishedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the most recent date when the project was published.|
|LastSavedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the most recent date when the project was saved.|
|ListId|||&#x2713;|Guid||
|MoveActualIfLater|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the end date of completed parts forward to the status date, if the actual end date falls before the status date. |
|MoveActualToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the end date of completed parts back to the status date, if the actual end data falls after the status date. |
|MoveRemainingIfEarlier|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the start date of remaining parts forward to the status date, if the actual start date falls before the status date. |
|MoveRemainingToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the start date of the remaining parts back to the status date, if the actual start date falls after the status date. |
|MultipleCriticalPaths|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to calculate multiple critical paths. |
|OptimizerDecision|&#x2713;|&#x2713;|&#x2713;|Enumerated value|Gets the result of the Optimizer in a project portfolio analysis.|
|PercentComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the percentage complete of the project summary task.|
|Phase|&#x2713;|&#x2713;|&#x2713;|Phase|Gets the current workflow phase of the project.|
|PlannerDecision|&#x2713;|&#x2713;|&#x2713;|Enumerated value|Gets the result of the Planner in a project portfolio analysis.|
|ProjectSiteUrl|&#x2713;|&#x2713;|&#x2713;|String|Gets the URL of the project site.|
|ProjectSummaryTask|&#x2713;|&#x2713;|&#x2713;|ProjectSummaryTask||
|ProjectType|&#x2713;|&#x2713;|&#x2713;|Enumerated value|Gets the type of project (standard project, template, master project, or subproject).|
|QueueJobs|&#x2713;|&#x2713;|&#x2713;|QueueJobCollection|Gets the collection of Project Server Queue Service jobs that are associated with the project.|
|ScheduledFromStart|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets whether the project is scheduled from the finish date instead of the start date. |
|SplitInProgress|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to split tasks that are in progress. |
|SpreadActualCostsToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether actual costs are spread to the status date or to the stop date. |
|SpreadPercentCompleteToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the percentage complete consideration period is spread to the status date or to the task finish date. |
|Stage|&#x2713;|&#x2713;|&#x2713;|Stage|Gets the current workflow stage of the project.|
|SummaryTaskId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID for the hidden project summary task.|
|TaskListId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the project's task list.|
|UserPermissions|||&#x2713;|UserPermissions||
|WebId|||&#x2713;|Guid||


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[EnterProjectStage(stage: Stage)](#enterprojectstage)|&#x2713;|&#x2713;| |void|Switches the project to the specified stage in a Project Server workflow.|
|[GetResourcePlan(start: DateTime, end: DateTime, timeScale: TimeScale)](#getresourceplan)|&#x2713;|&#x2713;||ResourcePlan|Gets resource plan data for a project by filtering project data with date range and timescale parameters.|
|[GetResourcePlanByUrl(start: string, end: string, timeScale: string)](#getresourceplanbyurl)|||&#x2713;|ResourcePlan|Gets resource plan data for a project by filtering project data with date range and timescale parameters.|
|[LeaveProjectStage()](#leaveprojectstage)|&#x2713;|&#x2713;|&#x2713;|void|Sets the project complete and leaves the current workflow stage.|
|[ReadyToLeaveProjectStage()](#readytoleaveprojectstage)|&#x2713;|&#x2713;|&#x2713;|Enumerated value|Checks whether the current workflow stage requirements are met and the project is ready to move to the next stage.|
|[SetCustomFieldValue(fieldName: string, value: object)](#setcustomfieldvalue)|&#x2713;|&#x2713;| |void|Sets a custom field on the project.|
|[UpdateIdeaListItemStatus(status: string)](#updateidealistitemstatus)|&#x2713;|&#x2713;|&#x2713;|void|Updates the Project Server Status column in the idea list with a status message.|
|[UpdateProjectStageStatus(stage: Stage, statusInformation: string, stageStatusValue: UpdateProjectStageStatusFieldValue, append: Boolean)](#updateprojectstagestatus)|&#x2713;|&#x2713;| |void|Updates the status of a workflow stage for the project.|


<!-- Originals. Replaced with entries above. 
  |[EnterProjectStage(stage: Stage)](#enterprojectstage)|&#x2713;|&#x2713;|&#x2713;|void|Switches the project to the specified stage in a Project Server workflow.|

  |[SetCustomFieldValue(fieldName: string, value: object)](#setcustomfieldvalue)|&#x2713;|&#x2713;|&#x2713;|void|Sets a custom field on the project.|

  |[UpdateProjectStageStatus(stage: Stage, statusInformation: string, stageStatusValue: UpdateProjectStageStatusFieldValue, append: Boolean)](#updateprojectstagestatus)|&#x2713;|&#x2713;|&#x2713;|void|Updates the status of a workflow stage for the project.|
 
-->


## Method Details

### <a name="enterprojectstage"></a>EnterProjectStage(stage: Stage)

Switches the project to the specified stage in a Project Server workflow.

#### Syntax

```
EnterProjectStage(stage: Stage)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|stage| Stage|The workflow stage.

#### Return Value

void

### <a name="getresourceplan"></a> GetResourcePlan(start: DateTime, end: DateTime, timeScale: TimeScale)

Gets resource plan data for a project by filtering project data with date range and timescale parameters.

#### Syntax

```
GetResourcePlan(start: DateTime, end: DateTime, timeScale: TimeScale)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| DateTime | The start date for the resource plan data.
|end| DateTime | The end date for the resource plan data.
|timeScale |TimeScale| An enumeration that represents a time scale (for example, days or weeks).

#### Return value

ResourcePlan<br />
A resource plan.

#### Remarks

A resource plan provides a way to estimate corporate resource capacity when some projects are in full execution and others are still in the proposal phase or planning phase.


###  <a name="getresourceplanbyurl"></a> GetResourcePlanByUrl(start: string, end: string, timeScale: string)

Gets resource plan data for a project by filtering project data with date range and timescale parameters.

#### Syntax

```
GetResourcePlanByUrl(start: string, end: string, timeScale: string)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| string | The start date for the resource plan data.
|end| string | The end date for the resource plan data.
|timeScale | string | An enumeration that represents a time scale (for example, days or weeks).

#### Return value

ResourcePlan<br />
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

ClientResult<br />
A collection of enumeration constants that describe which of the requirements are not met.


### <a name="setcustomfieldvalue"></a> SetCustomFieldValue(fieldName: string, value: object)

Sets a custom field on the project.

#### Syntax

```
SetCustomFieldValue(fieldName: string, value: object)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|fieldName | string | The name of the custom field.|
|value     | object | The value to be set for the custom field.|


#### Return Value

void

### <a name="updateidealistitemstatus"></a> UpdateIdeaListItemStatus(status: string)

Updates the Project Server Status column in the idea list with a status message.

#### Syntax

```
UpdateIdeaListItemStatus(status: string)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----   |:------ |
|status  | string | The project status message.|

#### Return Value

void

### <a name="updateprojectstagestatus"></a> UpdateProjectStageStatus(stage: Stage, statusInformation: string, stageStatusValue: UpdateProjectStageStatusFieldValue, append: Boolean)

Updates the status of a workflow stage for the project.

#### Syntax

```
UpdateProjectStageStatus(stage: Stage, statusInformation: string, stageStatusValue: UpdateProjectStageStatusFieldValue, append: Boolean)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----   |:------ |
| stage | Stage | The workflow stage to be updated.|
| statusInformation | string | The status message.
| stageStatusValue | UpdateProjectStageStatusFieldValue | An enumeration constant that indicates the stage status. |
| append | Boolean | True if the status message is appended to the current stage status; False if the status message overwrites the current status.|

#### Return Value

void


## See Also

[DraftProject class](DraftProject_Combined.md) <br />
[PublishedProject class](PublishedProject_Combined.md)