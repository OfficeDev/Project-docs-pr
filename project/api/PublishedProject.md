[comment]: # (Name:PublishedProject)
[comment]: # (Name:Microsoft.ProjectServer.PublishedProject)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PublishedProject class

inherits members from [Project](Project.md)<br/>

<a name="description"></a>Represents a project that is published on the Project Service.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PublishedProject 
```
### JSOM

```javascript
PS.PublishedProject
```

### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.PublishedProject

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the published project.|
|<a name="Assignments"></a>Assignments|&#x2713;|&#x2713;|&#x2713;|[PublishedAssignmentCollection](PublishedAssignmentCollection.md)|Gets the collection of assignments in the project.|
|<a name="Calendar"></a>Calendar|&#x2713;|&#x2713;|&#x2713;|[Calendar](Calendar.md)|Gets the project calendar.|
|<a name="CurrencyCode"></a>CurrencyCode|&#x2713;|&#x2713;|&#x2713;|String|Gets the currency code of the project, as defined in ISO 4217.|
|<a name="CurrencyDigits"></a>CurrencyDigits|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the number of decimal digits in currency values.|
|<a name="CurrencyPosition"></a>CurrencyPosition|&#x2713;|&#x2713;|&#x2713;|[CurrencySymbolPosition](CurrencySymbolPosition.md)|Gets the placement of the currency symbol in relation to the currency value.|
|<a name="CurrencySymbol"></a>CurrencySymbol|&#x2713;|&#x2713;|&#x2713;|String|Gets the currency symbol that represents the type of currency that is used in the project.|
|<a name="CurrentDate"></a>CurrentDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the current date for the project.|
|<a name="DaysPerMonth"></a>DaysPerMonth|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the default number of working days per month.|
|<a name="DefaultEffortDriven"></a>DefaultEffortDriven|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the scheduling of new tasks is effort-driven.|
|<a name="DefaultEstimatedDuration"></a>DefaultEstimatedDuration|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether new tasks have estimated durations.|
|<a name="DefaultFixedCostAccrual"></a>DefaultFixedCostAccrual|&#x2713;|&#x2713;|&#x2713;|[FixedCostAccrual](FixedCostAccrual.md)|Gets a value that indicates which default fixed-cost accrual method to use on new tasks.|
|<a name="DefaultOvertimeRate"></a>DefaultOvertimeRate|&#x2713;|&#x2713;|&#x2713;|Double|Gets the default overtime rate for local resources.|
|<a name="DefaultStandardRate"></a>DefaultStandardRate|&#x2713;|&#x2713;|&#x2713;|Double|Gets the default standard rate for local resources.|
|<a name="DefaultTaskType"></a>DefaultTaskType|&#x2713;|&#x2713;|&#x2713;|[TaskType](TaskType.md)|Gets the default type for tasks in the project.|
|<a name="DefaultWorkFormat"></a>DefaultWorkFormat|&#x2713;|&#x2713;|&#x2713;|[WorkFormat](WorkFormat.md)|Gets the default format for work duration.|
|<a name="Description"></a>Description|&#x2713;|&#x2713;|&#x2713;|String|Gets the project description.|
|<a name="Draft"></a>Draft|&#x2713;|&#x2713;|&#x2713;|[DraftProject](DraftProject.md)|Gets a [DraftProject](DraftProject.md) object if it is not already checked out.|
|<a name="EnterpriseProjectTypeId"></a>EnterpriseProjectTypeId|||&#x2713;|Guid|Gets the GUID of the enterprise project type.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the published project.|
|<a name="FinishDate"></a>FinishDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the project finish date.|
|<a name="FiscalYearStartMonth"></a>FiscalYearStartMonth|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the number of the first month in the fiscal year.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the project. (Inherited from[Project](Project.md).)|
|<a name="IncludeCustomFields"></a>IncludeCustomFields|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Gets a PublishedProject object that includes custom fields.|
|<a name="IsCheckedOut"></a>IsCheckedOut|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the project is checked out. (Inherited from[Project](Project.md).)|
|<a name="IsEnterpriseProject"></a>IsEnterpriseProject|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the published project is an enterprise project (managed by Project Server).|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the published project.|
|<a name="MinutesPerDay"></a>MinutesPerDay|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the default number of minutes per day.|
|<a name="MinutesPerWeek"></a>MinutesPerWeek|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the default number of minutes per week.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the project.|
|<a name="NewTasksAreManual"></a>NewTasksAreManual|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether new tasks are manually scheduled.|
|<a name="NumberFiscalYearFromStart"></a>NumberFiscalYearFromStart|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether to use the project start year for fiscal year numbering.|
|<a name="Owner"></a>Owner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the owner of the project.|
|<a name="ProjectIdentifier"></a>ProjectIdentifier|&#x2713;|&#x2713;|&#x2713;|String|Gets the project identifer.|
|<a name="ProjectResources"></a>ProjectResources|&#x2713;|&#x2713;|&#x2713;|[PublishedProjectResourceCollection](PublishedProjectResourceCollection.md)|Gets the collection of resources for a project.|
|<a name="ProjectSiteUrl"></a>ProjectSiteUrl|&#x2713;|&#x2713;|&#x2713;|String|Gets the URL of the project site. (Inherited from[Project](Project.md).)|
|<a name="ProtectedActualsSynch"></a>ProtectedActualsSynch|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets whether the project actuals are synchronized with the protected actuals.|
|<a name="ShowEstimatedDurations"></a>ShowEstimatedDurations|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether a question mark is displayed after an estimated duration for a task.|
|<a name="StartDate"></a>StartDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the project start date.|
|<a name="StatusDate"></a>StatusDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the status date for the project.|
|<a name="SummaryTaskId"></a>SummaryTaskId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID for the hidden project summary task. (Inherited from[Project](Project.md).)|
|<a name="TaskLinks"></a>TaskLinks|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLinkCollection](PublishedTaskLinkCollection.md)|Gets the collection of task links for the project.|
|<a name="Tasks"></a>Tasks|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskCollection](PublishedTaskCollection.md)|Gets the collection of tasks for the project.|
|<a name="TrackingMode"></a>TrackingMode|&#x2713;|&#x2713;|&#x2713;|[TrackingMode](TrackingMode.md)|Gets the default tracking method for all assignments in the project.|
|<a name="UtilizationDate"></a>UtilizationDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the date and time of resource utilization for the current project.|
|<a name="UtilizationType"></a>UtilizationType|&#x2713;|&#x2713;|&#x2713;|[ProjectUtilizationType](ProjectUtilizationType.md)|Gets the derivation source(s) of the summary resource assignments of a project.|
|<a name="WeekStartDay"></a>WeekStartDay|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the day of the week on which a work week starts.|
|<a name="WinprojVersion"></a>WinprojVersion|&#x2713;|&#x2713;|&#x2713;|Decimal|Gets the version of Project Professional that created the published project.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----: |:-----: |:-----: |:-----|:-----|
|[CheckOut()](#CheckOut__)|&#x2713;|&#x2713;|&#x2713;|[DraftProject](DraftProject.md)|Checks out the draft version of the project.|
|[CreateProjectSite(String siteName)](#CreateProjectSite_String_siteName_)|&#x2713;|&#x2713;|&#x2713;|void|Creates the project site for the project.|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Deletes the published project object.|
|[SubmitToWorkflow()](#SubmitToWorkflow__)|&#x2713;|&#x2713;|&#x2713;|void|Causes the workflow to run.|
|[UpdateVisibilityCustomFields()](#UpdateVisibilityCustomFields__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Updates the custom fields for a project in visibility mode.|

<br/>
#### Method Details

#### <a name="CheckOut__"></a>CheckOut()

Checks out the draft version of the project.

##### Syntax

```
DraftProject CheckOut()
```

##### Parameters

None

##### Return Value

[DraftProject](DraftProject.md)<br />
The draft version of the project.

#### <a name="CreateProjectSite_String_siteName_"></a>CreateProjectSite(String siteName)

Creates the project site for the project. 

##### Syntax


```
void CreateProjectSite(String siteName)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|siteName| String |Name of the new project website. If empty, the website name will be the same as the project name.|

