# ProjectCollection class

Represents a collection of [PublishedProject](PublishedProject.md) objects.

## Syntax

### CSOM

```C#
Class ProjectCollection Inherits ClientObjectCollection(Of PublishedProject)
```

### JSOM

```
PS.ProjectCollection

```

### REST Interface

This resource supports GET and DELETE HTTP commands:

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects
```

## Remarks

Project Server creates a virtual [PublishedProject](PublishedProject.md) object for each draft project that has not yet been published. A virtual published project ensures that a draft project can be retrieved through the ProjectCollection object, whether it has been published or not.

For example, if you create a draft project, and then read all projects with the CSOM, ProjectCollection object contains the unpublished draft project. 

You can determine whether a project has been published by the value of the PublishedProject.LastPublishedDate property, which is inherited from Project.LastPublishedDate. For an unpublished project, the LastPublishedDate property value is DateTime.Min (1/1/0001).


## Members

### Properties

<!-- The following table has left-aligned columns 1,5,6; and center-aligned columns 2,3,4. -->

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|item| |&#x2713;| |PublishedProject|Gets the current PublishedProject from the collection.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add(ProjectCreationInformation pcinfo)](#add)|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Adds the project that is specified by the [ProjectCreationInformation](ProjectCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Gets the [PublishedProject](PublishedProject.md) with the specified Guid.|
|[GetById(String id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Gets the [PublishedProject](PublishedProject.md) with the specified ID.|
|[Remove(PublishedProject project)](#remove)|&#x2713;|&#x2713;|&#x2713; |Boolean|Removes the project from the collection. Returns true if successful.|
|[Update()](#update)|&#x2713;|&#x2713;|&#x2713; |[QueueJob](QueueJob.md)|Updates the collection of published projects.|
|[Validate()](#validate)|&#x2713;|&#x2713;|&#x2713; |void|Validates pending changes to the project and all of the entities that it contains without saving them.|

## Method Details

### <a name="add"></a> Add(ProjectCreationInformation pcinfo)

Adds the project that is specified by the [ProjectCreationInformation](ProjectCreationInformation.md) object to the collection.

#### Syntax

```
Add(ProjectCreationInformation pcinfo)
```

#### Parameters


|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|pcinfo| [ProjectCreationInformation](ProjectCreationInformation.md)|Contains the properties that can be set when creating a project.|

#### Return Value

PublishedProject<br />
The added project.




### <a name="getbyguid"></a> GetByGuid(Guid uid)

Gets the [PublishedProject](PublishedProject.md) with the specified Guid.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|The guid that references the [PublishedProject](PublishedProject.md).

#### Return Value

[PublishedProject](PublishedProject.md)<br />
The [PublishedProject](PublishedProject.md) with the specified guid.




### <a name="getbyid"></a>GetById(String id)

Gets the [PublishedProject](PublishedProject.md) with the specified ID.

#### Syntax

```
GetById(String id)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| String|The identifier of the referenced object.

#### Return Value

[PublishedProject](PublishedProject.md)<br />
The [PublishedProject](PublishedProject.md) with the specified ID.




### <a name="remove"></a> Remove(PublishedProject project)

Removes the project from the collection. Returns true if successful.

#### Syntax

```
Remove(PublishedProject project)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|project | [PublishedProject](PublishedProject.md) |The project to remove from the collection.|

#### Return Value

Boolean<br />
Returns true if successful.


### <a name="update"></a> Update()

Updates the collection of published projects.

#### Syntax

```
Update()
```

#### Parameters

none

#### Return Value

[QueueJob](QueueJob.md)<br />
The [QueueJob](QueueJob.md) includes the JobState property that identifies the result of the update request.




### <a name="validate"></a> Validate()

Validates pending changes to the project and all of the entities that it contains without saving them.

#### Syntax

```
Validate()
```

#### Parameters

none

#### Return Code

void

