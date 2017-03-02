[comment]: # (Name:StatusTask)
[comment]: # (Name:Microsoft.ProjectServer.StatusTask)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StatusTask class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Provides an object that keeps track of the progress of a task.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StatusTask 
```
### JSOM

```javascript
PS.StatusTask
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.StatusTask

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Assignments('{assignmentid}')/Task
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the status task.|
|<a name="ActualWork"></a>ActualWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of work that has already been performed by resources that are assigned to tasks.|
|<a name="ActualWorkMilliseconds"></a>ActualWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval for the amount of work that has already been performed by resources that are assigned to tasks.|
|<a name="ActualWorkTimeSpan"></a>ActualWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of work that has already been performed by resources that are assigned to tasks.|
|<a name="CustomFields"></a>CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)||
|<a name="Deadline"></a>Deadline|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date that was entered as a deadline for the task.|
|<a name="Duration"></a>Duration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total span of active working time for a task.|
|<a name="DurationMilliseconds"></a>DurationMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval for the total span of active working time for a task.|
|<a name="DurationTimeSpan"></a>DurationTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total span of active working time for a task.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the status task.|
|<a name="Finish"></a>Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when a task is scheduled to be completed.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the StatusTask object.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the status task.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the StatusTask object.|
|<a name="Overtime"></a>Overtime|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of overtime that is scheduled to be performed by all resources that are assigned to a task, for all tasks that are assigned to a resource, or by a resource on a task, and charged at the overtime rates of the resources involved.|
|<a name="OvertimeMilliseconds"></a>OvertimeMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval for the amount of overtime that is scheduled to be performed by all resources that are assigned to a task or by a resource on a task, and charged at the overtime rates of the resources involved.|
|<a name="OvertimeTimeSpan"></a>OvertimeTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of overtime that is scheduled to be performed by all resources that are assigned to a task or by a resource on a task, and charged at the overtime rates of the resources involved.|
|<a name="PercentComplete"></a>PercentComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the current status of a task, expressed as the percentage of the task's duration that has been completed.|
|<a name="PercentWorkComplete"></a>PercentWorkComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the current status of a task, resource, or assignment, expressed as the percentage of work that has been completed.|
|<a name="PhysicalPercentComplete"></a>PhysicalPercentComplete|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the entered percent complete value that can be used as an alternative for calculating budgeted cost of work performed (BCWP).|
|<a name="ProjectTaskId"></a>ProjectTaskId|&#x2713;|&#x2713;|&#x2713;|Guid|Specifies the Guid of the published task.|
|<a name="RegularWork"></a>RegularWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total amount of non-overtime work that is scheduled to be performed by resources.|
|<a name="RegularWorkMilliseconds"></a>RegularWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval for the total amount of non-overtime work that is scheduled to be performed by resources.|
|<a name="RegularWorkTimeSpan"></a>RegularWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total amount of non-overtime work that is scheduled to be performed by resources.|
|<a name="RemainingDuration"></a>RemainingDuration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of time that is required to complete the unfinished part of a task.|
|<a name="RemainingDurationMilliseconds"></a>RemainingDurationMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the the amount of time that is required to complete the unfinished part of a task.|
|<a name="RemainingDurationTimeSpan"></a>RemainingDurationTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the the amount of time that is required to complete the unfinished part of a task.|
|<a name="RemainingOvertime"></a>RemainingOvertime|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of remaining scheduled overtime work.|
|<a name="RemainingOvertimeMilliseconds"></a>RemainingOvertimeMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval for the amount of remaining scheduled overtime work.|
|<a name="RemainingOvertimeTimeSpan"></a>RemainingOvertimeTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of remaining scheduled overtime work.|
|<a name="RemainingWork"></a>RemainingWork|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the amount of time, such as person-hours or days, that is still required to complete a task or set of tasks.|
|<a name="RemainingWorkMilliseconds"></a>RemainingWorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval for the amount of time, such as person-hours or days, that is still required to complete a task or set of tasks.|
|<a name="RemainingWorkTimeSpan"></a>RemainingWorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the amount of time, such as person-hours or days, that is still required to complete a task or set of tasks.|
|<a name="Resume"></a>Resume|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date that the remaining part of a task is scheduled to resume after you enter any progress.|
|<a name="Start"></a>Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when an assigned resource is scheduled to begin working on a task.|
|<a name="StatusManager"></a>StatusManager|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)||
|<a name="Work"></a>Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the total amount of time that is scheduled on a task for all assigned resources, the total time to which a resource is scheduled on all assigned tasks, or the total amount of time scheduled for a resource on a task.|
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the time interval for the total amount of time that is scheduled on a task for all assigned resources, the total time to which a resource is scheduled on all assigned tasks, or the total amount of time scheduled for a resource on a task.|
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the time interval for the total amount of time that is scheduled on a task for all assigned resources, the total time to which a resource is scheduled on all assigned tasks, or the total amount of time scheduled for a resource on a task.|

## <a name="seeAlso"></a>See Also

[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
[StatusAssignment](StatusAssignment.md)<br/>