##### Return Value

void

#### <a name="DeleteObject__"></a>DeleteObject()

Deletes the published project object.

##### Syntax
Deletes the [PublishedProject](PublishedProject.md) object.

```
QueueJob DeleteObject()
```

##### Parameters

None

##### Return Value

[QueueJob](QueueJob.md)

#### Remarks

If the queue job is successful, the Project Server Queuing Service deletes the published version of the project. The draft version is also deleted.


#### <a name="SubmitToWorkflow__"></a>SubmitToWorkflow()

Causes the workflow to run.

##### Syntax

```
void SubmitToWorkflow()
```

##### Parameters

None

##### Return Value

void

#### <a name="UpdateVisibilityCustomFields__"></a>UpdateVisibilityCustomFields()
 
Updates the custom fields for a project in visibility mode.

##### Syntax

```
QueueJob UpdateVisibilityCustomFields() 
```

##### Parameters

None

##### Return Value
[QueueJob](QueueJob.md)<br />
A [QueueJob](QueueJob.md) object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service saves the published version of the project.


## Remarks

To set the value of properties in an existing project:

1. Use the **[PublishedProject](PublishedProject.md) [CheckOut](#checkout)** method.
2. Edit the **[DraftProject](DraftProject.md)** object.
3. Check in the edited project using the **[DraftProject](DraftProject.md) CheckIn** method.


## <a name="seeAlso"></a>See Also

[ProjectCollection](ProjectCollection.md)<br/>
[ProjectCreationInformation](ProjectCreationInformation.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
[StatusAssignment](StatusAssignment.md)<br/>
[Task](Task.md)<br/>
