[comment]: # (Name:ProjectSummaryTask)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectSummaryTask class

inherits members from [Task](Task.md)<br/>

<a name="description"></a>

Represents an entire project as a single task, with start and and finish dates, and 
calculated values for project details. 

## <a name="syntax"></a>Syntax

### CSOM

```C#
class ProjectSummaryTask 
```
### JSOM

```JavaScript
PS.ProjectSummaryTask
```

### REST Interface

This resource supports the GET HTTP commands.

```
PS.ProjectSummaryTask

http://<sitecollection>/<site>/api/ProjectServer/ProjectsProjects('projectid')/ProjectSummaryTask
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[]"></a>[]|&#x2713;&#x02B7;|||Dictionary&lt;string, Object&gt;|Gets or sets an item in the project summary task.|
|<a name="ActualCost"></a>ActualCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets costs incurred for work already performed on the project, together with any other recorded costs that are associated with the project.|
|<a name="ActualWork"></a>ActualWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of work that has already been performed on the project.|
|<a name="ActualWorkMilliseconds"></a>ActualWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of work that has already been performed on the project.|
|<a name="ActualWorkTimeSpan"></a>ActualWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of work that has already been performed on the project.|
|<a name="BudgetWork"></a>BudgetWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of work that is estimated to be performed on the project.|
|<a name="BudgetWorkMilliseconds"></a>BudgetWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of work that is estimated to be performed on the project.|
|<a name="BudgetWorkTimeSpan"></a>BudgetWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of work that is estimated to be performed on the project.|
|<a name="Cost"></a>Cost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total scheduled or forecasted cost of the project, based on costs already incurred for work performed, in addition to the costs planned for the remaining work.|
|<a name="Duration"></a>Duration|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that it takes to complete the project.|
|<a name="DurationMilliseconds"></a>DurationMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of time that it takes to complete the project.|
|<a name="DurationTimeSpan"></a>DurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time that it takes to complete the project.|
|<a name="FieldValues"></a>FieldValues|&#x2713;|&#x2713;||Dictionary&lt;string, Object&gt;|Gets the collection of custom fields that have values set for the project summary task.|
|<a name="Finish"></a>Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the project finish date.|
|<a name="FinishText"></a>FinishText|&#x2713;|&#x2713;|&#x2713;|String|Gets the project finish date expressed as a string.|
|<a name="Item"></a>Item||&#x2713;&#x02B7;||Dictionary&lt;string, Object&gt;|Gets the collection of task-related custom fields.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the project summary task.|
|<a name="PercentComplete"></a>PercentComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the percent of duration completed on the project.|
|<a name="Priority"></a>Priority|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the project priority.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the project start date.|
|<a name="StartText"></a>StartText|&#x2713;|&#x2713;|&#x2713;|String|Gets the project start date expressed as a string.|
|<a name="Work"></a>Work|&#x2713;|&#x2713;|&#x2713;|String|Gets the total time scheduled for the project.|
|<a name="WorkMilliseconds"></a>WorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total time scheduled for the project.|
|<a name="WorkTimeSpan"></a>WorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total time scheduled for the project.|

## <a name="seeAlso"></a>See Also

[Project](Project.md)<br/>
