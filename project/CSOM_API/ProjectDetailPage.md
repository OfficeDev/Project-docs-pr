[comment]: # (Name:ProjectDetailPage)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# ProjectDetailPage

Represents a project detail page (PDP), which is a Web Part page for creating, viewing, or managing the properties of projects in Project Web App.



## Syntax

### CSOM

```C#
Class ProjectDetailPage 
```
### JSOM

```
PS.ProjectDetailPage
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/ProjectDetailPages('{pageid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the project detail page.|
|Item|&#x2713;|&#x2713;|&#x2713;|SPListItem|Gets an item from the list of items on the project detail page.|
|Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the title or name of the project detail page.|
|PageType|&#x2713;|&#x2713;|&#x2713;|[PageType](PageType.md)|Gets the type of the project detail page.|






## See Also
