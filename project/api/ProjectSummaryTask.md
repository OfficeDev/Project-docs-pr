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
|ActualCost|&#x2713;|&#x2713;|&#x2713;|Double|Gets costs incurred for work already performed on the project, together with any other recorded costs that are associated with the project.|
|ActualWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of work that has already been performed on the project.|
|ActualWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of work that has already been performed on the project.|
|ActualWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of work that has already been performed on the project.|
|BudgetWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of work that is estimated to be performed on the project.|
|BudgetWorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of work that is estimated to be performed on the project.|
|BudgetWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of work that is estimated to be performed on the project.|
|Cost|&#x2713;|&#x2713;|&#x2713;|Double|Gets the total scheduled or forecasted cost of the project, based on costs already incurred for work performed, in addition to the costs planned for the remaining work.|
|Duration|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that it takes to complete the project.|
|DurationMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the amount of time that it takes to complete the project.|
|DurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time that it takes to complete the project.|
|FieldValues|&#x2713;|&#x2713;||Dictionary<string,object>|Gets the collection of task-related custom fields.|
|Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the project finish date.|
|FinishText|&#x2713;|&#x2713;|&#x2713;|String|Gets the project finish date expressed as a string.|
|Item|&#x2713;|&#x2713;||Object|Gets an item in the project.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the project summary task.|
|PercentComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the percent of duration completed on the project.|
|Priority|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the project priority.|
|Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the project start date.|
|StartText|&#x2713;|&#x2713;|&#x2713;|String|Gets the project start date expressed as a string.|
|Work|&#x2713;|&#x2713;|&#x2713;|String|Gets the total time scheduled for the project.|
|WorkMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for the total time scheduled for the project.|
|WorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total time scheduled for the project.|


## <a name="seeAlso"></a>See Also

[Project](Project.md)<br/>
