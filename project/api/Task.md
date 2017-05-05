[comment]: # (Name:Task)
[comment]: # (Name:Microsoft.ProjectServer.Task)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>Task class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Contains methods and properties that can be used to access the details of the task.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class Task 
```

### JSOM

```javascript
PS.Task
```

### REST Interface

Supported.

```
PS.Task

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('projectid')/Tasks('taskid')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="ActualCostWorkPerformed"></a>ActualCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double|Decimal value|Gets the costs incurred for work already performed by resources on the task to date.|
|<a name="ActualDuration"></a>ActualDuration|&#x2713;|&#x2713;|&#x2713;|String|Gets the span of active working time that is required to complete a task.|
|<a name="ActualDurationMilliseconds"></a>ActualDurationMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the span of active working time that is required to complete a task.|
|<a name="ActualDurationTimeSpan"></a>ActualDurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the span of active working time that is required to complete a task.|
|<a name="ActualOvertimeCost"></a>ActualOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the costs incurred for overtime work already performed on the task by assigned resources.|
|<a name="ActualOvertimeWork"></a>ActualOvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the actual amount of overtime work that has already been performed by resources assigned to the task.|
|<a name="ActualOvertimeWorkMilliseconds"></a>ActualOvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the actual amount of overtime work already performed by resources assigned to the task.|
|<a name="ActualOvertimeWorkTimeSpan"></a>ActualOvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan||Gets the time interval for the actual amount of overtime work that has already been performed by resources assigned to the task.|
|<a name="BaselineCost"></a>BaselineCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total planned cost for the task.|
|<a name="BaselineDuration"></a>BaselineDuration|&#x2713;|&#x2713;|&#x2713;|String|Gets the original span of time that is planned to complete the task, established at the time of the project baseline.|
|<a name="BaselineDurationMilliseconds"></a>BaselineDurationMilliseconds||&#x2713;|&#x2713;|Integer||Gets the time interval, expressed in milliseconds, for the original span of time that is planned to complete the task, established at the time of the project baseline.|
|<a name="BaselineDurationTimeSpan"></a>BaselineDurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the original span of time that is planned to complete the task, established at the time of the project baseline.|
|<a name="BaselineFinish"></a>BaselineFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the planned task completion date that was set at the time that the baseline was saved.|
|<a name="BaselineStart"></a>BaselineStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the planned task start date that was set at the time that the baseline was saved.|
|<a name="BaselineWork"></a>BaselineWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total planned person-hours that are scheduled for a task, as established at the time of the project baseline.|
|<a name="BaselineWorkMilliseconds"></a>BaselineWorkMilliseconds||&#x2713;|&#x2713;|Integer|Decimal value|Gets the time interval, expressed in milliseconds, for the total planned person-hours that are scheduled for the task, as established at the time of the project baseline.|
|<a name="BaselineWorkTimeSpan"></a>BaselineWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the total planned person-hours that are scheduled for the task, as established at the time of the project baseline.|
|<a name="BudgetCost"></a>BudgetCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budget costs for budget cost resources.|
|<a name="BudgetedCostWorkPerformed"></a>BudgetedCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost of work that has been performed (BCWP) on the task to date.|
|<a name="BudgetedCostWorkScheduled"></a>BudgetedCostWorkScheduled|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost of work that is scheduled (BCWS) for the task.|
|<a name="Contact"></a>Contact|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the individual who is responsible for a task.|
|<a name="CostPerformanceIndex"></a>CostPerformanceIndex|&#x2713;|&#x2713;|&#x2713;|Double|Gets the ratio of the baseline costs of work that has been performed on the task to the actual costs of work that has been performed, calculated up to the project status date or today's date.|
|<a name="CostVariance"></a>CostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and the total cost for the task.|
|<a name="CostVarianceAtCompletion"></a>CostVarianceAtCompletion|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and the total cost at the completion of the task.|
|<a name="CostVariancePercentage"></a>CostVariancePercentage|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the ratio of cost variance (CV) to the budgeted cost of work that has been performed on the task (BCWP), expressed as a percentage.|
|<a name="Created"></a>Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and the time when the task was added to the project.|
|<a name="CurrentCostVariance"></a>CurrentCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and the actual cost of the task to date.|
|<a name="CustomFields"></a>CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets the collection of custom fields for the task.|
|<a name="DurationVariance"></a>DurationVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the difference between the baseline duration of the task and the total duration, or current estimated duration, of the task.|
|<a name="DurationVarianceMilliseconds"></a>DurationVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, of the difference between the baseline duration of the task and the total duration, or current estimated duration, of the task.|
|<a name="DurationVarianceTimeSpan"></a>DurationVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the difference between the baseline duration of the task and the total duration, or current estimated duration, of the task.|
|<a name="EarliestFinish"></a>EarliestFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the earliest date that the task could possibly finish, based on the early finish dates of predecessor and successor tasks, other constraints, and any leveling delay.|
|<a name="EarliestStart"></a>EarliestStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the earliest date that the task could possibly begin, based on the early start dates of predecessor and successor tasks and other constraints.|
|<a name="EstimateAtCompletion"></a>EstimateAtCompletion|&#x2713;|&#x2713;|&#x2713;|Double|Gets the estimate at completion (EAC) for the task.|
|<a name="FinishSlack"></a>FinishSlack|&#x2713;|&#x2713;|&#x2713;|String|Gets the duration between the EarlyFinish date and theLateFinish date.|
|<a name="FinishSlackMilliseconds"></a>FinishSlackMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|<a name="FinishSlackTimeSpan"></a>FinishSlackTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|<a name="FinishVariance"></a>FinishVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the time that represents the difference between the baseline finish date of the task and the current finish date.|
|<a name="FinishVarianceMilliseconds"></a>FinishVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, of the variance of the finish date of the task.|
|<a name="FinishVarianceTimeSpan"></a>FinishVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the variance of the finish date of the task.|
|<a name="FixedCostAccrual"></a>FixedCostAccrual|&#x2713;|&#x2713;|&#x2713;|[FixedCostAccrual](FixedCostAccrual.md)|Gets the cost accrual method for how and when fixed costs are to be charged, or accrued, to the cost of the task.|
|<a name="FreeSlack"></a>FreeSlack|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that the task can be delayed without delaying successor tasks.|
|<a name="FreeSlackMilliseconds"></a>FreeSlackMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, of the amount of time that the task can be delayed without delaying successor tasks.|
|<a name="FreeSlackTimeSpan"></a>FreeSlackTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the amount of time that the task can be delayed without delaying successor tasks.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the task.|
|<a name="IgnoreResourceCalendar"></a>IgnoreResourceCalendar|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the resource calendar is ignored when scheduling a task. True indicates the calendar is not used. False indicates that both the resource calendar and task calendar (if defined) are used when scheduling the task.|
|<a name="IsCritical"></a>IsCritical|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the timing for the task is critical or whether there can be any slack in the timing.|
|<a name="IsEffortDriven"></a>IsEffortDriven|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the scheduling of the task is effort-driven.|
|<a name="IsExternalTask"></a>IsExternalTask|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether this is a ghost task from another project created by Project Professional.|
|<a name="IsOverAllocated"></a>IsOverAllocated|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is overallocated.|
|<a name="IsRecurring"></a>IsRecurring|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is part of a recurring series.|
|<a name="IsRecurringSummary"></a>IsRecurringSummary|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is the parent of a recurring series.|
|<a name="IsRolledUp"></a>IsRolledUp|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether information on the subtask Gantt bars is rolled up to the summary task bar.|
|<a name="IsSubProject"></a>IsSubProject|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task represents a subproject.|
|<a name="IsSubProjectReadOnly"></a>IsSubProjectReadOnly|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether a subproject for this task is read-only.|
|<a name="IsSubProjectScheduledFromFinish"></a>IsSubProjectScheduledFromFinish|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether a subproject for this task is set to schedule from finish.|
|<a name="IsSummary"></a>IsSummary|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is a summary task.|
|<a name="LatestFinish"></a>LatestFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the latest date that the task can finish without delaying the finish of the project.|
|<a name="LatestStart"></a>LatestStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the latest date that the task can start without delaying the finish of the project.|
|<a name="LevelingDelay"></a>LevelingDelay|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that leveling can delay the task from its early start.|
|<a name="LevelingDelayMilliseconds"></a>LevelingDelayMilliseconds||&#x2713;|&#x2713;|Integer|Decimal value|Gets the time interval, expressed in milliseconds, for the amount of time that leveling can delay the task from its early start.|
|<a name="LevelingDelayTimeSpan"></a>LevelingDelayTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time that leveling can delay the task from its early start.|
|<a name="Modified"></a>Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the modified date.|
|<a name="Notes"></a>Notes|&#x2713;|&#x2713;|&#x2713;|String|Gets the notes about the task.|
|<a name="OutlinePosition"></a>OutlinePosition|&#x2713;|&#x2713;|&#x2713;|String|Gets the position of the task in the project outline hierarchy.|
|<a name="OvertimeCost"></a>OvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total overtime cost for the task.|
|<a name="OvertimeWork"></a>OvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of overtime scheduled to be performed on the task.|
|<a name="OvertimeWorkMilliseconds"></a>OvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of overtime scheduled to be performed on the task.|
|<a name="OvertimeWorkTimeSpan"></a>OvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the amount of overtime scheduled to be performed on the task.|
|<a name="PercentWorkComplete"></a>PercentWorkComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the current status of the task, expressed as the percentage of work that has been completed.|
|<a name="PreLevelingFinish"></a>PreLevelingFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the finish date of the task as it was before resource leveling was performed.|
|<a name="PreLevelingStart"></a>PreLevelingStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the start date of the task as it was before resource leveling was performed.|
|<a name="RegularWork"></a>RegularWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total amount of non-overtime work that is scheduled to be performed on the task.|
|<a name="RegularWorkMilliseconds"></a>RegularWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total amount of non-overtime work that is scheduled to be performed on the task.|
|<a name="RegularWorkTimeSpan"></a>RegularWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the total amount of non-overtime work that is scheduled to be performed on the task.|
|<a name="RemainingCost"></a>RemainingCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the remaining scheduled expense that will be incurred during completion of the remaining scheduled work on the task.|
|<a name="RemainingOvertimeCost"></a>RemainingOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the remaining scheduled overtime expense for the task.|
|<a name="RemainingOvertimeWork"></a>RemainingOvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time, such as person-hours or days, that is required to complete the remaining overtime work for a task.|
|<a name="RemainingOvertimeWorkMilliseconds"></a>RemainingOvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of time, such as person-hours or days, that is required to complete the remaining overtime work for a task.|
|<a name="RemainingOvertimeWorkTimeSpan"></a>RemainingOvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the amount of time, such as person-hours or days, that is required to complete the remaining overtime work for a task.|
|<a name="RemainingWork"></a>RemainingWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the time, such as person-hours or days, that is required to complete the task or set of tasks.|
|<a name="RemainingWorkMilliseconds"></a>RemainingWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the time, such as person-hours or days, that is required to complete the task or set of tasks.|
|<a name="RemainingWorkTimeSpan"></a>RemainingWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the time, such as person-hours or days, that is required to complete the task or set of tasks.|
|<a name="Resume"></a>Resume|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date that the remaining part of the task is scheduled to resume after progress is entered.|
|<a name="ScheduleCostVariance"></a>ScheduleCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference in cost terms between the current progress and the baseline planned progress for a resource on the task.|
|<a name="ScheduledDuration"></a>ScheduledDuration|&#x2713;|&#x2713;|&#x2713;|String|Gets the total span of active working time for the task as entered or as calculated based on the start date, the finish date, calendars, and other scheduling factors.|
|<a name="ScheduledDurationMilliseconds"></a>ScheduledDurationMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total span of active working time for the task as entered or as calculated based on the start date, the finish date, calendars, and other scheduling factors.|
|<a name="ScheduledDurationTimeSpan"></a>ScheduledDurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total span of active working time for the task as entered or as calculated based on the start date, the finish date, calendars, and other scheduling factors.|
|<a name="ScheduledFinish"></a>ScheduledFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when work on the task is scheduled to be complete as it was calculated based on the start date, the duration, dependencies, calendars, and other scheduling factors.|
|<a name="ScheduledStart"></a>ScheduledStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when work on the task is scheduled to begin as it was calculated based on dependencies, constraints, calendars, and other scheduling factors.|
|<a name="SchedulePerformanceIndex"></a>SchedulePerformanceIndex|&#x2713;|&#x2713;|&#x2713;|Double|Gets the ratio of the budgeted cost of work performed to the budgeted cost of work scheduled.|
|<a name="ScheduleVariancePercentage"></a>ScheduleVariancePercentage|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the ratio of schedule variance (SV) to budgeted cost of work scheduled (BCWS), expressed as a percentage.|
|<a name="StartSlack"></a>StartSlack|&#x2713;|&#x2713;|&#x2713;|String|Gets the duration between the EarlyStart date and theLateStart date.|
|<a name="StartSlackMilliseconds"></a>StartSlackMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the duration between the EarlyStart date and theLateStart date.|
|<a name="StartSlackTimeSpan"></a>StartSlackTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the duration between the EarlyStart date and theLateStart date.|
|<a name="StartVariance"></a>StartVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the time that represents the difference between a baseline start date of the task and its currently scheduled start date.|
|<a name="StartVarianceMilliseconds"></a>StartVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the variance of the task start date.|
|<a name="StartVarianceTimeSpan"></a>StartVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the variance of the task start date.|
|<a name="Stop"></a>Stop|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date that represents the end of the actual portion of the task.|
|<a name="SubProject"></a>SubProject|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Gets a project that has been inserted into the master project.|
|<a name="ToCompletePerformanceIndex"></a>ToCompletePerformanceIndex|&#x2713;|&#x2713;|&#x2713;|Double|Gets the To Complete Performance Index for the task.|
|<a name="TotalSlack"></a>TotalSlack|&#x2713;|&#x2713;|&#x2713;|String|Gets the time that the task's finish date can be delayed without delaying the project's finish date.|
|<a name="TotalSlackMilliseconds"></a>TotalSlackMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of time that the task finish date can be delayed without delaying the project's finish date.|
|<a name="TotalSlackTimeSpan"></a>TotalSlackTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the amount of time that the task finish date can be delayed without delaying the project's finish date.|
|<a name="WorkBreakdownStructure"></a>WorkBreakdownStructure|&#x2713;|&#x2713;|&#x2713;|String|Gets a code that identifies a location in a hierarchical structure that is used to organize tasks for reporting schedules and tracking costs.|
|<a name="WorkVariance"></a>WorkVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the difference between baseline work and currently scheduled work on a task, expressed as, for example, the number of person-hours or days.|
|<a name="WorkVarianceMilliseconds"></a>WorkVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the difference between baseline work and currently scheduled work on the task.|
|<a name="WorkVarianceTimeSpan"></a>WorkVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the difference between baseline work and currently scheduled work on the task.|

## <a name="seeAlso"></a>See Also

[DraftTask](DraftTask.md)<br/>
[ProjectSummaryTask](ProjectSummaryTask.md)<br/>
[PublishedTask](PublishedTask.md)<br/>
