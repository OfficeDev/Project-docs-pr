
# Assignment class
Contains inheritable properties common to draft and published assignments.

## Syntax

### CSOM

```C#
Class Assignment 
```

### JSOM

```
PS.Assignment
```

### REST Interface

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Assignments('assignmentid')
```

This resource supports GET HTTP command.

## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ActualCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the actual cost of work performed (ACWP) for the assignment to date.|
|ActualOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the actual overtime cost for the assignment.|
|BaselineCost|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the total planned costs of the assignment.|
|BaselineCostPerUse|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the cost per use of a resource on an assignment, at the time of the project baseline.|
|BaselineFinish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the planned completion date for an assignment, at the time of the project baseline.|
|BaselineStart|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the planned start date for an assignment, at the time of the project baseline.|
|BaselineWork|&#x2713;|&#x2713;|&#x2713;|String|Gets total planned person-hours scheduled for an assignment, at the time of the project baseline.|
|BaselineWorkMilliseconds||&#x2713;|&#x2713;|Double (64-bit)|Gets the total time interval, expressed in milliseconds, of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|BaselineWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the total time interval of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|BudgetedCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the budgeted cost of work performed (BCWP).|
|BudgetedCostWorkScheduled|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the budgeted cost of work scheduled (BCWS) for the assignment.|
|CostVariance|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the cost variance (CV), which is the difference between the baseline cost and the total cost of the assignment.|
|CostVarianceAtCompletion|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the cost variance at completion (VAC) for the assignment.|
|Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the assignment was created.|
|CurrentCostVariance|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the current cost variance (CV).|
|CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](39c70b02-09d2-d60e-94d9-ea538846124a.md)|Gets the collection of custom fields for the assignment.|
|Delay|&#x2713;&#x22C6;|&#x2713;&#x22C6;|&#x2713;&#x22C6;|String| |
|DelayMilliseconds||&#x2713;&#x22C6;|&#x2713;&#x22C6;|Double (64-bit)| |
|DelayTimeSpan|&#x2713;&#x22C6;||&#x2713;&#x22C6;|TimeSpan| |
|Finish|&#x2713;&#x22C6;|&#x2713;&#x22C6;|&#x2713;&#x22C6;|DateTime| |
|FinishVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the variance of the finish date of the assignment.|
|FinishVarianceMilliseconds||&#x2713;|&#x2713;|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the variance of the finish date of the assignment.|
|FinishVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the variance of the finish date of the assignment.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the assignment.|
|IsConfirmed|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that shows whether the resource has accepted the assignment.|
|IsOverAllocated|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the resource is overallocated during the time of the assignment.|
|IsPublished|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the assignment is published.|
|IsResponsePending|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that shows whether the assignment update has been sent to the resource.|
|IsUpdateNeeded|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether an assignment update should be sent to the resource.|
|LevelingDelay|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that resource leveling can delay the assignment from its early start date.|
|LevelingDelayMilliseconds||&#x2713;|&#x2713;|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of time that resource leveling can delay the assignment from its early start date.|
|LevelingDelayTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time that resource leveling can delay the assignment from its early start date.|
|Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the assignment was modified.|
|Notes|&#x2713;&#x22C6;|&#x2713;&#x22C6;|&#x2713;&#x22C6;|String| |
|OvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the total overtime cost of the assignment.|
|RemainingCost|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the total remaining cost of the assignment, as scheduled.|
|RemainingOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the scheduled remaining overtime cost of the assignment.|
|Resume|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when a resource resumes work on the assignment.|
|ScheduleCostVariance|&#x2713;|&#x2713;|&#x2713;|Double (64-bit)|Gets the schedule cost variance (CV), which is the difference between the baseline cost and the scheduled cost of the assignment.|
|Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time that a resource is scheduled to start the assignment.|
|StartVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the variance of the assignment start date.|
|StartVarianceMilliseconds||&#x2713;|&#x2713;|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the variance of the assignment start date.|
|StartVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the variance of the assignment start date.|
|Stop|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when a resource stops work on the assignment.|
|WorkContourType|&#x2713;&#x22C6;|&#x2713;&#x22C6;|&#x2713;&#x22C6;|WorkContourType| |
|WorkVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the difference between baseline work and currently scheduled work on the assignment.|
|WorkVarianceMilliseconds||&#x2713;|&#x2713;|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the difference between baseline work and currently scheduled work on the assignment.|
|WorkVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the difference between baseline work and currently scheduled work on the assignment.|


### Methods

The **Assignment** object has no methods.



