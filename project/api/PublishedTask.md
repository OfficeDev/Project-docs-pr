
# PublishedTask
Represents a task in a published project.

[PublishedTask](PublishedTask.md) inherits properties from the [Task class](Task.md).

## Syntax

### CSOM

```
Class PublishedTask
```

### JSOM

```
PS.PublishedTask
```

### REST

This resource supports the GET and DELETE HTTP commands:

```
http://<sitecollection> /<site> /_api/ProjectServer/Tasks('taskid')
```

## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ActualCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the costs incurred for work already performed on the task, together with any other recorded costs that are associated with the task.|
|ActualFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when the task is complete.|
|ActualStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time that the task actually began, based on progress information that was entered.|
|ActualWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of work that has already been performed by resources assigned to the task.|
|ActualWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, in milliseconds, for the amount of work that has already been performed by resources assigned to the task.|
|ActualWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of work that has already been performed by resources assigned to the task.|
|Assignments|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignmentCollection](PublishedAssignmentCollection.md)|Gets the collection of assignments for the task.|
|BudgetWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the budgeted work.|
|BudgetWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the budgeted work.|
|BudgetWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the budgeted work.|
|Calendar|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets the task calendar.|
|Completion|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets a completion date for the task.|
|ConstraintStartEnd|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets a constraint start date or end date.|
|ConstraintType|&#x2713;|&#x2713;|&#x2713;|[ConstraintType](ConstraintType.md)|Gets the choices for the type of constraint that can be applied to the scheduling of a task.|
|Cost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total scheduled or projected cost for the task.|
|Deadline|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date that was entered as a deadline for the task.|
|Duration|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time it takes to complete a task.|
|DurationMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of time it takes to complete a task.|
|DurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time it takes to complete a task.|
|EntityLinks|||&#x2713;|[EntityLinkCollection](EntityLinkCollection.md)||
|FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string,object&gt;|Gets the task-associated collection of custom fields that have values set.|
|Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when a task is scheduled to be completed.|
|FinishText|&#x2713;|&#x2713;|&#x2713;|String|Gets a string representation of the task finish date.|
|FixedCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the fixed cost for the task, which is a nonresource expense.|
|IsActive|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is active.|
|IsLockedByManager|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task has been locked for changes by a manager.|
|IsManual|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is manually scheduled.|
|IsMarked|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is marked as having special meaning.|
|IsMilestone|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is a milestone.|
|Item|&#x2713;|&#x2713;||Dictionary&lt;string,object&gt;|Gets an item in the project.|
|LevelingAdjustsAssignments|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether resource leveling can delay or split assignments (rather than the task itself) to resolve overallocations.|
|LevelingCanSplit|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether resource leveling can interrupt and split the task.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the task.|
|OutlineLevel|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the task outline level in a hierarchical task list.|
|Parent|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets the parent task.|
|PercentComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the current status of the task, expressed as the percentage of the task's duration that has been completed.|
|PercentPhysicalWorkComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the manually entered percentage of physical work completed.|
|Predecessors|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLinkCollection](PublishedTaskLinkCollection.md)|Gets the links to predecessor tasks on which the task depends, before the current task can be started or finished.|
|Priority|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the level of importance given to the task, which indicates how readily a task can be delayed or split during resource leveling.|
|RemainingDuration|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that is required to complete the unfinished part of the task.|
|RemainingDurationMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of time that is required to complete the unfinished part of the task.|
|RemainingDurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time that is required to complete the unfinished part of the task.|
|Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when an assigned resource is scheduled to begin working on the task.|
|StartText|&#x2713;|&#x2713;|&#x2713;|String|Gets a string representation of the task start date.|
|StatusManager|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the enterprise resource name who receives status updates.|
|Successors|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLinkCollection](PublishedTaskLinkCollection.md)|Gets a collection of links to tasks that depend on the current task.|
|UsePercentPhysicalWorkComplete|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to compute earned value using PercentPhysicalWorkComplete orPercentComplete.|
|Work|&#x2713;|&#x2713;|&#x2713;|String|Gets the total time that is scheduled for all resources assigned to the task.|
|WorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total time that is scheduled for all resources assigned to the task.|
|WorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total time that is scheduled for all resources assigned to the task.|


### Methods

The  **PublishedTask** object has no methods.

## See Also

[Task class](Task.md) <br />
[DraftTask class](DraftTask.md)
