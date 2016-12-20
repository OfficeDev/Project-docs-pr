[comment]: # (Name:TimeSheetWorkCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:23Z)

# TimeSheetWorkCollection

Provides a collection of actual work entries for a timesheet. 



## Syntax

### CSOM

```C#
Class TimeSheetWorkCollection 
```
### JSOM

```
PS.TimeSheetWorkCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines('{lineid}')/Work
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([TimeSheetWorkCreationInformation](TimeSheetWorkCreationInformation.md) parameters)](#Add_[TimeSheetWorkCreationInformation]_TimeSheetWorkCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetWork](TimeSheetWork.md)|Adds an actual work value to a timesheet.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetWork](TimeSheetWork.md)|Gets a timesheet actual work object from the collection with the  **Id()** value.|
|[GetByStartDate(DateTime start)](#GetByStartDate_DateTime_start_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetWork](TimeSheetWork.md)|Gets a timesheet actual work object from the collection with a specified start date.|
|[Remove([TimeSheetWork](TimeSheetWork.md) work)](#Remove_[TimeSheetWork]_TimeSheetWork.md__work_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes a specified actual work value from a timesheet.|



## Method Details


### <a id="Add_[TimeSheetWorkCreationInformation]_TimeSheetWorkCreationInformation.md__parameters_"></a>Add([TimeSheetWorkCreationInformation](TimeSheetWorkCreationInformation.md) parameters)
 
Adds an actual work value to a timesheet.

#### Syntax

```
TimeSheetWork Add(TimeSheetWorkCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [TimeSheetWorkCreationInformation](TimeSheetWorkCreationInformation.md) | An object that contains information for the creation of an actual work item.


#### Return Value

[TimeSheetWork](TimeSheetWork.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a timesheet actual work object from the collection with the  **Id()** value.

#### Syntax

```
TimeSheetWork GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of a timesheet actual work GUID.


#### Return Value

[TimeSheetWork](TimeSheetWork.md)

### <a id="GetByStartDate_DateTime_start_"></a>GetByStartDate(DateTime start)
 
Gets a timesheet actual work object from the collection with a specified start date.

#### Syntax

```
TimeSheetWork GetByStartDate(DateTime start)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|start| DateTime | The start date and time.


#### Return Value

[TimeSheetWork](TimeSheetWork.md)

### <a id="Remove_[TimeSheetWork]_TimeSheetWork.md__work_"></a>Remove([TimeSheetWork](TimeSheetWork.md) work)
 
Removes a specified actual work value from a timesheet.

#### Syntax

```
Boolean Remove(TimeSheetWork work)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|work| [TimeSheetWork](TimeSheetWork.md) | The actual work element to remove.


#### Return Value

Boolean


## See Also
