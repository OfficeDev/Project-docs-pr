
# DraftTask class
Represents a task in a checked-out project.

DraftTask inherits properties from the Task object.

## Syntax

### CSOM

```
Class DraftTask 
```

### JSOM

```
PS.DraftTask
```

### REST Interface

This resource supports the PUT, DELETE, and MERGE HTTP commands.

```
http://<sitecollection> /<site> /_api/ProjectServer/DraftTasks('taskid')
```
## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ActualCost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or set costs incurred for work already performed on a task, together with any other recorded costs that are associated with a task.|
|ActualFinish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a date and time when a task is complete.|
|ActualStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a date and time that a task actually began, based on progress information that has been entered.|
|ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of work that has already been performed on a task.|
|ActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the time interval, expressed in milliseconds, for the amount of work that has already been performed on a task.|
|ActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;|TimeSpan|Gets or sets the time interval for the amount of work that has already been performed on a task.|
|AddAfterId|||&#x2713;|Guid||
|Assignments|&#x2713;|&#x2713;|&#x2713;|DraftAssignmentCollection|Gets the assignments for a task.|
|BudgetWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of work that is estimated to be performed on a task.|
|BudgetWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the time interval, expressed in milliseconds, for the amount of work that is estimated to be performed on a task.|
|BudgetWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;|TimeSpan|Gets or sets the time interval for the amount of work that is estimated to be performed on a task.|
|Calendar|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Calendar|Gets or sets the task calendar.|
|Completion|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a completion date for a task.|
|ConstraintStartEnd|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a constraint start date or end date for a task.|
|ConstraintType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Enumeration|Gets or sets the time constraint type for a task.|
|Cost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the total scheduled or projected cost based on costs already incurred for work performed on a task, in addition to the costs planned for the remaining work.|
|Deadline|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date that was entered as a deadline for a task. |
|Duration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of time that it takes to complete a task.|
|DurationMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the time interval, expressed in milliseconds, for the amount of time that it takes to complete a task.|
|DurationTimeSpan|&#x2713;&#x02B7;||&#x2713;|TimeSpan|Gets or sets the time interval for the amount of time that it takes to complete a task.|
|FieldValues|&#x2713;|&#x2713;||Dictionary<string,object>|Gets the collection of custom fields that have values set for a task.|
|Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a task finish date.|
|FinishText|&#x22C6;&#x2713;&#x02B7;|&#x22C6;&#x2713;&#x02B7;|&#x22C6;&#x2713;&#x02B7;|String||
|FixedCost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets any non-resource task expense.|
|IsActive|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a task is active.|
|IsLockedByManager|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a task has been locked for changes by a manager.|
|IsManual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a task is manually scheduled.|
|IsMarked|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a task has been marked as having special meaning.|
|IsMilestone|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a task is a milestone.|
|Item|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x02B7;|Object|Gets or sets an item in the project.|
|LevelingAdjustsAssignments|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether leveling can delay or split assignments (rather than the task itself) to resolve overallocations.|
|LevelingCanSplit|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether leveling can interrupt and split a task.|
|Name|&#x2713;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of a task.|
|OutlineLevel|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the task outline level in a hierarchical task list.|
|Parent|&#x2713;|&#x2713;|&#x2713;|DraftTask|Gets the parent task.|
|ParentId|||&#x2713;|||
|PercentComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the percent of duration completed on a task.|
|PercentPhysicalWorkComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the percentage of physical work completed on a task.|
|Predecessors|&#x2713;|&#x2713;|&#x2713;|DraftTaskLinkCollection|Gets the links to the predecessor tasks that the current task depends on.|
|Priority|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the task priority.|
|RemainingDuration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the remaining task duration.|
|RemainingDurationMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the time interval, expressed in milliseconds, for the remaining task duration.|
|RemainingDurationTimeSpan|&#x2713;&#x02B7;||&#x2713;|TimeSpan|Gets or sets the time interval for the remaining task duration.|
|Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the task start date.|
|StartText|&#x22C6;&#x2713;&#x02B7;|&#x22C6;&#x2713;&#x02B7;|&#x22C6;&#x2713;&#x02B7;|String||
|StatusManager|&#x22C6;&#x2713;&#x02B7;|&#x22C6;&#x2713;&#x02B7;|&#x22C6;&#x2713;&#x02B7;|User (SharePoint)||
|Successors|&#x2713;|&#x2713;|&#x2713;|DraftTaskLinkCollection|Gets links to tasks that depend on the current task.|
|UsePercentPhysicalWorkComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether to use PercentPhysicalWorkComplete orPercentComplete to compute earned value.|
|Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total time scheduled for a task.|
|WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the time interval, expressed in milliseconds, for the total time scheduled for a task.|
|WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;|TimeSpan|Gets or sets the time interval for the total time scheduled for a task.|


### Methods

The  **DRaftTask** object has the following method:

|**Name**|**CSOM** |**JSOM** |**REST** |**Return Type**|**Description**|
|:----- |:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#deleteobject)|&#x2713;|&#x2713;| &#x2713;|void|Deletes the DraftTask object.|


## Method Details

### <a name="deleteobject"></a> DeleteObject() 

Deletes the DraftTask object.

#### Syntax

```
DeleteObject()
```

#### Parameters

none

#### Return value

void



