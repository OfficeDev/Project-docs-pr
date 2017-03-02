[comment]: # (Name:PublishedAssignment)
[comment]: # (Name:Microsoft.ProjectServer.PublishedAssignment)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PublishedAssignment class

inherits members from [Assignment](Assignment.md)<br/>

<a name="description"></a>Represents the assignment that is in a published project.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PublishedAssignment 
```
### JSOM

```javascript
PS.PublishedAssignment
```

### REST Interface

This resource supports the GET HTTP command.

```
PS.PublishedAssignment

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Assignments('{assignmentid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the published assignment.|
|<a name="ActualCost"></a>ActualCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the costs incurred for work already performed on the assignment, together with any other recorded costs that are associated with the assignment.|
|<a name="ActualFinish"></a>ActualFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when the assignment is complete.|
|<a name="ActualOvertimeWork"></a>ActualOvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the actual amount of overtime work that has already been performed on the assignment.|
|<a name="ActualOvertimeWorkMilliseconds"></a>ActualOvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the actual amount of overtime work that has already been performed on the assignment.|
|<a name="ActualOvertimeWorkTimeSpan"></a>ActualOvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the actual amount of overtime work that has already been performed on the assignment.|
|<a name="ActualStart"></a>ActualStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time that the assignment actually began, based on progress information that was entered.|
|<a name="ActualWork"></a>ActualWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of work that has already been performed on the assignment.|
|<a name="ActualWorkMilliseconds"></a>ActualWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of work that has already been performed on the assignment.|
|<a name="ActualWorkTimeSpan"></a>ActualWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of work that has already been performed on the assignment.|
|<a name="BudgetedCost"></a>BudgetedCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost for the assignment.|
|<a name="BudgetedWork"></a>BudgetedWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the budgeted work for the assignment.|
|<a name="BudgetedWorkMilliseconds"></a>BudgetedWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the budgeted work for the assignment.|
|<a name="BudgetedWorkTimeSpan"></a>BudgetedWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the budgeted work for the assignment.|
|<a name="Cost"></a>Cost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total scheduled or projected cost for the assignment.|
|<a name="DefaultBookingType"></a>DefaultBookingType|&#x2713;|&#x2713;|&#x2713;|[BookingType](BookingType.md)|Gets the default booking type for the assignment.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the published assignment.|
|<a name="IsLockedByManager"></a>IsLockedByManager|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the assignment has been locked for changes by a manager.|
|<a name="IsWorkResource"></a>IsWorkResource|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether an assignment resource is a work resource or a material resource.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the published assignment.|
|<a name="OvertimeWork"></a>OvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of overtime that is scheduled to be performed on the assignment.|
|<a name="OvertimeWorkMilliseconds"></a>OvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of overtime that is scheduled to be performed on the assignment.|
|<a name="OvertimeWorkTimeSpan"></a>OvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of overtime that is scheduled to be performed on the assignment.|
|<a name="Owner"></a>Owner|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the name of the user who is responsible for entering status for the current assignment.|
|<a name="Parent"></a>Parent|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignment](PublishedAssignment.md)|Gets the parent assignment link.|
|<a name="PercentWorkComplete"></a>PercentWorkComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the current status of the assignment, expressed as the percentage of the total work that has been completed.|
|<a name="RegularWork"></a>RegularWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|<a name="RegularWorkMilliseconds"></a>RegularWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|<a name="RegularWorkTimeSpan"></a>RegularWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|<a name="RemainingOvertimeWork"></a>RemainingOvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of remaining scheduled overtime work on the assignment.|
|<a name="RemainingOvertimeWorkMilliseconds"></a>RemainingOvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of remaining scheduled overtime work on the assignment.|
|<a name="RemainingOvertimeWorkTimeSpan"></a>RemainingOvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of remaining scheduled overtime work on the assignment.|
|<a name="RemainingWork"></a>RemainingWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the time, such as person-hours or days, that is still required to complete the assignment.|
|<a name="RemainingWorkMilliseconds"></a>RemainingWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds,  for the time that is still required to complete the assignment.|
|<a name="RemainingWorkTimeSpan"></a>RemainingWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the time, such as person-hours or days, that is still required to complete the assignment.|
|<a name="Resource"></a>Resource|&#x2713;|&#x2713;|&#x2713;|[PublishedProjectResource](PublishedProjectResource.md)|Gets the resource that is associated with the assignment.|
|<a name="ResourceCapacity"></a>ResourceCapacity|&#x2713;|&#x2713;|&#x2713;|Double|Gets how much work the resource performs on the assignment, expressed as a percentage of the resource's theoretical full capacity.|
|<a name="Task"></a>Task|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets the task to which the assignment belongs.|
|<a name="Work"></a>Work|&#x2713;|&#x2713;|&#x2713;|String|Gets the total amount of time that is scheduled for the assignment.|
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total amount of time that is scheduled for the assignment.|
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total amount of time that is scheduled for the assignment.|

## <a name="seeAlso"></a>See Also

[PublishedAssignmentCollection](PublishedAssignmentCollection.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
[TimeSheetLine](TimeSheetLine.md)<br/>
