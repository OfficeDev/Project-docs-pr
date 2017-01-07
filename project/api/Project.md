[comment]: # (Name:Project)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>Project class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Contains the common properties for draft projects and published projects.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class Project 
```

### JSOM

```JavaScript
PS.Project
```

### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.Project

http://<sitecollection> /<site> /_api/ProjectServer/Projects('projectid')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="ApprovedEnd"></a>ApprovedEnd|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the approved end date in the project portfolio planner.|
|<a name="ApprovedStart"></a>ApprovedStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the approved start date in the project portfolio planner.|
|<a name="CalculateActualCosts"></a>CalculateActualCosts|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project automatically calculates actual and remaining work and costs.|
|<a name="CalculatesActualCosts"></a>CalculatesActualCosts|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project always calculates actual costs.|
|<a name="CheckedOutBy"></a>CheckedOutBy|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the enterprise resource who has the project checked out.|
|<a name="CheckedOutDate"></a>CheckedOutDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when project was checked out.|
|<a name="CheckOutDescription"></a>CheckOutDescription|&#x2713;|&#x2713;|&#x2713;|String|Gets the description of the current checkout action for the project.|
|<a name="CheckOutId"></a>CheckOutId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the session GUID that is associated with the current check out.|
|<a name="CreatedDate"></a>CreatedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the project was created.|
|<a name="CriticalSlackLimit"></a>CriticalSlackLimit|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the date when the project was created.|
|<a name="CustomFields"></a>CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets the collection of project custom fields that have values set for the project.|
|<a name="DefaultFinishTime"></a>DefaultFinishTime|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the default end time of a working day.|
|<a name="DefaultOvertimeRateUnits"></a>DefaultOvertimeRateUnits|&#x2713;|&#x2713;|&#x2713;|[OvertimeRateFormat](OvertimeRateFormat.md)|Gets the time unit for the default overtime rate.|
|<a name="DefaultStandardRateUnits"></a>DefaultStandardRateUnits|&#x2713;|&#x2713;|&#x2713;|[StandardRateFormat](StandardRateFormat.md)|Gets the time unit for the default standard rate.|
|<a name="DefaultStartTime"></a>DefaultStartTime|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the default start time of a working day.|
|<a name="Engagements"></a>Engagements|&#x2713;|&#x2713;|&#x2713;|[ProjectEngagementCollection](ProjectEngagementCollection.md)||
|<a name="EnterpriseProjectType"></a>EnterpriseProjectType|&#x2713;|&#x2713;|&#x2713;|[EnterpriseProjectType](EnterpriseProjectType.md)|Gets the enterprise project type (EPT) for the project.|
|<a name="HasMppPendingImport"></a>HasMppPendingImport|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether there is an mpp file waiting to be imported.|
|<a name="HonorConstraints"></a>HonorConstraints|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether scheduling constraints take precedence over dependencies.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the project.|
|<a name="IsCheckedOut"></a>IsCheckedOut|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project is checked out.|
|<a name="LastPublishedDate"></a>LastPublishedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the most recent date when the project was published.|
|<a name="LastSavedDate"></a>LastSavedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the most recent date when the project was saved.|
|<a name="ListId"></a>ListId|||&#x2713;&#x02B7;|Guid||
|<a name="MoveActualIfLater"></a>MoveActualIfLater|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the end date of completed parts forward to the status date, if the actual end date falls before the status date. 
|<a name="MoveActualToStatus"></a>MoveActualToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the end date of completed parts back to the status date, if the actual end data falls after the status date.|
|<a name="MoveRemainingIfEarlier"></a>MoveRemainingIfEarlier|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the start date of remaining parts forward to the status date, if the actual start date falls before the status date.|
|<a name="MoveRemainingToStatus"></a>MoveRemainingToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to move the start date of the remaining parts back to the status date, if the actual start date falls after the status date.|
|<a name="MultipleCriticalPaths"></a>MultipleCriticalPaths|&#x2713;|&#x2713;|&#x2713;|Boolean||Gets a value that indicates whether to calculate multiple critical paths.|
|<a name="OptimizerDecision"></a>OptimizerDecision|&#x2713;|&#x2713;|&#x2713;|[CommittedDecisionResult](CommittedDecisionResult.md)|Gets the result of the Optimizer in a project portfolio analysis.|
|<a name="PercentComplete"></a>PercentComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the percentage complete of the project summary task.|
|<a name="Phase"></a>Phase|&#x2713;|&#x2713;|&#x2713;|[Phase](Phase.md)|Gets the current workflow phase of the project.|
|<a name="PlannerDecision"></a>PlannerDecision|&#x2713;|&#x2713;|&#x2713;|[CommittedDecisionResult](CommittedDecisionResult.md)|Gets the result of the Planner in a project portfolio analysis.|
|<a name="ProjectSiteUrl"></a>ProjectSiteUrl|&#x2713;|&#x2713;|&#x2713;|String|Gets the URL of the project site.|
|<a name="ProjectSummaryTask"></a>ProjectSummaryTask|&#x2713;|&#x2713;|&#x2713;|[ProjectSummaryTask](ProjectSummaryTask.md)|Gets the summary task that represents the entire project.|
|<a name="ProjectType"></a>ProjectType|&#x2713;|&#x2713;|&#x2713;|[ProjectType](ProjectType.md)|Gets the type of project (standard project, template, master project, or subproject).|
|<a name="QueueJobs"></a>QueueJobs|&#x2713;|&#x2713;|&#x2713;|[QueueJobCollection](QueueJobCollection.md)|Gets the collection of Project Server Queue Service jobs that are associated with the project.|
|<a name="ScheduledFromStart"></a>ScheduledFromStart|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets whether the project is scheduled from the finish date instead of the start date.|
|<a name="SplitInProgress"></a>SplitInProgress|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to split tasks that are in progress.|
|<a name="SpreadActualCostsToStatus"></a>SpreadActualCostsToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether actual costs are spread to the status date or to the stop date.|
|<a name="SpreadPercentCompleteToStatus"></a>SpreadPercentCompleteToStatus|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the percentage complete consideration period is spread to the status date or to the task finish date.|
|<a name="Stage"></a>Stage|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets the current workflow stage of the project.|
|<a name="SummaryTaskId"></a>SummaryTaskId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID for the hidden project summary task.|
|<a name="TaskListId"></a>TaskListId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the project's task list.|
|<a name="UserPermissions"></a>UserPermissions|||&#x2713;|[UserPermissionCollection](UserPermissionCollection.md)||
|<a name="WebId"></a>WebId|||&#x2713;&#x02B7;|Guid||

### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[EnterProjectStage(Stage stage)](#EnterProjectStage_[Stage]_Stage.md__stage_)|&#x2713;|&#x2713;|&#x2713;|void|Switches the project to the specified stage in a Project Server workflow.|
|[GetResourcePlan(DateTime start, DateTime end, TimeScale timeScale)](#GetResourcePlan_DateTime_start,_DateTime_end,_[TimeScale]_TimeScale.md__timeScale_)|&#x2713;|&#x2713;||[ResourcePlan](ResourcePlan.md)|Gets resource plan data for a project by filtering project data with date range and timescale parameters.|
|[GetResourcePlanByUrl(String start, String end, String scale)](#GetResourcePlanByUrl_String_start,_String_end,_String_scale_)|||&#x2713;|[ResourcePlan](ResourcePlan.md)||
|[LeaveProjectStage()](#LeaveProjectStage__)|&#x2713;|&#x2713;|&#x2713;|void|Sets the project complete and leaves the current workflow stage.|
|[ReadyToLeaveProjectStage()](#ReadyToLeaveProjectStage__)|&#x2713;|&#x2713;|&#x2713;|[ReadyToLeaveProjectStageValue](ReadyToLeaveProjectStageValue.md)|Checks whether the current workflow stage requirements are met and the project is ready to move to the next stage.|
|[SetCustomFieldValue(String fieldName, Object value)](#SetCustomFieldValue_String_fieldName,_Object_value_)|&#x2713;|&#x2713;||void|Sets a custom field on the project.|
|[UpdateIdeaListItemStatus(String status)](#UpdateIdeaListItemStatus_String_status_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the Project Server Status column in the idea list with a status message.|
|[UpdateProjectStageStatus(Stage stage, String statusInformation, UpdateProjectStageStatusFieldValue stageStatusValue, Boolean append)](#UpdateProjectStageStatus_[Stage]_Stage.md__stage,_String_statusInformation,_[UpdateProjectStageStatusFieldValue]_UpdateProjectStageStatusFieldValue.md__stageStatusValue,_Boolean_append_)|&#x2713;|&#x2713;|&#x2713;|void|Updates the status of a workflow stage for the project.|

<br/>
#### Method Details

#### <a name="EnterProjectStage_[Stage]_Stage.md__stage_"></a>EnterProjectStage([Stage](Stage.md) stage)

Switches the project to the specified stage in a Project Server workflow.

##### Syntax

```
void EnterProjectStage(Stage stage)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|stage| [Stage](Stage.md)|The workflow stage.

