[comment]: # (Name:DraftTaskLink)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# DraftTaskLink

Creates an object to access the task links in a draft project.



## Syntax

### CSOM

```C#
Class DraftTaskLink 
```
### JSOM

```
PS.DraftTaskLink
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Draft/TaskLinks('{linkid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|DependencyType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[DependencyType](DependencyType.md)|Gets or sets the type of link relationship between two tasks.|
|End|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Gets the task at the end of the link.|
|Start|&#x2713;|&#x2713;|&#x2713;|[DraftTask](DraftTask.md)|Gets the task at the start of the link.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the DraftTaskLink object.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the DraftTaskLink object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
