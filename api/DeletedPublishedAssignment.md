
# DeletedPublishedAssignment class
Represents an assignment that was deleted from a [PublishedProject](PublishedProject.md).

## Syntax

### CSOM

```C#
Class DeletedPublishedAssignment
```

### JSOM

```
PS.DeletedPublishedAssignment
```

### REST Interface

This resource supports GET HTTP command.

<!-- The following endpoint is for an assignment. I don't know how to edit it for DeletedPublishedAssignment.

     http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Assignments('assignmentid') 
-->

```
// Endpoint goes here.
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|DeletedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the data and time that the assignment was deleted.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid| Gets the Id of the deleted [Assignment](Assignment.md).|
|ProjectId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the Id of the [PublishedProject](PublishedProject.md) associated with the [Assignment](Assignment.md).|


### Methods

The **DeletedPublishedAssignment** object has no methods.

