[comment]: # (Name:DraftProject)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>DraftProject class

inherits members from [Project](Project.md)<br/>

<a name="description"></a>Represents the draft version of a project that is either new, or a [PublishedProject](PublishedProject.md) that is checked out for editing.

## <a name="syntax"></a>Syntax
### CSOM

```C#
class DraftProject 
```
### JSOM

```JavaScript
PS.DraftProject
```

### REST Interface

This resource supports GET, POST, PUT, PATCH,  and MERGE HTTP commands.

```
PS.DraftProject

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Draft
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the draft project.|
|<a name="Assignments"></a>Assignments|&#x2713;|&#x2713;|&#x2713;|[DraftAssignmentCollection](DraftAssignmentCollection.md)|Gets the collection of assignments for a project.|
|<a name="Calendar"></a>Calendar|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[Calendar](Calendar.md)|Gets or sets a Project Server calendar.|
|<a name="CurrencyCode"></a>CurrencyCode|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the currency code of the project, as defined in ISO 4217.|
|<a name="CurrencyDigits"></a>CurrencyDigits|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the number of decimal digits in currency values.|
|<a name="CurrencyPosition"></a>CurrencyPosition|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CurrencySymbolPosition](CurrencySymbolPosition.md)|Gets or sets the placement of the currency symbol in relation to the currency value.|
|<a name="CurrencySymbol"></a>CurrencySymbol|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the currency symbol that represents the type of currency that is used in the project.|
|<a name="CurrentDate"></a>CurrentDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the current date for the project.|
|<a name="DaysPerMonth"></a>DaysPerMonth|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the default number of working days per month.|
|<a name="DefaultEffortDriven"></a>DefaultEffortDriven|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the scheduling of new tasks is effort-driven.|
|<a name="DefaultEstimatedDuration"></a>DefaultEstimatedDuration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether new tasks have estimated durations.|
|<a name="DefaultFixedCostAccrual"></a>DefaultFixedCostAccrual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[FixedCostAccrual](FixedCostAccrual.md)|Gets or sets a value that indicates which default fixed cost accrual method to use on new tasks.|
|<a name="DefaultOvertimeRate"></a>DefaultOvertimeRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the default overtime rate for local resources.|
|<a name="DefaultStandardRate"></a>DefaultStandardRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|Gets or sets the default standard rate for local resources.|
|<a name="DefaultTaskType"></a>DefaultTaskType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[TaskType](TaskType.md)|Gets or sets the default type for tasks in the project.|
|<a name="DefaultWorkFormat"></a>DefaultWorkFormat|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[WorkFormat](WorkFormat.md)|Gets or sets the default format for work duration.|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets a project description.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the draft project.|
|<a name="FinishDate"></a>FinishDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the project finish date.|
|<a name="FiscalYearStartMonth"></a>FiscalYearStartMonth|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the number of the first month in the fiscal year.|
|<a name="IncludeCustomFields"></a>IncludeCustomFields|&#x2713;|&#x2713;|&#x2713;|[DraftProject](DraftProject.md)|Gets a DraftProject object that includes custom fields.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets or sets an item in the draft project.|
|<a name="MinutesPerDay"></a>MinutesPerDay|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the default number of minutes per day.|
|<a name="MinutesPerWeek"></a>MinutesPerWeek|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the default number of minutes per week.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets a project name.|
|<a name="NewTasksAreManual"></a>NewTasksAreManual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether new tasks are manually scheduled.|
|<a name="NumberFiscalYearFromStart"></a>NumberFiscalYearFromStart|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether to use the project start year for fiscal year numbering.|
|<a name="Owner"></a>Owner|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets or sets the project owner.|
|<a name="ProjectIdentifier"></a>ProjectIdentifier|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the Project Identifer (secondary identifer)|
|<a name="ProjectResources"></a>ProjectResources|&#x2713;|&#x2713;|&#x2713;|[DraftProjectResourceCollection](DraftProjectResourceCollection.md)|Gets the collection of resources for a project.|
|<a name="ProtectedActualsSynch"></a>ProtectedActualsSynch|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the project actuals are synchronized with the protected actuals.|
|<a name="ShowEstimatedDurations"></a>ShowEstimatedDurations|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a question mark is displayed after an estimated duration for a task.|
|<a name="StartDate"></a>StartDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the project start date.|
|<a name="StatusDate"></a>StatusDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the current status date for the project.|
|<a name="TaskLinks"></a>TaskLinks|&#x2713;|&#x2713;|&#x2713;|[DraftTaskLinkCollection](DraftTaskLinkCollection.md)|Gets the collection of draft task link objects for the project.|
|<a name="Tasks"></a>Tasks|&#x2713;|&#x2713;|&#x2713;|[DraftTaskCollection](DraftTaskCollection.md)|Gets the collection of task objects for the project.|
|<a name="TrackingMode"></a>TrackingMode|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[PSTrackingModeEnum](PSTrackingModeEnum.md)|Gets or sets the default tracking method for all assignments in the project.|
|<a name="UtilizationDate"></a>UtilizationDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime||
|<a name="UtilizationType"></a>UtilizationType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[UtilizationType](UtilizationType.md)||
|<a name="WeekStartDay"></a>WeekStartDay|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the day of the week on which a work week starts.|
|<a name="WinprojVersion"></a>WinprojVersion|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal|Gets or sets the version of Project Professional that created the draft project.|


### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[ChangeEnterpriseProjectType(Guid enterpriseProjectTypeUid)](#ChangeEnterpriseProjectType_Guid_enterpriseProjectTypeUid_)|||&#x2713;|void|Changes or sets an [EnterpriseProjectType](EnterpriseProjectType.md) associated with a project.|
|[CheckIn(Boolean force)](#CheckIn_Boolean_force_)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Queues a check-in job for a draft project if it is still checked out.|
|[Publish(Boolean checkIn)](#Publish_Boolean_checkIn_)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Queues a publish job to get the changes from the draft project back to the published version.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Saves changes in a new project or checked-out draft project back to Project Server.|
|[UpdateCustomFields(Collection(SP.KeyValue) customFieldDictionary)](#UpdateCustomFields_Collection_SP.KeyValue__customFieldDictionary_)|||&#x2713;|[QueueJob](QueueJob.md)|Updates the custom fields for a project in bulk.|
|[Validate()](#Validate__)|&#x2713;|&#x2713;|&#x2713;|void|Validates pending changes from all added or removed projects.|

<br/>
#### Method Details

#### <a name="ChangeEnterpriseProjectType_Guid_enterpriseProjectTypeUid_"></a>ChangeEnterpriseProjectType(Guid enterpriseProjectTypeUid)

Changes or sets an [EnterpriseProjectType](EnterpriseProjectType.md) associated with a project.

##### Syntax

```
void ChangeEnterpriseProjectType(Guid enterpriseProjectTypeUid)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|enterpriseProjectTypeUid|Guid|Id of the new [EnterpriseProjectType](EnterpriseProjectType.md).

