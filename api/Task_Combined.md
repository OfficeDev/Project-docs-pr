
# Task class
Contains inheritable properties common to draft and published tasks.

A task is an activity that has a beginning and an end. Project plans are made up of tasks.

## Syntax

### CSOM

```C#
Class Project
```

### JSOM

```
PS.Task
```

### REST Interface

This resource supports the GET and DELETE HTTP commands.

```
http://<sitecollection> /<site> /_api/ProjectServer/Tasks('taskid')
```

## Members

### Properties

|**CSOM**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ActualCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double|Gets the costs incurred for work already performed by resources on the task to date.|
|ActualDuration|&#x2713;|&#x2713;|&#x2713;|String|Gets the span of active working time that is required to complete a task.|
|ActualDurationMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the span of active working time that is required to complete a task.|
|ActualDurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the span of active working time that is required to complete a task.|
|ActualOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the costs incurred for overtime work already performed on the task by assigned resources.|
|ActualOvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the actual amount of overtime work that has already been performed by resources assigned to the task.|
|ActualOvertimeWorkMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the actual amount of overtime work already performed by resources assigned to the task.|
|ActualOvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the actual amount of overtime work that has already been performed by resources assigned to the task.|
|BaselineCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total planned cost for the task.|
|BaselineDuration|&#x2713;|&#x2713;|&#x2713;|String|Gets the original span of time that is planned to complete the task, established at the time of the project baseline. (Inherited from Task.|
|BaselineDurationMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the original span of time that is planned to complete the task, established at the time of the project baseline.|
|BaselineDurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the original span of time that is planned to complete the task, established at the time of the project baseline.|
|BaselineFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the planned task completion date that was set at the time that the baseline was saved.|
|BaselineStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the planned task start date that was set at the time that the baseline was saved.|
|BaselineWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total planned person-hours that are scheduled for a task, as established at the time of the project baseline.|
|BaselineWorkMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the total planned person-hours that are scheduled for the task, as established at the time of the project baseline.|
|BaselineWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the total planned person-hours that are scheduled for the task, as established at the time of the project baseline.|
|BudgetCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budget costs for budget cost resources.|
|BudgetedCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost of work that has been performed (BCWP) on the task to date.|
|BudgetedCostWorkScheduled|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost of work that is scheduled (BCWS) for the task.|
|Contact|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the individual who is responsible for a task.|
|CostPerformanceIndex|&#x2713;|&#x2713;|&#x2713;|Double|Gets the ratio of the baseline costs of work that has been performed on the task to the actual costs of work that has been performed, calculated up to the project status date or today's date.|
|CostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and the total cost for the task.|
|CostVarianceAtCompletion|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and the total cost at the completion of the task.|
|CostVariancePercentage|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the ratio of cost variance (CV) to the budgeted cost of work that has been performed on the task (BCWP), expressed as a percentage.|
|Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and the time when the task was added to the project.|
|CurrentCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and the actual cost of the task to date.|
|CustomFields|&#x2713;|&#x2713;|&#x2713;|CustomFieldCollection|Gets the collection of custom fields for the task.|
|DurationVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the difference between the baseline duration of the task and the total duration, or current estimated duration, of the task.|
|DurationVarianceMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, of the difference between the baseline duration of the task and the total duration, or current estimated duration, of the task.|
|DurationVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the difference between the baseline duration of the task and the total duration, or current estimated duration, of the task.|
|EarliestFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the earliest date that the task could possibly finish, based on the early finish dates of predecessor and successor tasks, other constraints, and any leveling delay.|
|EarliestStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the earliest date that the task could possibly begin, based on the early start dates of predecessor and successor tasks and other constraints.|
|EstimateAtCompletion|&#x2713;|&#x2713;|&#x2713;|Double|Gets the estimate at completion (EAC) for the task.|
|FinishSlack|&#x2713;|&#x2713;|&#x2713;|String|Gets the duration between the EarlyFinish date and theLateFinish date.|
|FinishSlackMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|FinishSlackTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|FinishVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the time that represents the difference between the baseline finish date of the task and the current finish date.|
|FinishVarianceMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, of the variance of the finish date of the task.|
|FinishVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the variance of the finish date of the task.|
|FixedCostAccrual|&#x2713;|&#x2713;|&#x2713;|FixedCostAccrual|Gets the cost accrual method for how and when fixed costs are to be charged, or accrued, to the cost of the task.|
|FreeSlack|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that the task can be delayed without delaying successor tasks.|
|FreeSlackMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, of the amount of time that the task can be delayed without delaying successor tasks.|
|FreeSlackTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the amount of time that the task can be delayed without delaying successor tasks.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the task.|
|IgnoreResourceCalendar|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the resource calendar is ignored when scheduling a task. True indicates the calendar is not used. False indicates that both the resource calendar and task calendar (if defined) are used when scheduling the task.|
|IsCritical|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the timing for the task is critical or whether there can be any slack in the timing.|
|IsEffortDriven|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the scheduling of the task is effort-driven.|
|IsExternalTask|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether this is a ghost task from another project created by Project Professional.|
|IsOverAllocated|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is overallocated.|
|IsRecurring|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is part of a recurring series.|
|IsRecurringSummary|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is the parent of a recurring series.|
|IsRolledUp|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether information on the subtask Gantt bars is rolled up to the summary task bar.|
|IsSubProject|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task represents a subproject.|
|IsSubProjectReadOnly|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether a subproject for this task is read-only.|
|IsSubProjectScheduledFromFinish|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether a subproject for this task is set to schedule from finish.|
|IsSummary|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is a summary task.|
|LatestFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the latest date that the task can finish without delaying the finish of the project.|
|LatestStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the latest date that the task can start without delaying the finish of the project.|
|LevelingDelay|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that leveling can delay the task from its early start.|
|LevelingDelayMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the amount of time that leveling can delay the task from its early start.|
|LevelingDelayTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time that leveling can delay the task from its early start.|
|Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the modified date.|
|Notes|&#x2713;|&#x2713;|&#x2713;|String|Gets the notes about the task.|
|OutlinePosition|&#x2713;|&#x2713;|&#x2713;|String|Gets the position of the task in the project outline hierarchy.|
|OvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total overtime cost for the task.|
|OvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of overtime scheduled to be performed on the task.|
|OvertimeWorkMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the amount of overtime scheduled to be performed on the task.|
|OvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the amount of overtime scheduled to be performed on the task.|
|PercentWorkComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the current status of the task, expressed as the percentage of work that has been completed.|
|PreLevelingFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the finish date of the task as it was before resource leveling was performed.|
|PreLevelingStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the start date of the task as it was before resource leveling was performed.|
|RegularWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total amount of non-overtime work that is scheduled to be performed on the task.|
|RegularWorkMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the total amount of non-overtime work that is scheduled to be performed on the task.|
|RegularWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the total amount of non-overtime work that is scheduled to be performed on the task.|
|RemainingCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the remaining scheduled expense that will be incurred during completion of the remaining scheduled work on the task.|
|RemainingOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the remaining scheduled overtime expense for the task.|
|RemainingOvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time, such as person-hours or days, that is required to complete the remaining overtime work for a task.|
|RemainingOvertimeWorkMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the amount of time, such as person-hours or days, that is required to complete the remaining overtime work for a task.|
|RemainingOvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the amount of time, such as person-hours or days, that is required to complete the remaining overtime work for a task.|
|RemainingWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the time, such as person-hours or days, that is required to complete the task or set of tasks.|
|RemainingWorkMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the time, such as person-hours or days, that is required to complete the task or set of tasks.|
|RemainingWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the time, such as person-hours or days, that is required to complete the task or set of tasks.|
|Resume|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date that the remaining part of the task is scheduled to resume after progress is entered.|
|ScheduleCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference in cost terms between the current progress and the baseline planned progress for a resource on the task.|
|SchedulePerformanceIndex|&#x2713;|&#x2713;|&#x2713;|Double|Gets the ratio of the budgeted cost of work performed to the budgeted cost of work scheduled.|
|ScheduleVariancePercentage|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the ratio of schedule variance (SV) to budgeted cost of work scheduled (BCWS), expressed as a percentage.|
|ScheduledDuration|&#x2713;|&#x2713;|&#x2713;|String|Gets the total span of active working time for the task as entered or as calculated based on the start date, the finish date, calendars, and other scheduling factors.|
|ScheduledDurationMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the total span of active working time for the task as entered or as calculated based on the start date, the finish date, calendars, and other scheduling factors.|
|ScheduledDurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total span of active working time for the task as entered or as calculated based on the start date, the finish date, calendars, and other scheduling factors.|
|ScheduledFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when work on the task is scheduled to be complete as it was calculated based on the start date, the duration, dependencies, calendars, and other scheduling factors.|
|ScheduledStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when work on the task is scheduled to begin as it was calculated based on dependencies, constraints, calendars, and other scheduling factors.|
|StartSlack|&#x2713;|&#x2713;|&#x2713;|String|Gets the duration between the EarlyStart date and theLateStart date.|
|StartSlackMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the duration between the EarlyStart date and theLateStart date.|
|StartSlackTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the duration between the EarlyStart date and theLateStart date.|
|StartVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the time that represents the difference between a baseline start date of the task and its currently scheduled start date.|
|StartVarianceMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the variance of the task start date.|
|StartVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the variance of the task start date.|
|Stop|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date that represents the end of the actual portion of the task.|
|SubProject|&#x2713;|&#x2713;|&#x2713;|PublishedProject|Gets a project that has been inserted into the master project.|
|TaskType|&#x2713;|&#x2713;|&#x2713;|TaskType|Gets the task type.|
|ToCompletePerformanceIndex|&#x2713;|&#x2713;|&#x2713;|Double|Gets the To Complete Performance Index for the task.|
|TotalSlack|&#x2713;|&#x2713;|&#x2713;|String|Gets the time that the task's finish date can be delayed without delaying the project's finish date.|
|TotalSlackMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the amount of time that the task finish date can be delayed without delaying the project's finish date.|
|TotalSlackTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the amount of time that the task finish date can be delayed without delaying the project's finish date.|
|WorkBreakdownStructure|&#x2713;|&#x2713;|&#x2713;|String|Gets a code that identifies a location in a hierarchical structure that is used to organize tasks for reporting schedules and tracking costs.|
|WorkVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the difference between baseline work and currently scheduled work on a task, expressed as, for example, the number of person-hours or days.|
|WorkVarianceMilliseconds||&#x2713;|&#x2713;|Double|Gets the time interval, expressed in milliseconds, for the difference between baseline work and currently scheduled work on the task.|
|WorkVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval for the difference between baseline work and currently scheduled work on the task.|


### Methods

The  **Task** object has no methods.


