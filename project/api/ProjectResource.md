[comment]: # (Name:ProjectResource)
[comment]: # (Name:Microsoft.ProjectServer.ProjectResource)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectResource class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Provides information about a project resource.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectResource 
```
### JSOM

```javascript
PS.ProjectResource
```

### REST Interface

Supported.

```
PS.ProjectResource

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectId}')/ProjectResource('projectresourceid')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="ActualCost"></a>ActualCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the costs incurred for work that has been performed by the project resource, along with any other recorded costs.|
|<a name="ActualCostWorkPerformed"></a>ActualCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|String|Gets the actual cost for work that has been performed by the project resource to date.|
|<a name="ActualCostWorkPerformedMilliseconds"></a>ActualCostWorkPerformedMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the actual cost for work that has been performed by the project resource to date.|
|<a name="ActualCostWorkPerformedTimeSpan"></a>ActualCostWorkPerformedTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the actual cost for work that has been performed by the project resource to date.|
|<a name="ActualOvertimeCost"></a>ActualOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the actual cost incurred for overtime work that has been performed by the project resource.|
|<a name="ActualOvertimeWork"></a>ActualOvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the actual amount of overtime work that has been performed by the project resource.|
|<a name="ActualOvertimeWorkMilliseconds"></a>ActualOvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the actual amount of overtime work that has been performed by the project resource.|
|<a name="ActualOvertimeWorkTimeSpan"></a>ActualOvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the actual amount of overtime work that has been performed by the project resource.|
|<a name="ActualWork"></a>ActualWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the actual amount of work that has already been performed by the project resource.|
|<a name="ActualWorkMilliseconds"></a>ActualWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the actual amount of work that has already been performed by the project resource.|
|<a name="ActualWorkTimeSpan"></a>ActualWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the actual amount of work that has already been performed by the project resource.|
|<a name="AvailableFrom"></a>AvailableFrom|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the starting date that the project resource is available for work, at the units specified for the current time period.|
|<a name="AvailableTo"></a>AvailableTo|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the end date that the project resource is available for work, at the units specified for the current time period.|
|<a name="BaselineCost"></a>BaselineCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the planned total cost for work to be performed by the project resource.|
|<a name="BaselineWork"></a>BaselineWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the planned amount of work to be performed by the project resource.|
|<a name="BaselineWorkMilliseconds"></a>BaselineWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the planned amount of work to be performed by the project resource.|
|<a name="BaselineWorkTimeSpan"></a>BaselineWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the planned amount of work to be performed by the project resource.|
|<a name="BudetCostWorkPerformed"></a>BudetCostWorkPerformed|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost for work performed by the project resource to date.|
|<a name="BudgetedCost"></a>BudgetedCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total budgeted cost for work performed by the project resource.|
|<a name="BudgetedCostWorkScheduled"></a>BudgetedCostWorkScheduled|&#x2713;|&#x2713;|&#x2713;|Double|Gets the budgeted cost of scheduled work for the project resource.|
|<a name="BudgetedWork"></a>BudgetedWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total budgeted amount of work to be performed by the project resource.|
|<a name="BudgetedWorkMilliseconds"></a>BudgetedWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total budgeted amount of work to be performed by the project resource.|
|<a name="BudgetedWorkTimeSpan"></a>BudgetedWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total budgeted amount of work to be performed by the project resource.|
|<a name="Cost"></a>Cost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total scheduled or estimated cost for work that has been performed, and work that remains to be performed, by the project resource.|
|<a name="CostVariance"></a>CostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and actual cost for the project resource.|
|<a name="CostVarianceAtCompletion"></a>CostVarianceAtCompletion|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and actual cost of the project resource at the completion of a project.|
|<a name="Created"></a>Created|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time when the task was added to the project.|
|<a name="CurrentCostVariance"></a>CurrentCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the difference between the baseline cost and the actual cost of the project resource to date.|
|<a name="CustomFields"></a>CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets a collection of custom fields that have values set for this project resource.|
|<a name="EnterpriseResource"></a>EnterpriseResource|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets identification information for the project resource.|
|<a name="Finish"></a>Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when the project resource is scheduled to complete work on all assigned tasks.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the project resource.|
|<a name="IsBudgeted"></a>IsBudgeted|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project resource is used for budgeting purposes or is a regular resource.|
|<a name="IsGenericResource"></a>IsGenericResource|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project resource is a generic placeholder.|
|<a name="IsOverAllocated"></a>IsOverAllocated|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project resource is assigned to do more work on all assigned tasks than can be done within the normal working capacity.|
|<a name="Modified"></a>Modified|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date of modification.|
|<a name="Notes"></a>Notes|&#x2713;|&#x2713;|&#x2713;|String|Gets comments entered about the project resource.|
|<a name="OvertimeCost"></a>OvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total overtime cost for a project resource on all assigned tasks.|
|<a name="OvertimeWork"></a>OvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of overtime work that is scheduled to be performed on all tasks assigned to the project resource and that is charged at the overtime rates of the project resource involved.|
|<a name="OvertimeWorkMilliseconds"></a>OvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of overtime work that is scheduled to be performed on all tasks assigned to the project resource and that is charged at the overtime rates of the project resource involved.|
|<a name="OvertimeWorkTimeSpan"></a>OvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of overtime work that is scheduled to be performed on all tasks assigned to the project resource and that is charged at the overtime rates of the project resource involved.|
|<a name="PeakWork"></a>PeakWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the maximum effort that the project resource is scheduled to work on all assigned tasks.|
|<a name="PeakWorkMilliseconds"></a>PeakWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the duration of the maximum effort, expressed in milliseconds, that the project resource is scheduled to work on all assigned tasks.|
|<a name="PeakWorkTimeSpan"></a>PeakWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the duration of the maximum effort that the project resource is scheduled to work on all assigned tasks.|
|<a name="PercentWorkComplete"></a>PercentWorkComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the current status of the project resource, expressed as the percentage of work that has been completed by the project resouce.|
|<a name="RegularWork"></a>RegularWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the total amount of non-overtime work that is scheduled to be performed by the project resource.|
|<a name="RegularWorkMilliseconds"></a>RegularWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total amount of non-overtime work that is scheduled to be performed by the project resource.|
|<a name="RegularWorkTimeSpan"></a>RegularWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total amount of non-overtime work that is scheduled to be performed by the project resource.|
|<a name="RemainingCost"></a>RemainingCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the remaining scheduled expense that will be incurred by the project resource in completing the remaining scheduled work.|
|<a name="RemainingOvertimeCost"></a>RemainingOvertimeCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the remaining scheduled overtime expense for the project resource.|
|<a name="RemainingOvertimeWork"></a>RemainingOvertimeWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of remaining scheduled overtime work for the project resource.|
|<a name="RemainingOvertimeWorkMilliseconds"></a>RemainingOvertimeWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of remaining scheduled overtime work for the project resource.|
|<a name="RemainingOvertimeWorkTimeSpan"></a>RemainingOvertimeWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of remaining scheduled overtime work for the project resource.|
|<a name="RemainingWork"></a>RemainingWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time, such as person-hours or days, that is still required for the project resource to complete a task or set of tasks.|
|<a name="RemainingWorkMilliseconds"></a>RemainingWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of time that is still required for the project resource to complete a task or set of tasks.|
|<a name="RemainingWorkTimeSpan"></a>RemainingWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time, such as person-hours or days, that is still required for the project resource to complete a task or set of tasks.|
|<a name="ScheduleCostVariance"></a>ScheduleCostVariance|&#x2713;|&#x2713;|&#x2713;|Double|Gets the scheduled cost variance for the project resource.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date when an assigned resource is scheduled to begin working on a task.|
|<a name="Work"></a>Work|&#x2713;|&#x2713;|&#x2713;|String|Gets the total amount of time to which the project resource is scheduled for a task.|
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total amount of time to which the project resource is scheduled for a task.|
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total amount of time to which the project resource is scheduled for a task.|
|<a name="WorkVariance"></a>WorkVariance|&#x2713;|&#x2713;|&#x2713;|String|Gets the difference between baseline work of a project resource and the currently scheduled work.|
|<a name="WorkVarianceMilliseconds"></a>WorkVarianceMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the difference between baseline work of a project resource and the currently scheduled work.|
|<a name="WorkVarianceTimeSpan"></a>WorkVarianceTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the difference between baseline work of a project resource and the currently scheduled work.|

## <a name="seeAlso"></a>See Also

[DraftProjectResource](DraftProjectResource.md)<br/>
[PublishedProjectResource](PublishedProjectResource.md)<br/>
