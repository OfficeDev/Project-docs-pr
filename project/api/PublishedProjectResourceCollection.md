# PublishedProjectResourceCollection class

Represents a collection of resources in a published project.

## Syntax

### CSOM

```
class PublishedProjectResourceCollection 
```

### JSOM

```
PS.PublishedProjectResourceCollection
```

### REST Interface

This resource supports GET and POST HTTP commands:

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/ProjectResources
```

## Members

### Properties

<!-- The following table has left-aligned columns 1,5,6; and center-aligned columns 2,3,4. -->

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|item| |&#x2713;| |PublishedProjectResource|Gets the current resource from the collection.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|[PublishedProjectResource](PublishedProjectResource.md)|Gets a resource from the collection with the specified Guid.|
|[GetById(String id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|[PublishedProjectResource](PublishedProjectResource.md)|Gets a resource from the collection with the Id value.|


## Method Details


### <a name="getbyguid"></a> GetByGuid(Guid uid)

Gets a resource from the collection with the specified Guid.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|A guid value.

#### Return Value

[PublishedProjectResource](PublishedProjectResource.md)<br />
A [PublishedProjectResource](PublishedProjectResource.md) object.



### <a name="getbyid"></a>GetById(string id)

Gets a resource from the collection with the Id value.

#### Syntax

```
GetById(string id)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| string|The string representation of the project resource GUID.

#### Return Value

[PublishedProjectResource](PublishedProjectResource.md)<br />
The [PublishedProjectResource](PublishedProjectResource.md) with the specified ID.

