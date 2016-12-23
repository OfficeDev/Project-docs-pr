
[comment]: # (Name:Assignment)
[comment]: # (Type:class)
[comment]: # (Status:Verified)


# <a name="name"></a>Assignment class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Contains the common properties for [DraftAssignments](DraftAssignment.md) and [PublishedAssignments](PublishedAssignment.md).

## <a name="syntax"></a>Syntax


### CSOM

```C#
class Assignment 
```
### JSOM

```JavaScript
PS.Assignment
```
### REST Interface

Supported.  Please see REST Interface in [PublishedAssignment](PublishedAssignment.md#syntax).

```
PS.Assignment
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="ActualCostWorkPerformed"></a>ActualCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double|Gets the actual cost of work performed (ACWP) for the assignment to date.|
|<a name="ActualOvertimeCost"></a>ActualOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the actual overtime cost for the assignment.|
|<a name="BaselineCost"></a>BaselineCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total planned costs of the assignment.|
|<a name="BaselineCostPerUse"></a>BaselineCostPerUse|&#x2713;|&#x2713;|&#x2713;|Double|Gets the cost per use of a resource on an assignment, at the time of the project baseline.|
|<a name="BaselineFinish"></a>BaselineFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the planned completion date for an assignment, at the time of the project baseline.|
|<a name="BaselineStart"></a>BaselineStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the planned start date for an assignment, at the time of the project baseline.|
|<a name="BaselineWork"></a>BaselineWork|&#x2713;|&#x2713;|&#x2713;|String|Gets total planned person-hours scheduled for an assignment, at the time of the project baseline.|
|<a name="BaselineWorkMilliseconds"></a>BaselineWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the total time in milliseconds, of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|<a name="BaselineWorkTimeSpan"></a>BaselineWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|<a name="BudgetedCostWorkPerformed"></a>BudgetedCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost of work performed (BCWP).|
|<a name="BudgetedCostWorkScheduled"></a>BudgetedCostWorkScheduled|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost of work scheduled (BCWS) for the assignment.|
|<a name="CostVariance"></a>CostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the cost variance (CV), which is the difference between the baseline cost and the total cost of the assignment.|
|<a name="CostVarianceAtCompletion"></a>CostVarianceAtCompletion|&#x2713;|&#x2713;|&#x2713;|Double|Gets the cost variance at completion (VAC) for the assignment.|
|<a name="Created"></a>Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the assignment was created.|
|<a name="CurrentCostVariance"></a>CurrentCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the current cost variance (CV).|
|<a name="CustomFields"></a>CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets the collection of custom fields for the assignment.|
|<a name="Delay"></a>Delay|&#x2713;|&#x2713;|&#x2713;|String|Specifies the amount of time (formatted) that the resource is to wait after the task start date, before starting work on the task.|
|<a name="DelayMilliseconds"></a>DelayMilliseconds||&#x2713;|&#x2713;|Integer|Specifies the amount of time in milliseconds, that the resource is to wait after the task start date, before starting work on the task.|
|<a name="DelayTimeSpan"></a>DelayTimeSpan|&#x2713;||&#x2713;|TimeSpan|Specifies the time interval that the resource is to wait after the task start date, before starting work on the task.|
|<a name="Finish"></a>Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Specifies the date and time that this resource is scheduled to finish this task.|
|<a name="FinishVariance"></a>FinishVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the variance of the finish date of the assignment.|
|<a name="FinishVarianceMilliseconds"></a>FinishVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the variance of the finish date of the assignment.|
|<a name="FinishVarianceTimeSpan"></a>FinishVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the variance of the finish date of the assignment.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the assignment.|
|<a name="IsConfirmed"></a>IsConfirmed|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that shows whether the resource has accepted the assignment.|
|<a name="IsOverAllocated"></a>IsOverAllocated|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the resource is overallocated during the time of the assignment.|
|<a name="IsPublished"></a>IsPublished|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the assignment is published.|
|<a name="IsResponsePending"></a>IsResponsePending|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that shows whether the assignment update has been sent to the resource.|
|<a name="IsUpdateNeeded"></a>IsUpdateNeeded|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether an assignment update should be sent to the resource.|
|<a name="LevelingDelay"></a>LevelingDelay|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that resource leveling can delay the assignment from its early start date.|
|<a name="LevelingDelayMilliseconds"></a>LevelingDelayMilliseconds||&#x2713;|&#x2713;|Integer|	Gets the time interval, expressed in milliseconds, for the amount of time that resource leveling can delay the assignment from its early start date.|
|<a name="LevelingDelayTimeSpan"></a>LevelingDelayTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time that resource leveling can delay the assignment from its early start date.|
|<a name="Modified"></a>Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the assignment was modified.|
|<a name="Notes"></a>Notes|&#x2713;|&#x2713;|&#x2713;|String|Specifies the notes that are entered in the assignment details.|
|<a name="OvertimeCost"></a>OvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total overtime cost of the assignment.|
|<a name="RemainingCost"></a>RemainingCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total remaining cost of the assignment, as scheduled.|
|<a name="RemainingOvertimeCost"></a>RemainingOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the scheduled remaining overtime cost of the assignment.|
|<a name="Resume"></a>Resume|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when a resource resumes work on the assignment.|
|<a name="ScheduleCostVariance"></a>ScheduleCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the schedule cost variance (CV), which is the difference between the baseline cost and the scheduled cost of the assignment.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time that a resource is scheduled to start the assignment.|
|<a name="StartVariance"></a>StartVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the variance of the assignment start date.|
|<a name="StartVarianceMilliseconds"></a>StartVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the variance of the assignment start date.|
|<a name="StartVarianceTimeSpan"></a>StartVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the variance of the assignment start date.|
|<a name="Stop"></a>Stop|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when a resource stops work on the assignment.|
|<a name="WorkContourType"></a>WorkContourType|&#x2713;|&#x2713;|&#x2713;|[WorkContourType](WorkContourType.md)|Indicates how to distribute work for an assignment across the duration of the assignment.|
|<a name="WorkVariance"></a>WorkVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the difference between baseline work and currently scheduled work on the assignment.|
|<a name="WorkVarianceMilliseconds"></a>WorkVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the difference between baseline work and currently scheduled work on the assignment.|
|<a name="WorkVarianceTimeSpan"></a>WorkVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the difference between baseline work and currently scheduled work on the assignment.|

## <a name="seeAlso"></a>See Also

[DraftAssignment](DraftAssignment.md)<br/>
[PublishedAssignment](PublishedAssignment.md)<br/>
