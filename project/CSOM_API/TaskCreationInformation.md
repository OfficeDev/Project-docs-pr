
# TaskCreationInformation class

Provides property settings and methods that are used to create a task.

## Syntax

### CSOM

```C#
Class TaskCreationInformation Inherits from ClientValueObject
```

### JSOM

```
PS.TaskCreationInformation
```

### REST Interface

<!-- 
    This needs to be verified, then added to the document. 
    This resource supports GET HTTP command.

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Assignments('assignmentid')
```

    End of comment  -->


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|AddAfterId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID value of the task that specifies the insertion point.|
|Duration|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the task duration.|
|Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the task finish date.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the task.|
|IsManual|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the task is manually scheduled.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the task name.|
|Notes|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets notes about the task.|
|ParentId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the parent task in a hierarchical task list.|
|Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the task start date.|
|StatusManager|&#x2713;&#x02B7;|&#x2713;&#x02B7;||User (SP)|Name of the enterprise resource to receive task status updates.<br />The list contains names of all resources identified as status managers for the current project.|

Ask not what your country can do for you. Ask what you can do for your country.

### Methods

The **ProjectResourceCreationInformation** object has no methods.

