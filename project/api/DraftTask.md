[comment]: # (Name:DraftTask)
[comment]: # (Name:Microsoft.ProjectServer.DraftTask)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>DraftTask class

inherits members from [Task](Task.md)<br/>

<a name="description"></a>Represents a task in a checked-out project.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class DraftTask 
```
### JSOM

```javascript
PS.DraftTask
```

### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE,  and DELETE HTTP commands.

```
PS.DraftTask

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Draft/Tasks('{taskid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the draft task.|
|<a name="ActualCost"></a>ActualCost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or set costs incurred for work already performed on a task, together with any other recorded costs that are associated with a task.|
|<a name="ActualFinish"></a>ActualFinish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a date and time when a task is complete.|
|<a name="ActualStart"></a>ActualStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a date and time that a task actually began, based on progress information that has been entered.|
|<a name="ActualWork"></a>ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of work that has already been performed on a task.|
|<a name="ActualWorkMilliseconds"></a>ActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of work that has already been performed on a task.|
|<a name="ActualWorkTimeSpan"></a>ActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of work that has already been performed on a task.|
|<a name="AddAfterId"></a>AddAfterId|||&#x2713;|Guid|Id of the task that immediately precedes the current task.|
|<a name="Assignments"></a>Assignments|&#x2713;|&#x2713;|&#x2713;|[DraftAssignmentCollection](DraftAssignmentCollection.md)|Gets the assignments for a task.|
|<a name="BudgetWork"></a>BudgetWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of work that is estimated to be performed on a task.|
|<a name="BudgetWorkMilliseconds"></a>BudgetWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of work that is estimated to be performed on a task.|
|<a name="BudgetWorkTimeSpan"></a>BudgetWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of work that is estimated to be performed on a task.|
|<a name="Calendar"></a>Calendar|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[Calendar](Calendar.md)|Gets or sets the task calendar.|
|<a name="Completion"></a>Completion|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a completion date for a task.|
|<a name="ConstraintStartEnd"></a>ConstraintStartEnd|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a constraint start date or end date for a task.|
|<a name="ConstraintType"></a>ConstraintType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[ConstraintType](ConstraintType.md)|Gets or sets the time constraint type for a task.|
|<a name="Cost"></a>Cost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the total scheduled or projected cost based on costs already incurred for work performed on a task, in addition to the costs planned for the remaining work.|
|<a name="Deadline"></a>Deadline|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date that was entered as a deadline for a task.|
|<a name="Duration"></a>Duration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of time that it takes to complete a task.|
|<a name="DurationMilliseconds"></a>DurationMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of time that it takes to complete a task.|
|<a name="DurationTimeSpan"></a>DurationTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of time that it takes to complete a task.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the draft task.|
|<a name="Finish"></a>Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a task finish date.|
|<a name="FinishText"></a>FinishText|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets a string representation of the task finish date.|
|<a name="FixedCost"></a>FixedCost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets any non-resource task expense.|
|<a name="IsActive"></a>IsActive|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a task is active.|
|<a name="IsLockedByManager"></a>IsLockedByManager|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a task has been locked for changes by a manager.|
|<a name="IsManual"></a>IsManual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a task is manually scheduled.|
|<a name="IsMarked"></a>IsMarked|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a task has been marked as having special meaning.|
|<a name="IsMilestone"></a>IsMilestone|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a task is a milestone.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the draft task.|
|<a name="LevelingAdjustsAssignments"></a>LevelingAdjustsAssignments|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether leveling can delay or split assignments (rather than the task itself) to resolve overallocations.|
|<a name="LevelingCanSplit"></a>LevelingCanSplit|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether leveling can interrupt and split a task.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of a task.|
|<a name="OutlineLevel"></a>OutlineLevel|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the task outline level in a hierarchical task list.|
|<a name="Parent"></a>Parent|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Gets the parent task.|
|<a name="ParentId"></a>ParentId|||&#x2713;|Guid|Gets the Guid of the parent task in a hierarchical task list.|
|<a name="PercentComplete"></a>PercentComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the percent of duration completed on a task.|
|<a name="PercentPhysicalWorkComplete"></a>PercentPhysicalWorkComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the percentage of physical work completed on a task.|
|<a name="Predecessors"></a>Predecessors|&#x2713;|&#x2713;|&#x2713;|[DraftTaskLinkCollection](DraftTaskLinkCollection.md)|Gets the links to the predecessor tasks that the current task depends on.|
|<a name="Priority"></a>Priority|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the task priority.|
|<a name="RemainingDuration"></a>RemainingDuration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the remaining task duration.|
|<a name="RemainingDurationMilliseconds"></a>RemainingDurationMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the remaining task duration.|
|<a name="RemainingDurationTimeSpan"></a>RemainingDurationTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the remaining task duration.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the task start date.|
|<a name="StartText"></a>StartText|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets a string representation of the task start date.|
|<a name="StatusManager"></a>StatusManager|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)||
|<a name="Successors"></a>Successors|&#x2713;|&#x2713;|&#x2713;|[DraftTaskLinkCollection](DraftTaskLinkCollection.md)|Gets links to tasks that depend on the current task.|
|<a name="UsePercentPhysicalWorkComplete"></a>UsePercentPhysicalWorkComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether to use PercentPhysicalWorkComplete orPercentComplete to compute earned value.|
|<a name="Work"></a>Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total time scheduled for a task.|
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the total time scheduled for a task.|
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total time scheduled for a task.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the draft task object.|
|[SetCustomFieldValue(String fieldName, Object value)](#SetCustomFieldValue_String_fieldName,_Object_value_)|&#x2713;|&#x2713;||void|Sets a custom field on the draft task.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()

Deletes the draft task object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

#### <a name="SetCustomFieldValue_String_fieldName,_Object_value_"></a>SetCustomFieldValue(String fieldName, Object value)

Sets a custom field on the draft task.

##### Syntax

```
void SetCustomFieldValue(String fieldName, Object value)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name**|**Type**|**Description**|
|:------ |:----|:------ |
|fieldName|String|The [InternalName](CustomField.md#InternalName) of the custom field to update.|
|value|Object|New value of the custom field.|

##### Return Value

void

## <a name="seeAlso"></a>See Also

[DraftAssignment](DraftAssignment.md)<br/>
[DraftTaskCollection](DraftTaskCollection.md)<br/>
[DraftTaskLink](DraftTaskLink.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
[TaskCreationInformation](TaskCreationInformation.md)<br/>
