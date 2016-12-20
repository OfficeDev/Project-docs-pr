[comment]: # (Name:PublishedTaskLink)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# PublishedTaskLink

Represents a dependency relationship between the start and finish dates of two tasks.



## Syntax

### CSOM

```C#
Class PublishedTaskLink 
```
### JSOM

```
PS.PublishedTaskLink
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/TaskLinks('{linkid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|DependencyType|&#x2713;|&#x2713;|&#x2713;|[DependencyType](DependencyType.md)|Gets the type of link relationship between two tasks.|
|End|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets the task at the end of the link.|
|Start|&#x2713;|&#x2713;|&#x2713;|[PublishedTask](PublishedTask.md)|Gets the task at the start of the link.|






## See Also
