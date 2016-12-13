[comment]: # (Name:PlanAssignmentCreationInformation)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# PlanAssignmentCreationInformation

Provides information for the creation of a PlanAssignment object.



## Syntax

### CSOM

```C#
Class PlanAssignmentCreationInformation 
```
### JSOM

```
PS.PlanAssignmentCreationInformation
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/?????
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|BookingType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[BookingType](BookingType.md)|Gets or sets the booking type of the assignment.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the plan assignment.|
|Intervals|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|ReadOnlyCollection`1|Gets or sets an enumerator that iterates through a collection of time intervals.|
|ResourceId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the resource.|






## See Also