##### Return Value

void

#### <a name="GetResourcePlan_DateTime_start,_DateTime_end,_[TimeScale]_TimeScale.md__timeScale_"></a>GetResourcePlan(DateTime start, DateTime end, [TimeScale](TimeScale.md) timeScale)

Gets resource plan data for a project by filtering project data with date range and timescale parameters.

##### Syntax

```
ResourcePlan GetResourcePlan(DateTime start, DateTime end, TimeScale timeScale)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start|DateTime|The start date for the resource plan data.|
|end|DateTime|The end date for the resource plan data.|
|timeScale|[TimeScale](TimeScale.md)|An enumeration that represents a time scale (for example, days or weeks).|

##### Return Value

[ResourcePlan](ResourcePlan.md)

#### <a name="GetResourcePlanByUrl_String_start,_String_end,_String_scale_"></a>GetResourcePlanByUrl(String start, String end, String scale)


##### Syntax

```
ResourcePlan GetResourcePlanByUrl(String start, String end, String scale)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start|String|The start date for the resource plan data.|
|end|String|The end date for the resource plan data.|
|scale|String|An enumeration that represents a time scale (for example, days or weeks).  See [TimeScale](TimeScale.md)|

##### Return Value

[ResourcePlan](ResourcePlan.md)<br />
A resource plan.

