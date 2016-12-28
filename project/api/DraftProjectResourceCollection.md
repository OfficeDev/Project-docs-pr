[comment]: # (Name:DraftProjectResourceCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

Represents a collection of [DraftProjectResource](DraftProjectResource.md) objects.

## Syntax

### CSOM

```C#
class DraftProjectResourceCollection 
```
### JSOM

```JavaScript
PS.DraftProjectResourceCollection
```

### REST Interface

This resource supports GET, POST, PUT, PATCH,  and MERGE HTTP commands.

```
PS.DraftProjectResourceCollection

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Draft/ProjectResources
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[DraftProjectResource](DraftProjectResource.md)|Gets a [DraftProjectResource](DraftProjectResource.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[DraftProjectResource](DraftProjectResource.md)|Gets a [DraftProjectResource](DraftProjectResource.md) from the collection at the specified index.|

### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{DraftProjectResourceId}&#39;](#&#39;{DraftProjectResourceId}&#39;)|||&#x2713;|[DraftProjectResource](DraftProjectResource.md)|Gets a [DraftProjectResource](DraftProjectResource.md) from the collection with the specified DraftProjectResourceId.|
|[Add(ProjectResourceCreationInformation parameters)](#Add_[ProjectResourceCreationInformation]_ProjectResourceCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[DraftProjectResource](DraftProjectResource.md)|Adds a new project resource that is specified by the [ProjectResourceCreationInformation](ProjectResourceCreationInformation.md) object to the collection.|
|[AddEnterpriseResource(EnterpriseResource resource)](#AddEnterpriseResource_[EnterpriseResource]_EnterpriseResource.md__resource_)|&#x2713;|&#x2713;||[DraftProjectResource](DraftProjectResource.md)|Adds an existing enterprise resource to the draft project resource collection.|
|[AddEnterpriseResourceById(Guid resourceId)](#AddEnterpriseResourceById_Guid_resourceId_)|||&#x2713;|[QueueJob](QueueJob.md)|Adds an existing enterprise resource with the specified Id value to the draft project resource collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[DraftProjectResource](DraftProjectResource.md)|Gets a draft project resource from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[DraftProjectResource](DraftProjectResource.md)|Gets a draft project resource from the collection with the Id value.|
|[Remove(DraftProjectResource resource)](#Remove_[DraftProjectResource]_DraftProjectResource.md__resource_)|&#x2713;|&#x2713;||Boolean|Removes the specified draft project resource from the collection.|

<br/>
#### Method Details

#### <a name="&#39;{DraftProjectResourceId}&#39;"></a>&#39;{DraftProjectResourceId}&#39;
 
Gets a [DraftProjectResource](DraftProjectResource.md) from the collection with the specified DraftProjectResourceId.

##### Syntax

```
DraftProjectResource http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Draft/ProjectResources('{DraftProjectResourceId}')
```

##### Parameters

None

##### Return Value

[DraftProjectResource](DraftProjectResource.md)

#### <a name="Add_[ProjectResourceCreationInformation]_ProjectResourceCreationInformation.md__parameters_"></a>Add([ProjectResourceCreationInformation](ProjectResourceCreationInformation.md) parameters)

Adds a new [ProjectResource](ProjectResource.md) that is specified by the [ProjectResourceCreationInformation](ProjectResourceCreationInformation.md) object to the collection.

##### Syntax

```
DraftProjectResource Add(ProjectResourceCreationInformation parameters)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[ProjectResourceCreationInformation](ProjectResourceCreationInformation.md)|The properties of the project resource to create.

##### Return Value

[DraftProjectResource](DraftProjectResource.md)<br />
The added [DraftProjectResource](DraftProjectResource.md).

#### <a name="AddEnterpriseResource_[EnterpriseResource]_EnterpriseResource.md__resource_"></a>AddEnterpriseResource([EnterpriseResource](EnterpriseResource.md) resource)

Adds an existing enterprise resource to the draft project resource collection.

##### Syntax

```
DraftProjectResource AddEnterpriseResource(EnterpriseResource resource)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|resource|[EnterpriseResource](EnterpriseResource.md)|The enterprise resource to add.

##### Return Value

[DraftProjectResource](DraftProjectResource.md)<br />
The added [DraftProjectResource](DraftProjectResource.md).



#### <a name="AddEnterpriseResourceById_Guid_resourceId_"></a>AddEnterpriseResourceById(Guid resourceId)
 
Adds an existing enterprise resource specified by the Guid to the draft project resource collection.

##### Syntax

```
QueueJob AddEnterpriseResourceById(Guid resourceId)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|resourceId|Guid|The guid of the enterprise resource to add to the collection.|

#### Return Value

[QueueJob](QueueJob.md)<br />
The [QueueJob](QueueJob.md) includes the JobState property that identifies the result of the AddEnterpriseResource request.



#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)

Gets a [DraftProjectResource](DraftProjectResource.md) from the collection with the specified GUID.

##### Syntax

```
DraftProjectResource GetByGuid(Guid uid)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The project resource guid.|

##### Return Value

[DraftProjectResource](DraftProjectResource.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a [DraftProjectResource](DraftProjectResource.md) from the collection with the Id value.

##### Syntax

```
DraftProjectResource GetById(String objectId)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The string representation of the project resource GUID.

##### Return Value

[DraftProjectResource](DraftProjectResource.md)<br />
The [DraftProjectResource](DraftProjectResource.md) with the specified ID.



#### <a name="Remove_[DraftProjectResource]_DraftProjectResource.md__resource_"></a>Remove([DraftProjectResource](DraftProjectResource.md) resource)

Removes the [DraftProjectResource](DraftProjectResource.md) from the collection. Returns true if successful.

##### Syntax

```
Boolean Remove(DraftProjectResource resource)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|resource|[DraftProjectResource](DraftProjectResource.md)|The draft project resource to remove.

##### Return Value

Boolean<br />
Returns true if successful.
## <a name="seeAlso"></a>See Also

[DraftProject](DraftProject.md)<br/>
[DraftProjectResource](DraftProjectResource.md)<br/>
[ProjectResourceCreationInformation](ProjectResourceCreationInformation.md)<br/>
