
# AssignmentCreationInformation class
Contains the properties that can be set when creating an [Assignment](Assignment.md).

## Syntax

### CSOM

```C#
Class AssignmentCreationInformation Inherits from ClientValueObject
```

### JSOM

```
PS.AssignmentCreationInformation
```

### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP command.

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Assignments('assignmentid')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the assignment finish date and time.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the Guid of the assignment.|
|Notes|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the notes for the assignment.|
|ResourceId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the Guid of the resource for the assignment.|
|Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the assignment start date and time.|
|TaskId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the Guid of the task for the assignment.|


### Methods

The **AssignmentCreationInformation** object has no methods.

