[comment]: # (Name:ProjectDetailPageCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# ProjectDetailPageCollection

Represents a collection of project detail pages (PDPs).



## Syntax

### CSOM

```C#
Class ProjectDetailPageCollection 
```
### JSOM

```
PS.ProjectDetailPageCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/ProjectDetailPages
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|List|&#x2713;|&#x2713;|&#x2713;|SPList|Gets a list of available project detail pages.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[ProjectDetailPage](ProjectDetailPage.md)|Gets a project detail page from the list of available project detail pages by using a GUID identifier.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[ProjectDetailPage](ProjectDetailPage.md)|Gets a project detail page from the list of available project detail pages by using a string identifier.|



## Method Details


### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a project detail page from the list of available project detail pages by using a GUID identifier.

#### Syntax

```
ProjectDetailPage GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | The GUID identifier of a project detail page.


#### Return Value

[ProjectDetailPage](ProjectDetailPage.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a project detail page from the list of available project detail pages by using a string identifier.

#### Syntax

```
ProjectDetailPage GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string identifier of a project detail page.


#### Return Value

[ProjectDetailPage](ProjectDetailPage.md)


## See Also
