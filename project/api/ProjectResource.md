
# ProjectResource class

Contains information about a project resource. The properties of ProjectResource are inheritable and common to draft and published project resources.

## Syntax

### CSOM

```
Class ProjectResource 
```

### JSOM

```
PS.ProjectResource
```

### REST Interface

This resource supports the DELETE, MERGE, and PUT HTTP commands.

```
http://<sitecollection> /<site> /_api/ProjectServer/ProjectResource('projectresourceid')
```

## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ActualCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the costs incurred for work that has been performed by the project resource, along with any other recorded costs. |
|ActualCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|String|Gets the actual cost for work that has been performed by the project resource to date. |
|ActualCostWorkPerformedMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the actual cost for work that has been performed by the project resource to date. |
|ActualCostWorkPerformedTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the actual cost for work that has been performed by the project resource to date. |
|ActualOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the actual cost incurred for overtime work that has been performed by the project resource. |
|ActualOvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the actual amount of overtime work that has been performed by the project resource. |
|ActualOvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the actual amount of overtime work that has been performed by the project resource. |
|ActualOvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the actual amount of overtime work that has been performed by the project resource. |
|ActualWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the actual amount of work that has already been performed by the project resource. |
|ActualWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the actual amount of work that has already been performed by the project resource. |
|ActualWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the actual amount of work that has already been performed by the project resource. |
|AvailableFrom|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the starting date that the project resource is available for work, at the units specified for the current time period. |
|AvailableTo|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the end date that the project resource is available for work, at the units specified for the current time period. |
|BaselineCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the planned total cost for work to be performed by the project resource. |
|BaselineWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the planned amount of work to be performed by the project resource. |
|BaselineWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the planned amount of work to be performed by the project resource. |
|BaselineWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the planned amount of work to be performed by the project resource. |
|BudetCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost for work performed by the project resource to date. |
|BudgetedCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total budgeted cost for work performed by the project resource. |
|BudgetedCostWorkScheduled|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost of scheduled work for the project resource. |
|BudgetedWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total budgeted amount of work to be performed by the project resource. |
|BudgetedWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total budgeted amount of work to be performed by the project resource. |
|BudgetedWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total budgeted amount of work to be performed by the project resource. |
|Cost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total scheduled or estimated cost for work that has been performed, and work that remains to be performed, by the project resource. |
|CostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and actual cost for the project resource. |
|CostVarianceAtCompletion|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and actual cost of the project resource at the completion of a project. |
|Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when the task was added to the project. |
|CurrentCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and the actual cost of the project resource to date. |
|CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets a collection of custom fields that have values set for this project resource. |
|EnterpriseResource|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets identification information for the project resource. |
|Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the project resource is scheduled to complete work on all assigned tasks. |
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the project resource. |
|IsBudgeted|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project resource is used for budgeting purposes or is a regular resource. |
|IsGenericResource|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project resource is a generic placeholder. |
|IsOverAllocated|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project resource is assigned to do more work on all assigned tasks than can be done within the normal working capacity. |
|Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date of modification. |
|Notes|&#x2713;|&#x2713;|&#x2713;|String|Gets comments entered about the project resource. |
|OvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total overtime cost for a project resource on all assigned tasks. |
|OvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of overtime work that is scheduled to be performed on all tasks assigned to the project resource and that is charged at the overtime rates of the project resource involved. |
|OvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of overtime work that is scheduled to be performed on all tasks assigned to the project resource and that is charged at the overtime rates of the project resource involved. |
|OvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of overtime work that is scheduled to be performed on all tasks assigned to the project resource and that is charged at the overtime rates of the project resource involved. |
|PeakWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the maximum effort that the project resource is scheduled to work on all assigned tasks. |
|PeakWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the duration of the maximum effort, expressed in milliseconds, that the project resource is scheduled to work on all assigned tasks. |
|PeakWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the duration of the maximum effort that the project resource is scheduled to work on all assigned tasks. |
|PercentWorkComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the current status of the project resource, expressed as the percentage of work that has been completed by the project resouce. |
|RegularWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total amount of non-overtime work that is scheduled to be performed by the project resource. |
|RegularWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total amount of non-overtime work that is scheduled to be performed by the project resource. |
|RegularWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total amount of non-overtime work that is scheduled to be performed by the project resource. |
|RemainingCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the remaining scheduled expense that will be incurred by the project resource in completing the remaining scheduled work. |
|RemainingOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the remaining scheduled overtime expense for the project resource. |
|RemainingOvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of remaining scheduled overtime work for the project resource. |
|RemainingOvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of remaining scheduled overtime work for the project resource. |
|RemainingOvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of remaining scheduled overtime work for the project resource. |
|RemainingWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time, such as person-hours or days, that is still required for the project resource to complete a task or set of tasks. |
|RemainingWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of time that is still required for the project resource to complete a task or set of tasks.|
|RemainingWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time, such as person-hours or days, that is still required for the project resource to complete a task or set of tasks. |
|ScheduleCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the scheduled cost variance for the project resource. |
|Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when an assigned resource is scheduled to begin working on a task. |
|Work|&#x2713;|&#x2713;|&#x2713;|String|Gets the total amount of time to which the project resource is scheduled for a task. |
|WorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total amount of time to which the project resource is scheduled for a task. |
|WorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total amount of time to which the project resource is scheduled for a task. |
|WorkVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the difference between baseline work of a project resource and the currently scheduled work. |
|WorkVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the difference between baseline work of a project resource and the currently scheduled work. |
|WorkVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the difference between baseline work of a project resource and the currently scheduled work. |


## See Also

[DraftProjectResource class](DraftProjectResource.md) <br />
[PublishedProjectResource class](PublishedProjectResource.md)