##### Return Value

void

#### <a name="CheckIn_Boolean_force_"></a>CheckIn(Boolean force)

Queues a check-in job for a draft project if it is still checked out.

##### Syntax

```
QueueJob CheckIn(Boolean force)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|force | Boolean | True if the administrator or project owner forces check in of a project; otherwise, False.

##### Return Value

[QueueJob](QueueJob.md) <br />
A queued job that will check in the draft version of the project.

#### <a name="Publish_Boolean_checkIn_"></a>Publish(Boolean checkIn)

Queues a publish job to get the changes from the draft project back to the published version.

##### Syntax

```
QueueJob Publish(Boolean checkIn)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|checkIn| Boolean | Boolean that indicates whether the project should be checked in after it is published.

##### Return Value

[QueueJob](QueueJob.md) <br />
A [QueueJob](QueueJob.md) object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service publishes the draft version of the project.

#### <a name="Update__"></a>Update()

Saves changes in a new project or checked-out draft project back to Project Server.

##### Syntax

```
QueueJob Update()
```

##### Parameters

None

##### Return Value

[QueueJob](QueueJob.md) <br />
A [QueueJob](QueueJob.md) object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service saves the new or draft version of the project.

#### <a name="UpdateCustomFields_Collection_SP.KeyValue__customFieldDictionary_"></a>UpdateCustomFields(Collection(SP.KeyValue) customFieldDictionary)
 
##### Syntax

```
QueueJob UpdateCustomFields(Collection(SP.KeyValue) customFieldDictionary)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|customFieldDictionary|Collection([SP.KeyValue](https://msdn.microsoft.com/en-us/library/office/dn600183.aspx#bk_KeyValue))|Collection of project custom fields to set for the project

##### Return Value

[QueueJob](QueueJob.md)<br />
A [QueueJob](QueueJob.md) object that contains information about the queued job. If the queue job is successful, the Project Server Queuing Service saves the new or draft version of the project.


#### <a name="Validate__"></a>Validate()
 
Validates pending changes from all added or removed projects.

##### Syntax

```
void Validate()
```

##### Parameters

None
 
##### Return Value

void


## Remarks

The **[DraftProject](DraftProject.md)** class and the **[PublishedProject](PublishedProject.md)** class derive from the **[Project](Project.md)** class. 

To set the value of properties in an existing project:

1. Use the **[PublishedProject](PublishedProject.md) CheckOut** method.
2. Edit the **[DraftProject](DraftProject.md)** object.
3. Check in the edited project using the **DraftProject [CheckIn](#checkin)** method.


## <a name="seeAlso"></a>See Also

[Collection(SP.KeyValue)](https://msdn.microsoft.com/en-us/library/office/dn600183.aspx#bk_KeyValue)<br/>
[PublishedProject](PublishedProject.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
