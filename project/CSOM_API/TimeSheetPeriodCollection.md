[comment]: # (Name:TimeSheetPeriodCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:23Z)

# TimeSheetPeriodCollection

Represents a collection of TimeSheetPeriod objects.



## Syntax

### CSOM

```C#
Class TimeSheetPeriodCollection 
```
### JSOM

```
PS.TimeSheetPeriodCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/TimeSheetPeriods
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetPeriod](TimeSheetPeriod.md)|Gets a timesheet period from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[TimeSheetPeriod](TimeSheetPeriod.md)|Gets a timesheet period from the collection with the  **Id()** value.|



## Method Details


### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a timesheet period from the collection with the specified GUID.

#### Syntax

```
TimeSheetPeriod GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[TimeSheetPeriod](TimeSheetPeriod.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a timesheet period from the collection with the  **Id()** value.

#### Syntax

```
TimeSheetPeriod GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the timesheet period GUID.


#### Return Value

[TimeSheetPeriod](TimeSheetPeriod.md)


## See Also
