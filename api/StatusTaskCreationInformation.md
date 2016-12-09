
# StatusTaskCreationInformation

Provides property settings and methods for the creation of a StatusTask object.

## Syntax

### CSOM

```C#
Class StatusTaskCreationInformation 
```
### JSOM

```
PS.StatusTaskCreationInformation
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection> /<site> /_api/ProjectServer/?????
```


## Members

### Properties

|**CSOM**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Finish|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when a task is scheduled to be completed.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the status task object.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the status task object.|
|ParentId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the parent, or summary, task in a hierarchical task list.|
|Start|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date when work on the task is scheduled to begin.|
|Work|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the planned work for the task.|




## See Also
