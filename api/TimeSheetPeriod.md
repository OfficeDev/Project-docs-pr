[comment]: # (Name:TimeSheetPeriod)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:23Z)

# TimeSheetPeriod

Represents a defined period of time on a timesheet.



## Syntax

### CSOM

```C#
Class TimeSheetPeriod 
```
### JSOM

```
PS.TimeSheetPeriod
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/TimeSheetPeriods('{periodid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|End|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the end date of a timesheet period.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the timesheet period.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the timesheet period.|
|Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the start date of the timesheet period.|
|TimeSheet|&#x2713;|&#x2713;|&#x2713;|[TimeSheet](TimeSheet.md)|Gets the timesheet that is associated with the timesheet period.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[CreateTimeSheet()](#CreateTimeSheet__)|&#x2713;|&#x2713;|&#x2713;|[TimeSheet](TimeSheet.md)|Creates a new TimeSheet object.|



## Method Details


### <a id="CreateTimeSheet__"></a>CreateTimeSheet()
 
Creates a new TimeSheet object.

#### Syntax

```
TimeSheet CreateTimeSheet()
```

#### Parameters

None

#### Return Value

[TimeSheet](TimeSheet.md)


## See Also
