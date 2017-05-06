[comment]: # (Name:DraftAssignment)
[comment]: # (Name:Microsoft.ProjectServer.DraftAssignment)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>DraftAssignment class

inherits members from [Assignment](Assignment.md)<br/>

<a name="description"></a>Represents an [Assignment](Assignment.md) in a project that is checked out or yet to be published and enables the creation of a assignments for a project.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class DraftAssignment 
```

### JSOM

```javascript
PS.DraftAssignment
```

### REST Interface

This resource supports GET, POST, and DELETE HTTP commands.

```
PS.DraftAssignment

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Draft/Assignments('{assignmentid}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the draft assignment.|
|<a name="ActualCost"></a>ActualCost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the costs incurred for work already performed on the assignment, together with any other recorded costs that are associated with the assignment.|
|<a name="ActualFinish"></a>ActualFinish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time when the assignment is complete.|
|<a name="ActualOvertimeWork"></a>ActualOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the actual amount of overtime work that has already been performed on the assignment.|
|<a name="ActualOvertimeWorkMilliseconds"></a>ActualOvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval in milliseconds, for the actual amount of overtime work that has already been performed on the assignment|
|<a name="ActualOvertimeWorkTimeSpan"></a>ActualOvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the actual amount of overtime work that has already been performed on the assignment|
|<a name="ActualStart"></a>ActualStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time that the assignment actually began, based on progress information that was entered.|
|<a name="ActualWork"></a>ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of work that has already been performed on the assignment.|
|<a name="ActualWorkMilliseconds"></a>ActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the actual amount of overtime work that has already been performed on the assignment.|
|<a name="ActualWorkTimeSpan"></a>ActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of work that has already been performed on the assignment.|
|<a name="BudgetedCost"></a>BudgetedCost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the budgeted cost for the assignment.|
|<a name="BudgetedWork"></a>BudgetedWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the budgeted work for the assignment.|
|<a name="BudgetedWorkMilliseconds"></a>BudgetedWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the budgeted work for the assignment.|
|<a name="BudgetedWorkTimeSpan"></a>BudgetedWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the budgeted work for the assignment.|
|<a name="Cost"></a>Cost|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the total scheduled or projected cost for the assignment.|
|<a name="CostRateTable"></a>CostRateTable|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CostRateTableName](CostRateTableName.md)|Gets or sets the cost rate table name for the assignment.|
|<a name="DefaultBookingType"></a>DefaultBookingType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[BookingType](BookingType.md)|Gets or sets the default booking type for the assignment.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the draft assignment.|
|<a name="IsLockedByManager"></a>IsLockedByManager|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the assignment has been locked for changes by a manager.|
|<a name="IsWorkResource"></a>IsWorkResource|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether an assignment resource is a work resource or a material resource.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the draft assignment.|
|<a name="OvertimeWork"></a>OvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of overtime that is scheduled to be performed on the assignment.|
|<a name="OvertimeWorkMilliseconds"></a>OvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of overtime that is scheduled to be performed on the assignment.|
|<a name="OvertimeWorkTimeSpan"></a>OvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of overtime that is scheduled to be performed on the assignment.|
|<a name="Owner"></a>Owner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets or sets the name of the user who is responsible for entering status for the current assignment.|
|<a name="Parent"></a>Parent|&#x2713;|&#x2713;|&#x2713;|[DraftAssignment](DraftAssignment.md)|Gets the parent assignment link.|
|<a name="PercentWorkComplete"></a>PercentWorkComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the amount of work that has been done on the assignment, expressed as a percentage of the total work.|
|<a name="RegularWork"></a>RegularWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|<a name="RegularWorkMilliseconds"></a>RegularWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|<a name="RegularWorkTimeSpan"></a>RegularWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|<a name="RemainingOvertimeWork"></a>RemainingOvertimeWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of remaining scheduled overtime work on the assignment.|
|<a name="RemainingOvertimeWorkMilliseconds"></a>RemainingOvertimeWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||Gets or sets the time interval for the amount of time in milliseconds, for the amount of remaining scheduled overtime work on the assignment.|
|<a name="RemainingOvertimeWorkTimeSpan"></a>RemainingOvertimeWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of remaining scheduled overtime work on the assignment.|
|<a name="RemainingWork"></a>RemainingWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of time, such as person-hours or days, that is still required to complete the assignment.|
|<a name="RemainingWorkMilliseconds"></a>RemainingWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval for the amount of time in milliseconds, that is still required to complete the assignment|
|<a name="RemainingWorkTimeSpan"></a>RemainingWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of time, such as person-hours or days, that is still required to complete the assignment|
|<a name="Resource"></a>Resource|&#x2713;|&#x2713;|&#x2713;|[DraftProjectResource](DraftProjectResource.md)|Gets the resource that is associated with the assignment.|
|<a name="ResourceCapacity"></a>ResourceCapacity|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets a value that indicates how much work the resource performs on the assignment, expressed as a percentage of the resource's theoretical full capacity.|
|<a name="ResourceId"></a>ResourceId|||&#x2713;|Guid|Gets the ResourceId that is associated with the assignment.|
|<a name="Task"></a>Task|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Gets the task to which the assignment belongs.|
|<a name="TaskId"></a>TaskId|||&#x2713;|Guid|Gets the TaskId to which the assignment belongs.|
|<a name="Work"></a>Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total amount of time that is scheduled for the assignment.|
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval in milliseconds, for the total amount of time that is scheduled for the assignment.|
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total amount of time that is scheduled for the assignment.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the draft assignment object.|
|[SetCustomFieldValue(String fieldName, Object value)](#SetCustomFieldValue_String_fieldName,_Object_value_)|&#x2713;|&#x2713;||void|Sets a custom field on the draft assignment.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the draft assignment object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

#### <a name="SetCustomFieldValue_String_fieldName,_Object_value_"></a>SetCustomFieldValue(String fieldName, Object value)
 
Sets a custom field on the draft assignment.

##### Syntax

```
void SetCustomFieldValue(String fieldName, Object value)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|fieldName|String|The [InternalName](CustomField.md#InternalName) of the custom field to update.|
|value|Object|New value of the custom field.|

##### Return Value

void

## <a name="seeAlso"></a>See Also

[AssignmentCreationInformation](AssignmentCreationInformation.md)<br/>
[DraftAssignmentCollection](DraftAssignmentCollection.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
