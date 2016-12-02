# DraftProjectResourceCollection class

Represents a collection of draft project resources.

## Syntax

### CSOM

```C#
class DraftProjectResourceCollection Inherits ClientObjectCollection(of DraftProjectResource)
```

### JSOM

```
PS.DraftProjectResourceCollection
```

### REST Interface

This resource supports GET and POST HTTP commands:

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Draft/ProjectResources
```

## Members

### Properties

<!-- The following table has left-aligned columns 1,5,6; and center-aligned columns 2,3,4. -->

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|item| |&#x2713;| |DraftProjectResource|Gets the current DraftProjectResource from the collection.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[Add(ProjectResourceCreationInformation prcinfo)](#add)|&#x2713;|&#x2713;|&#x2713;|DraftProjectResource|Adds a new ProjectResource that is specified by the ProjectResourceCreationInformation object to the collection.|
|[AddEnterpriseResource(EnterpriseResource resource)](#addenterpriseresource)|&#x2713;|&#x2713;||DraftProjectResource|Adds an existing enterprise resource to the draft project resource collection.|
|[AddEnterpriseResourceById(Guid resourceId)](#addenterpriseresourcebyid)|||&#x2713;|QueueJob|Adds an existing enterprise resource with the specified Id value to the draft project resource collection.|
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|DraftProjectResource|Gets a draft project resource from the collection with the specified GUID.|
|[GetById(String id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|DraftProjectResource|Gets a draft project resource from the collection with the Id value.|
|[Remove(DraftProjectResource resource)](#remove)|&#x2713;|&#x2713;||Boolean|Removes the specified draft project resource from the collection|


## Method Details

### <a name="add"></a> Add(ProjectResourceCreationInformation prcinfo)

Adds a new ProjectResource that is specified by the ProjectResourceCreationInformation object to the collection.

#### Syntax

```
Add(ProjectResourceCreationInformation prcinfo)
```

#### Parameters


|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|prcinfo | ProjectResourceCreationInformation |Contains the properties of the project resource to create.|

#### Return Value

DraftProjectResource<br />
The added DraftProjectResource.



### <a name="addenterpriseresource"></a> AddEnterpriseResource(EnterpriseResource resource)

Adds an existing enterprise resource to the draft project resource collection.

#### Syntax

```
AddEnterpriseResource(EnterpriseResource resource)
```

#### Parameters


|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|resource | EnterpriseResource |The enterprise resource to add.|

#### Return Value

DraftProjectResource<br />
The added DraftProjectResource.



### <a name="addenterpriseresourcebyid"></a> AddEnterpriseResourceById(Guid resourceId)

Adds an existing enterprise resource specified by the guid to the draft project resource collection.

#### Syntax

```
AddEnterpriseResourceById(Guid resourceId)
```

#### Parameters


|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|resourceId | Guid |The guid of the enterprise resource to add to the collection.|

#### Return Value

QueueJob<br />
The QueueJob includes the JobState property that identifies the result of the AddEnterpriseResource request.



### <a name="getbyguid"></a> GetByGuid(Guid uid)

Gets a draft ProjectResource from the collection with the specified GUID.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|A guid value.

#### Return Value

DraftProjectResource<br />
A DraftProjectResource object.



### <a name="getbyid"></a>GetById(string id)

Gets a draft ProjectResource from the collection with the Id value.

#### Syntax

```
GetById(string id)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| string|The string representation of the project resource GUID.

#### Return Value

DraftProjectResource<br />
The DraftProjectResource with the specified ID.



### <a name="remove"></a> Remove(DraftProjectResource ProjectResource)

Removes the DraftProjectResource from the collection. Returns true if successful.

#### Syntax

```
Remove(DraftProjectResource ProjectResource))
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|ProjectResource | DraftProjectResource |The project to remove from the collection.|

#### Return Value

Boolean<br />
Returns true if successful.
