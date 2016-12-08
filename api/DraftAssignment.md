
# DraftAssignment

Represents an assignment in a project is checked out or not published yet.

DarftAssignment inherits properties and from the Assignment class.

## Syntax

### CSOM

```C#
Class DraftAssignment 
```

### JSOM

```
PS.DraftAssignment
```

### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection> /<site> /_api/ProjectServer/Projects('projectid')/Draft/Assignments('assignmentid')
```


## Members

### Properties

|**CSOM**|**CSOM**|**JSOM**|**REST**|**Data Type CSOM**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ActualCost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the costs incurred for work already performed on the assignment, together with any other recorded costs that are associated with the assignment.|
|ActualFinish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets the date and time when the assignment is complete.|
|ActualOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the actual amount of overtime work that has already been performed on the assignment.|
|ActualOvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the time interval, expressed in milliseconds, for the actual amount of overtime work that has already been performed on the assignment.|
|ActualOvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets the time interval for the actual amount of overtime work that has already been performed on the assignment.|
|ActualStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets the date and time that the assignment actually began, based on progress information that was entered.|
|ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the amount of work that has already been performed on the assignment.|
|ActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the time interval, expressed in milliseconds, for the amount of work that has already been performed on the assignment.|
|ActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets the time interval for the amount of work that has already been performed on the assignment.|
|BudgetedCost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the budgeted cost for the assignment.|
|BudgetedWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the budgeted work for the assignment.|
|BudgetedWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the time interval, expressed in milliseconds, for the budgeted work for the assignment.|
|BudgetedWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets the time interval for the budgeted work for the assignment.|
|Cost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the total scheduled or projected cost for the assignment.|
|DefaultBookingType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|BookingType  (enum)|Gets the default booking type for the assignment.|
|FieldValues|&#x2713;|&#x2713;||Dictionary<string,object>|Gets the collection of custom fields that have values set for the assignment.|
|IsLockedByManager|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets a value that indicates whether the assignment has been locked for changes by a manager.|
|IsWorkResource|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets a value that indicates whether an assignment resource is a work resource or a material resource.|
|Item|&#x2713;&#x02B7;|&#x2713;&#x02B7;||Object|Gets an item in the project.|
|OvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the amount of overtime that is scheduled to be performed on the assignment.|
|OvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the time interval, expressed in milliseconds, for the amount of overtime that is scheduled to be performed on the assignment.|
|OvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets the time interval for the amount of overtime that is scheduled to be performed on the assignment.|
|Owner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|User (SP)|Gets the name of the user who is responsible for entering status for the current assignment.|
|Parent|&#x2713;|&#x2713;|&#x2713;&#x02B7;|DraftAssignment|Gets the parent assignment link.|
|PercentWorkComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets the current status of the assignment, expressed as the percentage of the total work that has been completed.|
|RegularWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|RegularWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the time interval, expressed in milliseconds, for the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|RegularWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets the time interval for the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|RemainingOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the amount of remaining scheduled overtime work on the assignment.|
|RemainingOvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the time interval, expressed in milliseconds, for the amount of remaining scheduled overtime work on the assignment.|
|RemainingOvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets the time interval for the amount of remaining scheduled overtime work on the assignment.|
|RemainingWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the time, such as person-hours or days, that is still required to complete the assignment.|
|RemainingWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the time interval, expressed in milliseconds,  for the time that is still required to complete the assignment.|
|RemainingWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets the time interval for the time, such as person-hours or days, that is still required to complete the assignment.|
|Resource|&#x2713;|&#x2713;|&#x2713;&#x02B7;|DraftProjectResource|Gets the resource that is associated with the assignment.|
|ResourceCapacity|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets how much work the resource performs on the assignment, expressed as a percentage of the resource's theoretical full capacity.|
|Task|&#x2713;|&#x2713;|&#x2713;&#x02B7;|DraftTask|Gets the task to which the assignment belongs.|
|TaskId|||&#x2713;&#x02B7;|Guid|Gets the TaskId to which the assignment belongs.|
|Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets the total amount of time that is scheduled for the assignment.|
|WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal value|Gets the time interval, expressed in milliseconds, for the total amount of time that is scheduled for the assignment.|
|WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets the time interval for the total amount of time that is scheduled for the assignment.|


### Methods

|**Name** |**CSOM** |**JSOM** |**REST** |**Return Type** |**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:-----|
|[DeleteObject()](#deleteobject)|&#x2713;|&#x2713;|&#x2713;|   void |Deletes the draft assignment.|

## Method Details

### <a name="deleteobject"></a>DeleteObject()
 
Deletes the draft assignment.

#### Syntax

```
DeleteObject()
```

#### Parameters

none

#### Return Value

void


## See Also

[Assignment class](Assignment.md) <br />
[PublishedAssignment class](PublishedAssignment.md)