#### Remarks

A resource plan provides a way to estimate corporate resource capacity when some projects are in full execution and others are still in the proposal phase or planning phase.

#### <a name="LeaveProjectStage__"></a>LeaveProjectStage()

Sets the project complete and leaves the current workflow stage.

##### Syntax

```
void LeaveProjectStage()
```

##### Parameters

None

##### Return Value

void

#### <a name="ReadyToLeaveProjectStage__"></a>ReadyToLeaveProjectStage()

Checks whether the current workflow stage requirements are met and the project is ready to move to the next stage.

##### Syntax

```
ReadyToLeaveProjectStageValue ReadyToLeaveProjectStage()
```

##### Parameters

None

##### Return Value

[ReadyToLeaveProjectStageValue](ReadyToLeaveProjectStageValue.md)<br />
A collection of enumeration constants that describe which of the requirements are not met.


#### <a name="SetCustomFieldValue_String_fieldName,_Object_value_"></a>SetCustomFieldValue(String fieldName, Object value)

Sets a custom field on the project.

##### Syntax

```
void SetCustomFieldValue(String fieldName, Object value)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|fieldName|String|The [InternalName](CustomField.md#InternalName) of the custom field to update.|
|value|Object|New value of the custom field.|

##### Return Value

void

#### <a name="UpdateIdeaListItemStatus_String_status_"></a>UpdateIdeaListItemStatus(String status)

Updates the Project Server Status column in the idea list with a status message.

##### Syntax

```
void UpdateIdeaListItemStatus(String status)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----   |:------ |
|status|String|The project status message.|

##### Return Value

void

#### <a name="UpdateProjectStageStatus_[Stage]_Stage.md__stage,_String_statusInformation,_[UpdateProjectStageStatusFieldValue]_UpdateProjectStageStatusFieldValue.md__stageStatusValue,_Boolean_append_"></a>UpdateProjectStageStatus([Stage](Stage.md) stage, String statusInformation, [UpdateProjectStageStatusFieldValue](UpdateProjectStageStatusFieldValue.md) stageStatusValue, Boolean append)

Updates the status of a workflow stage for the project.

##### Syntax

```
void UpdateProjectStageStatus(Stage stage, String statusInformation, UpdateProjectStageStatusFieldValue stageStatusValue, Boolean append)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----   |:------ |
|stage|[Stage](Stage.md)|The workflow stage to be updated.
| statusInformation | String | The status message.
|stageStatusValue|[UpdateProjectStageStatusFieldValue](UpdateProjectStageStatusFieldValue.md)|An enumeration constant that indicates the stage status.
|append|Boolean|True if the status message is appended to the current stage status;False if the status message overwrites the current status.

##### Return Value

void


## Remarks

The **[DraftProject class](DraftProject.md)** class and the **[PublishedProject class](PublishedProject.md)** class derive from the **Project** class. 

To set the value of properties in an existing project:

1. Use the **[PublishedProject](PublishedProject.md) CheckOut** method.
2. Edit the **[DraftProject](DraftProject.md)** object.
3. Check in the edited project using the **[DraftProject](DraftProject.md) CheckIn** method.

## <a name="seeAlso"></a>See Also

[DraftProject](DraftProject.md)<br/>
[Engagement](Engagement.md)<br/>
[ProjectEngagement](ProjectEngagement.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
[QueueJob](QueueJob.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
