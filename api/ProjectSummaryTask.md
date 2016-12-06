
# ProjectSummaryTask class

Represents an entire project as a single task, with start and and finish dates, and 
calculated values for project details. 

## Syntax

### CSOM

```
Class ProjectSummaryTask 
```

### JSOM

```
PS.ProjectSummaryTask
```

### REST Interface

This resource supports the PUT, DELETE, and MERGE HTTP commands.

<!-- Need syntax for REST -->
```

```
## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|ActualCost|&#x2713;|&#x2713;|&#x2713;|Float64|Gets costs incurred for work already performed on the project, together with any other recorded costs that are associated with the project.|
|ActualWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of work that has already been performed on the project.|
|ActualWorkMilliseconds||&#x2713;|&#x2713;|Float64|Gets the time interval, expressed in milliseconds, for the amount of work that has already been performed on the project.|
|ActualWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of work that has already been performed on the project.|
|BudgetWork|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of work that is estimated to be performed on the project.|
|BudgetWorkMilliseconds||&#x2713;|&#x2713;|Float64|Gets the time interval, expressed in milliseconds, for the amount of work that is estimated to be performed on the project.|
|BudgetWorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of work that is estimated to be performed on the project.|
|Cost|&#x2713;|&#x2713;|&#x2713;|Float64|Gets the total scheduled or forecasted cost of the project, based on costs already incurred for work performed, in addition to the costs planned for the remaining work.|
|Duration|&#x2713;|&#x2713;|&#x2713;|String|Gets the amount of time that it takes to complete the project.|
|DurationMilliseconds||&#x2713;|&#x2713;|Float64|Gets the time interval, expressed in milliseconds, for the amount of time that it takes to complete the project.|
|DurationTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the amount of time that it takes to complete the project.|
|FieldValues|&#x2713;|&#x2713;||Dictionary<string,object>|Gets the collection of task-related custom fields.|
|Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the project finish date.|
|FinishText|&#x2713;|&#x2713;|&#x2713;|String|Gets the project finish date expressed as a string.|
|Item|&#x2713;|&#x2713;||Object|Gets an item in the project.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the project summary task.|
|PercentComplete|&#x2713;|&#x2713;|&#x2713;|int32|Gets the percent of duration completed on the project.|
|Priority|&#x2713;|&#x2713;|&#x2713;|int32|Gets the project priority.|
|Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the project start date.|
|StartText|&#x2713;|&#x2713;|&#x2713;|String|Gets the project start date expressed as a string.|
|Work|&#x2713;|&#x2713;|&#x2713;|String|Gets the total time scheduled for the project.|
|WorkMilliseconds||&#x2713;|&#x2713;|Float64|Gets the time interval, expressed in milliseconds, for the total time scheduled for the project.|
|WorkTimeSpan|&#x2713;||&#x2713;|TimeSpan|Gets the time interval for the total time scheduled for the project.|


### Methods

The  **ProjectSummaryTask** object has no methods.



