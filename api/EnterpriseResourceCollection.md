# EnterpriseResourceCollection class

Represents a collection of [EnterpriseResource](EnterpriseResource.md) objects.

## Syntax

### CSOM

```
class EnterpriseResourceCollection inherits ClientObjectCollection(of EnterpriseResource)
```

### JSOM

```
PS.EnterpriseResourceCollection
```

### REST Interface

This resource supports GET and POST HTTP commands:

```
http://<sitecollection>/<site>/_api/ProjectServer/EnterpriseResources
```

## Members

### Properties

<!-- The following table has left-aligned columns 1,5,6; and center-aligned columns 2,3,4. -->

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|item| |&#x2713;| |[EnterpriseResource](EnterpriseResource.md)|Gets the current resource from the collection.|


### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[Add(EnterpriseResourceCreationInformation ercinfo)](#add)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Adds the enterprise resource that is specified by the [EnterpriseResourceCreationInformation](EnterpriseResourceCreationInformation) object to the collection.|
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Get an enterprise resource from the collection with the specified GUID.|
|[GetById(String Id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets an enterprise resource from the collection with the Name value.|
|[GetByUser(SPUser user)](#getbyuser)|&#x2713;|&#x2713;||[EnterpriseResource](EnterpriseResource.md)|Returns an enterprise resource from the collection linked to the SharePoint user.|
|[Remove(EnterpriseResource resource)](#remove)|&#x2713;|&#x2713;||Boolean|Removes the specified enterprise resource from a project.|
|[Self()](#self)|||&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets the current member of the collection.|
|[Update()](#update)|&#x2713;|&#x2713;|&#x2713;|Void|Updates the enterprise resource collection.|


## Method Details

### <a name="add"></a> Add(EnterpriseResourceCreationInformation ercinfo)

Adds the enterprise resource that is specified by the [EnterpriseResourceCreationInformation](EnterpriseResourceCreationInformation.md) object to the collection.

#### Syntax

```
Add(EnterpriseResourceCreationInformation ercinfo)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|ercinfo| [EnterpriseResourceCreationInformation](EnterpriseResourceCreationInformation)|Contains the properties that can be set when creating an enterprise resource.|

#### Return Value

[EnterpriseResource](EnterpriseResource.md)<br />
An [EnterpriseResource](EnterpriseResource.md) object.



### <a name="getbyguid"></a> GetByGuid(Guid uid)

Get an enterprise resource from the collection with the specified GUID.

#### Syntax

```
GetByGuid(Guid uid)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid|A guid value.

#### Return Value

[EnterpriseResource](EnterpriseResource.md)<br />
An [EnterpriseResource](EnterpriseResource.md) object.



### <a name="getbyid"></a>GetById(string id)

Gets an enterprise resource from the collection with the Id value.

#### Syntax

```
GetById(string id)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| string|The string representation of the project resource GUID.

#### Return Value

[EnterpriseResource](EnterpriseResource.md)<br />
An [EnterpriseResource](EnterpriseResource.md) object.



### <a name="getbyuser"></a> GetByUser(SPUser user)

Returns an enterprise resource from the collection linked to the SharePoint user.

#### Syntax

```
GetByUser(SPUser user)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|user| SPUser|A SharePoint user object.

#### Return Value

[EnterpriseResource](EnterpriseResource.md)<br />
An [EnterpriseResource](EnterpriseResource.md) object.



### <a name="remove"></a> Remove(EnterpriseResource resource)

Removes the specified enterprise resource from a project.

#### Syntax

```
Remove(EnterpriseResource resource)
```

#### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|resource| [EnterpriseResource](EnterpriseResource.md)|The enterprise resource to remove.

#### Return Value

Boolean<br />
True if the object is removed from the collection; otherwise, False.



### <a name="self"></a> Self()

Gets the current enterprise resource from the collection.

#### Syntax

```
Self()
```

#### Parameters

none

#### Return Value

[EnterpriseResource](EnterpriseResource.md)<br />
An [EnterpriseResource](EnterpriseResource.md) object.



### <a name="update"></a> Update()

Updates the enterprise resource collection.

#### Syntax

```
Update()
```

#### Parameters

none

#### Return Value

void

