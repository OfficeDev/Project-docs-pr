[comment]: # (Name:TimeSheetLineCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:23Z)

# TimeSheetLineCollection

Represents a collection of timesheet lines.



## Syntax

### CSOM

```C#
Class TimeSheetLineCollection 
```
### JSOM

```
PS.TimeSheetLineCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/TimeSheetPeriods('{periodid}')/TimeSheet/Lines
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([TimeSheetLineCreationInformation](TimeSheetLineCreationInformation.md) parameters)](#Add_[TimeSheetLineCreationInformation]_TimeSheetLineCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetLine](TimeSheetLine.md)|Adds the specified timesheet line to the timesheet line collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetLine](TimeSheetLine.md)|Gets the timesheet line from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetLine](TimeSheetLine.md)|Gets the timesheet line from the collection with the  **Id()** value.|
|[Remove([TimeSheetLine](TimeSheetLine.md) line)](#Remove_[TimeSheetLine]_TimeSheetLine.md__line_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified timesheet line from the timesheet line collection.|



## Method Details


### <a id="Add_[TimeSheetLineCreationInformation]_TimeSheetLineCreationInformation.md__parameters_"></a>Add([TimeSheetLineCreationInformation](TimeSheetLineCreationInformation.md) parameters)
 
Adds the specified timesheet line to the timesheet line collection.

#### Syntax

```
TimeSheetLine Add(TimeSheetLineCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [TimeSheetLineCreationInformation](TimeSheetLineCreationInformation.md) | A TimeSheetLineCreationInformation object.


#### Return Value

[TimeSheetLine](TimeSheetLine.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets the timesheet line from the collection with the specified GUID.

#### Syntax

```
TimeSheetLine GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[TimeSheetLine](TimeSheetLine.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets the timesheet line from the collection with the  **Id()** value.

#### Syntax

```
TimeSheetLine GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the timesheet line GUID.


#### Return Value

[TimeSheetLine](TimeSheetLine.md)

### <a id="Remove_[TimeSheetLine]_TimeSheetLine.md__line_"></a>Remove([TimeSheetLine](TimeSheetLine.md) line)
 
Removes the specified timesheet line from the timesheet line collection.

#### Syntax

```
Boolean Remove(TimeSheetLine line)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|line| [TimeSheetLine](TimeSheetLine.md) | A TimeSheetLine object.


#### Return Value

Boolean


## See Also
