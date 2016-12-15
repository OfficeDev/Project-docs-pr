
# StatusAssignment

Provides an object that is an assignment in a status update.


## Syntax

### CSOM

```
Class StatusAssignment 
```
### JSOM

```
PS.StatusAssignment
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/EnterpriseResources('resourceid')/Assignments('assignmentid')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ActualFinish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time when an assignment was completed.|
|ActualOvertime|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the actual amount of overtime work already performed by resources that are assigned to tasks.|
|ActualOvertimeMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the actual amount of overtime work already performed by resources that are assigned to tasks.|
|ActualOvertimeTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the actual amount of overtime work already performed by resources that are assigned to tasks.|
|ActualStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time that an assignment actually began, based on progress information that was entered.|
|ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of work that has already been performed by resources that are assigned to tasks.|
|ActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of work that has already been performed by resources that are assigned to tasks.|
|ActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of work that has already been performed by resources that are assigned to tasks.|
|ApprovalStatus|&#x2713;|&#x2713;|&#x2713;|[StatusApprovalType](StatusApprovalType.md)|Gets **resource manager approval state** of the assignments for which the project manager should be notified of edits.|
|Comments|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the comments for the status assignment.|
|CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets the collection of custom fields that have values set for the status assignment.|
|FieldValues|&#x2713;|&#x2713;| |Dictionary&lt;string, Object&gt;|Gets the custom field values for the status assignment. |
|Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when an assignment is scheduled to be completed.|
|History|&#x2713;|&#x2713;|&#x2713;|[StatusAssignmentHistoryLineCollection](StatusAssignmentHistoryLineCollection.md)|Gets historical information about the assignment.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID for the status assignment.|
|IsConfirmed|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets whether the status assignment has been confirmed.|
|Item|&#x2713;&#x02B7;|&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the StatusAssignment.|
|Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets or sets the date and time that the status assignment was last updated.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the status assignment.|
|Overtime|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of overtime work.|
|OvertimeMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of overtime work.|
|OvertimeTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of overtime work.|
|PercentComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the current status of a task, resource, or assignment, expressed as the percentage of work that has been completed.|
|Project|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Gets the project that contains the status assignment.|
|RegularWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total amount of nonovertime work that is scheduled to be performed by resources.|
|RegularWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the total amount of nonovertime work that is scheduled to be performed by resources.|
|RegularWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total amount of nonovertime work that is scheduled to be performed by resources.|
|RemainingOvertime|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of remaining scheduled overtime work.|
|RemainingOvertimeMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of remaining scheduled overtime work.|
|RemainingOvertimeTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of remaining scheduled overtime work.|
|RemainingWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the time, such as person-hours or days, that are still required to complete a task or set of tasks.|
|RemainingWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the time, such as person-hours or days, that are still required to complete a task or set of tasks.|
|RemainingWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the time, such as person-hours or days, that are still required to complete a task or set of tasks.|
|Resource|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets the resource that is associated with the status assignment.|
|Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when an assigned resource is scheduled to begin working on an assignment.|
|Task|&#x2713;|&#x2713;|&#x2713;|[StatusTask](StatusTask.md)|Gets the task that is associated with the status assignment.|
|Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total time scheduled on a task for all assigned resources.|
|WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the total time scheduled on a task for all assigned resources.|
|WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total time scheduled on a task for all assigned resources.|

### Methods

|Name|CSOM|JSOM|REST|Return Type|Description|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#deleteobject)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the [StatusAssignment](StatusAssignment.md) object.|
|[SetCustomFieldValue(String fieldName, Object value)](#setcustomfieldvalue)|&#x2713;|&#x2713;||void|Updates the value of a custom field associated with the status assignment.|
|[SubmitStatusUpdates(String comment)](#submitstatusupdates)|&#x2713;|&#x2713;|&#x2713;|void|Submits all updates to this assignment for approval.|


## Method Details


### <a name="deleteobject"></a> DeleteObject()

Deletes the [StatusAssignment](StatusAssignment.md) object.

#### Syntax

```
DeleteObject()
```

#### Parameters

none

#### Return value

void



### <a name="setcustomfieldvalue"></a>SetCustomFieldValue(String fieldName, Object value)
 
Updates the value of a custom field associated with the status assignment.

#### Syntax

```
SetCustomFieldValue(String fieldName, Object value)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|fieldName| String | Name of the custom field to update. |
|value| Object | New value of the custom field.| 

#### Return Value

void



### <a name="submitstatusupdates"></a> SubmitStatusUpdates(String comment)

Submits all updates to this assignment for approval.

#### Syntax

```
SubmitStatusUpdates(String comment)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|comment| String|A comment about the submission.|

#### Return value

void

<!-- Can remove comment marks when see also becomes relevant.  
## See Also
 -->