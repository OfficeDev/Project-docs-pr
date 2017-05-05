[comment]: # (Name:StatusAssignment)
[comment]: # (Name:Microsoft.ProjectServer.StatusAssignment)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StatusAssignment class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Provides an object that is an assignment in a status update.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StatusAssignment 
```
### JSOM

```javascript
PS.StatusAssignment
```
### REST Interface

Supported.

```
PS.StatusAssignment

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Assignments('{assignmentid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the status assignment.|
|<a name="ActualFinish"></a>ActualFinish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time when an assignment was completed.|
|<a name="ActualOvertime"></a>ActualOvertime|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the actual amount of overtime work already performed by resources that are assigned to tasks.|
|<a name="ActualOvertimeMilliseconds"></a>ActualOvertimeMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the actual amount of overtime work already performed by resources that are assigned to tasks.|
|<a name="ActualOvertimeTimeSpan"></a>ActualOvertimeTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the actual amount of overtime work already performed by resources that are assigned to tasks.|
|<a name="ActualStart"></a>ActualStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time that an assignment actually began, based on progress information that was entered.|
|<a name="ActualWork"></a>ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of work that has already been performed by resources that are assigned to tasks.|
|<a name="ActualWorkMilliseconds"></a>ActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of work that has already been performed by resources that are assigned to tasks.|
|<a name="ActualWorkTimeSpan"></a>ActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of work that has already been performed by resources that are assigned to tasks.|
|<a name="ApprovalStatus"></a>ApprovalStatus|&#x2713;|&#x2713;|&#x2713;|[StatusApprovalType](StatusApprovalType.md)|Gets **resource manager approval state** of the assignments for which the project manager should be notified of edits.|
|<a name="Comments"></a>Comments|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the comments for the status assignment.|
|<a name="CustomFields"></a>CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets the collection of custom fields that have values set for the status assignment.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the status assignment.|
|<a name="Finish"></a>Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when an assignment is scheduled to be completed.|
|<a name="History"></a>History|&#x2713;|&#x2713;|&#x2713;|[StatusAssignmentHistoryLineCollection](StatusAssignmentHistoryLineCollection.md)|Gets historical comments about the assignment.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID for the status assignment.|
|<a name="IsConfirmed"></a>IsConfirmed|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets whether the status assignment has been confirmed.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the status assignment.|
|<a name="Modified"></a>Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets or sets the date and time that the status assignment was last updated.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the status assignment.|
|<a name="Overtime"></a>Overtime|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of overtime work.|
|<a name="OvertimeMilliseconds"></a>OvertimeMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of overtime work.|
|<a name="OvertimeTimeSpan"></a>OvertimeTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of overtime work.|
|<a name="PercentComplete"></a>PercentComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the current status of a task, resource, or assignment, expressed as the percentage of work that has been completed.|
|<a name="Project"></a>Project|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Gets the project that contains the status assignment.|
|<a name="RegularWork"></a>RegularWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total amount of nonovertime work that is scheduled to be performed by resources.|
|<a name="RegularWorkMilliseconds"></a>RegularWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the total amount of nonovertime work that is scheduled to be performed by resources.|
|<a name="RegularWorkTimeSpan"></a>RegularWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total amount of nonovertime work that is scheduled to be performed by resources.|
|<a name="RemainingOvertime"></a>RemainingOvertime|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of remaining scheduled overtime work.|
|<a name="RemainingOvertimeMilliseconds"></a>RemainingOvertimeMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the amount of remaining scheduled overtime work.|
|<a name="RemainingOvertimeTimeSpan"></a>RemainingOvertimeTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of remaining scheduled overtime work.|
|<a name="RemainingWork"></a>RemainingWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the time, such as person-hours or days, that are still required to complete a task or set of tasks.|
|<a name="RemainingWorkMilliseconds"></a>RemainingWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the time, such as person-hours or days, that are still required to complete a task or set of tasks.|
|<a name="RemainingWorkTimeSpan"></a>RemainingWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the time, such as person-hours or days, that are still required to complete a task or set of tasks.|
|<a name="Resource"></a>Resource|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets the resource that is associated with the status assignment.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when an assigned resource is scheduled to begin working on an assignment.|
|<a name="Task"></a>Task|&#x2713;|&#x2713;|&#x2713;|[StatusTask](StatusTask.md)|Gets the task that is associated with the status assignment.|
|<a name="Work"></a>Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total time scheduled on a task for all assigned resources.|
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval, expressed in milliseconds, for the total time scheduled on a task for all assigned resources.|
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total time scheduled on a task for all assigned resources.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the status assignment object.|
|[SetCustomFieldValue(String fieldName, Object value)](#SetCustomFieldValue_String_fieldName,_Object_value_)|&#x2713;|&#x2713;||void|Sets a custom field on the status assignment.|
|[SubmitStatusUpdates(String comment)](#SubmitStatusUpdates_String_comment_)|&#x2713;|&#x2713;|&#x2713;|void|Submits all updates to this assignment for approval.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()

Deletes the status assignment object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

#### <a name="SetCustomFieldValue_String_fieldName,_Object_value_"></a>SetCustomFieldValue(String fieldName, Object value)

Sets a custom field on the status assignment.

##### Syntax

```
void SetCustomFieldValue(String fieldName, Object value)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|fieldName|String|The [InternalName](CustomField.md#InternalName) of the custom field to update.|
|value| Object | New value of the custom field.| 

##### Return Value

void

#### <a name="SubmitStatusUpdates_String_comment_"></a>SubmitStatusUpdates(String comment)

Submits all updates to this assignment for approval.

##### Syntax

```
void SubmitStatusUpdates(String comment)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|comment| String|A comment about the submission.|

##### Return Value

void

## <a name="seeAlso"></a>See Also

[StatusAssignmentCollection](StatusAssignmentCollection.md)<br/>
[StatusAssignmentCreationInformation](StatusAssignmentCreationInformation.md)<br/>
