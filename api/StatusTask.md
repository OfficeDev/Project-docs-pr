
# StatusTask

Provides an object that keeps track of the progress of a task.

## Syntax

### CSOM

```C#
Class StatusTask 
```
### JSOM

```
PS.StatusTask
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection> /<site> /_api/ProjectServer/?????
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of work that has already been performed by resources that are assigned to tasks.|
|ActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int32|Gets or sets the time interval for the amount of work that has already been performed by resources that are assigned to tasks.|
|ActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of work that has already been performed by resources that are assigned to tasks.|
|CustomFields|&#x2713;|&#x2713;|&#x2713;|CustomFieldCollection||
|Deadline|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date that was entered as a deadline for the task.|
|Duration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total span of active working time for a task.|
|DurationMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int32|Gets or sets the time interval for the total span of active working time for a task.|
|DurationTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total span of active working time for a task.|
|FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;||
|Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when a task is scheduled to be completed.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the StatusTask object.|
|Item|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;||
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the StatusTask object.|
|Overtime|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of overtime that is scheduled to be performed by all resources that are assigned to a task, for all tasks that are assigned to a resource, or by a resource on a task, and charged at the overtime rates of the resources involved.|
|OvertimeMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int32|Gets or sets the time interval for the amount of overtime that is scheduled to be performed by all resources that are assigned to a task or by a resource on a task, and charged at the overtime rates of the resources involved.|
|OvertimeTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of overtime that is scheduled to be performed by all resources that are assigned to a task or by a resource on a task, and charged at the overtime rates of the resources involved.|
|PercentComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int16|Gets or sets the current status of a task, expressed as the percentage of the task's duration that has been completed.|
|PercentWorkComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int16|Gets or sets the current status of a task, resource, or assignment, expressed as the percentage of work that has been completed.|
|PhysicalPercentComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int16|Gets or sets the entered percent complete value that can be used as an alternative for calculating budgeted cost of work performed (BCWP).|
|ProjectTaskId|&#x2713;|&#x2713;|&#x2713;|Guid||
|RegularWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total amount of non-overtime work that is scheduled to be performed by resources.|
|RegularWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int32|Gets or sets the time interval for the total amount of non-overtime work that is scheduled to be performed by resources.|
|RegularWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total amount of non-overtime work that is scheduled to be performed by resources.|
|RemainingDuration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of time that is required to complete the unfinished part of a task.|
|RemainingDurationMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int32|Gets or sets the the amount of time that is required to complete the unfinished part of a task.|
|RemainingDurationTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the the amount of time that is required to complete the unfinished part of a task.|
|RemainingOvertime|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of remaining scheduled overtime work.|
|RemainingOvertimeMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int32|Gets or sets the time interval for the amount of remaining scheduled overtime work.|
|RemainingOvertimeTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of remaining scheduled overtime work.|
|RemainingWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of time, such as person-hours or days, that is still required to complete a task or set of tasks.|
|RemainingWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int32|Gets or sets the time interval for the amount of time, such as person-hours or days, that is still required to complete a task or set of tasks.|
|RemainingWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of time, such as person-hours or days, that is still required to complete a task or set of tasks.|
|Resume|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date that the remaining part of a task is scheduled to resume after you enter any progress.|
|Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when an assigned resource is scheduled to begin working on a task.|
|StatusManager|&#x2713;|&#x2713;|&#x2713;|SPUser||
|Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total amount of time that is scheduled on a task for all assigned resources, the total time to which a resource is scheduled on all assigned tasks, or the total amount of time scheduled for a resource on a task.|
|WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Int32|Gets or sets the time interval for the total amount of time that is scheduled on a task for all assigned resources, the total time to which a resource is scheduled on all assigned tasks, or the total amount of time scheduled for a resource on a task.|
|WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total amount of time that is scheduled on a task for all assigned resources, the total time to which a resource is scheduled on all assigned tasks, or the total amount of time scheduled for a resource on a task.|


## See Also
