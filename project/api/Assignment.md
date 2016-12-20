
[comment]: # (Name:Assignment)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)


# <a name="name"></a>Assignment class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Contains the common properties for draft assignments and published assignments.

## <a name="syntax"></a>Syntax


### CSOM

```C#
class Assignment 
```
### JSOM

```
PS.Assignment
```
### REST Interface

Supported.  Please see REST Interface in [PublishedAssignment](PublishedAssignment.md#syntax).


## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="ActualCostWorkPerformed">ActualCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double|Gets the actual cost of work performed (ACWP) for the assignment to date.|
|<a name="ActualOvertimeCost">ActualOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the actual overtime cost for the assignment.|
|<a name="BaselineCost">BaselineCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total planned costs of the assignment.|
|<a name="BaselineCostPerUse">BaselineCostPerUse|&#x2713;|&#x2713;|&#x2713;|Double|Gets the cost per use of a resource on an assignment, at the time of the project baseline.|
|<a name="BaselineFinish">BaselineFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the planned completion date for an assignment, at the time of the project baseline.|
|<a name="BaselineStart">BaselineStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the planned start date for an assignment, at the time of the project baseline.|
|<a name="BaselineWork">BaselineWork|&#x2713;|&#x2713;|&#x2713;|String|Gets total planned person-hours scheduled for an assignment, at the time of the project baseline.|
|<a name="BaselineWorkMilliseconds">BaselineWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the total time in milliseconds, of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|<a name="BaselineWorkTimeSpan">BaselineWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|<a name="BudgetedCostWorkPerformed">BudgetedCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost of work performed (BCWP).|
|<a name="BudgetedCostWorkScheduled">BudgetedCostWorkScheduled|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost of work scheduled (BCWS) for the assignment.|
|<a name="CostVariance">CostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the cost variance (CV), which is the difference between the baseline cost and the total cost of the assignment.|
|<a name="CostVarianceAtCompletion">CostVarianceAtCompletion|&#x2713;|&#x2713;|&#x2713;|Double|Gets the cost variance at completion (VAC) for the assignment.|
|<a name="Created">Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the assignment was created.|
|<a name="CurrentCostVariance">CurrentCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the current cost variance (CV).|
|<a name="CustomFields">CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets the collection of custom fields for the assignment.|
|<a name="Delay">Delay|&#x2713;|&#x2713;|&#x2713;|String|Specifies the amount of time (formatted) that the resource is to wait after the task start date, before starting work on the task.|
|<a name="DelayMilliseconds">DelayMilliseconds||&#x2713;|&#x2713;|Integer|Specifies the amount of time in milliseconds, that the resource is to wait after the task start date, before starting work on the task.|
|<a name="DelayTimeSpan">DelayTimeSpan|&#x2713;||&#x2713;|TimeSpan|Specifies the time interval that the resource is to wait after the task start date, before starting work on the task.|
|<a name="Finish">Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Specifies the date and time that this resource is scheduled to finish this task.|
|<a name="FinishVariance">FinishVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the variance of the finish date of the assignment.|
|<a name="FinishVarianceMilliseconds">FinishVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the variance of the finish date of the assignment.|
|<a name="FinishVarianceTimeSpan">FinishVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the variance of the finish date of the assignment.|
|<a name="Id">Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the assignment.|
|<a name="IsConfirmed">IsConfirmed|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that shows whether the resource has accepted the assignment.|
|<a name="IsOverAllocated">IsOverAllocated|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the resource is overallocated during the time of the assignment.|
|<a name="IsPublished">IsPublished|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the assignment is published.|
|<a name="IsResponsePending">IsResponsePending|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that shows whether the assignment update has been sent to the resource.|
|<a name="IsUpdateNeeded">IsUpdateNeeded|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether an assignment update should be sent to the resource.|
|<a name="LevelingDelay">LevelingDelay|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that resource leveling can delay the assignment from its early start date.|
|<a name="LevelingDelayMilliseconds">LevelingDelayMilliseconds||&#x2713;|&#x2713;|Integer|	Gets the time interval, expressed in milliseconds, for the amount of time that resource leveling can delay the assignment from its early start date.|
|<a name="LevelingDelayTimeSpan">LevelingDelayTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time that resource leveling can delay the assignment from its early start date.|
|<a name="Modified">Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the assignment was modified.|
|<a name="Notes">Notes|&#x2713;|&#x2713;|&#x2713;|String|Specifies the notes that are entered in the assignment details.|
|<a name="OvertimeCost">OvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total overtime cost of the assignment.|
|<a name="RemainingCost">RemainingCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total remaining cost of the assignment, as scheduled.|
|<a name="RemainingOvertimeCost">RemainingOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the scheduled remaining overtime cost of the assignment.|
|<a name="Resume">Resume|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when a resource resumes work on the assignment.|
|<a name="ScheduleCostVariance">ScheduleCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the schedule cost variance (CV), which is the difference between the baseline cost and the scheduled cost of the assignment.|
|<a name="Start">Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time that a resource is scheduled to start the assignment.|
|<a name="StartVariance">StartVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the variance of the assignment start date.|
|<a name="StartVarianceMilliseconds">StartVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the variance of the assignment start date.|
|<a name="StartVarianceTimeSpan">StartVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the variance of the assignment start date.|
|<a name="Stop">Stop|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when a resource stops work on the assignment.|
|<a name="WorkContourType">WorkContourType|&#x2713;|&#x2713;|&#x2713;|[WorkContourType](WorkContourType.md)|Indicates how to distribute work for an assignment across the duration of the assignment.|
|<a name="WorkVariance">WorkVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the difference between baseline work and currently scheduled work on the assignment.|
|<a name="WorkVarianceMilliseconds">WorkVarianceMilliseconds||&#x2713;|&#x2713;|Integer||
|<a name="WorkVarianceTimeSpan">WorkVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the difference between baseline work and currently scheduled work on the assignment.|






## <a name="seeAlso"></a>See Also

[DraftAssignment](DraftAssignment.md)<br/>
[PublishedAssignment](PublishedAssignment.md)<br/>
