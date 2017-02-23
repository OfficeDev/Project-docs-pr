[comment]: # (Name:PublishedTask)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PublishedTask class

inherits members from [Task](Task.md)<br/>

<a name="description"></a>Represents a task in a published project.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class PublishedTask 
```
### JSOM

```JavaScript
PS.PublishedTask
```
### REST Interface

This resource supports the GET and POST HTTP commands:

```
PS.PublishedTask

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Tasks('{taskid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the published task.|
|<a name="ActualCost"></a>ActualCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the costs incurred for work already performed on the task, together with any other recorded costs that are associated with the task.|
|<a name="ActualFinish"></a>ActualFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when the task is complete.|
|<a name="ActualStart"></a>ActualStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time that the task actually began, based on progress information that was entered.|
|<a name="ActualWork"></a>ActualWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of work that has already been performed by resources assigned to the task.|
|<a name="ActualWorkMilliseconds"></a>ActualWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, in milliseconds, for the amount of work that has already been performed by resources assigned to the task.|
|<a name="ActualWorkTimeSpan"></a>ActualWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of work that has already been performed by resources assigned to the task.|
|<a name="Assignments"></a>Assignments|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignmentCollection](PublishedAssignmentCollection.md)|Gets the collection of assignments for the task.|
|<a name="BudgetWork"></a>BudgetWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the budgeted work.|
|<a name="BudgetWorkMilliseconds"></a>BudgetWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the budgeted work.|
|<a name="BudgetWorkTimeSpan"></a>BudgetWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the budgeted work.|
|<a name="Calendar"></a>Calendar|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets the task calendar.|
|<a name="Completion"></a>Completion|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets a completion date for the task.|
|<a name="ConstraintStartEnd"></a>ConstraintStartEnd|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets a constraint start date or end date.|
|<a name="ConstraintType"></a>ConstraintType|&#x2713;|&#x2713;|&#x2713;|[ConstraintType](ConstraintType.md)|Gets the choices for the type of constraint that can be applied to the scheduling of a task.|
|<a name="Cost"></a>Cost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total scheduled or projected cost for the task. The cost is based on costs already incurred for work performed by resources that are assigned to the task, in addition to the costs planned for the remaining work.|
|<a name="Deadline"></a>Deadline|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date that was entered as a deadline for the task.|
|<a name="Duration"></a>Duration|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time it takes to complete a task.|
|<a name="DurationMilliseconds"></a>DurationMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of time it takes to complete a task.|
|<a name="DurationTimeSpan"></a>DurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time it takes to complete a task.|
|<a name="EntityLinks"></a>EntityLinks|||&#x2713;|[EntityLinksCollection](EntityLinksCollection.md)||
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the published task.|
|<a name="Finish"></a>Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when a task is scheduled to be completed.|
|<a name="FinishText"></a>FinishText|&#x2713;|&#x2713;|&#x2713;|String|Gets a string representation of the task finish date.|
|<a name="FixedCost"></a>FixedCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the fixed cost for the task, which is a nonresource expense.|
|<a name="IsActive"></a>IsActive|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is active.|
|<a name="IsLockedByManager"></a>IsLockedByManager|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task has been locked for changes by a manager.|
|<a name="IsManual"></a>IsManual|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is manually scheduled.|
|<a name="IsMarked"></a>IsMarked|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is marked as having special meaning.|
|<a name="IsMilestone"></a>IsMilestone|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the task is a milestone.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the published task.|
|<a name="LevelingAdjustsAssignments"></a>LevelingAdjustsAssignments|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether resource leveling can delay or split assignments (rather than the task itself) to resolve overallocations.|
|<a name="LevelingCanSplit"></a>LevelingCanSplit|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether resource leveling can interrupt and split the task.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the task.|
|<a name="OutlineLevel"></a>OutlineLevel|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the task outline level in a hierarchical task list.|
|<a name="Parent"></a>Parent|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets the parent task link.|
|<a name="PercentComplete"></a>PercentComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the current status of the task, expressed as the percentage of the task's duration that has been completed.|
|<a name="PercentPhysicalWorkComplete"></a>PercentPhysicalWorkComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the manually entered percentage of physical work completed.|
|<a name="Predecessors"></a>Predecessors|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLinkCollection](PublishedTaskLinkCollection.md)|Gets the links to predecessor tasks on which the task depends, before the current task can be started or finished.|
|<a name="Priority"></a>Priority|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the level of importance given to the task, which indicates how readily a task can be delayed or split during resource leveling.|
|<a name="RemainingDuration"></a>RemainingDuration|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that is required to complete the unfinished part of the task, which is the remaining task duration.|
|<a name="RemainingDurationMilliseconds"></a>RemainingDurationMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of time that is required to complete the unfinished part of the task.|
|<a name="RemainingDurationTimeSpan"></a>RemainingDurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time that is required to complete the unfinished part of the task, which is the remaining task duration.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when an assigned resource is scheduled to begin working on the task.|
|<a name="StartText"></a>StartText|&#x2713;|&#x2713;|&#x2713;|String|Gets a string representation of the task start date.|
|<a name="StatusManager"></a>StatusManager|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)||
|<a name="Successors"></a>Successors|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLinkCollection](PublishedTaskLinkCollection.md)|Gets a collection of links to tasks that depend on the current task.|
|<a name="UsePercentPhysicalWorkComplete"></a>UsePercentPhysicalWorkComplete|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to use PercentPhysicalWorkComplete orPercentComplete to compute earned value.|
|<a name="Work"></a>Work|&#x2713;|&#x2713;|&#x2713;|String|Gets the total time that is scheduled for all resources assigned to the task.|
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total time that is scheduled for all resources assigned to the task.|
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total time that is scheduled for all resources assigned to the task.|

## <a name="seeAlso"></a>See Also

[PublishedAssignment](PublishedAssignment.md)<br/>
[PublishedTaskCollection](PublishedTaskCollection.md)<br/>
[PublishedTaskLink](PublishedTaskLink.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
