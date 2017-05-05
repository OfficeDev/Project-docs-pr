[comment]: # (Name:ProjectCollection)
[comment]: # (Name:Microsoft.ProjectServer.ProjectCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectCollection class

inherits members from [ClientObjectCollection<PublishedProject>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [PublishedProject](PublishedProject.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectCollection 
```

### JSOM

```javascript
PS.ProjectCollection

```

### REST Interface

Supported.

```
PS.ProjectCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[PublishedProject](PublishedProject.md)|Gets a [PublishedProject](PublishedProject.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[PublishedProject](PublishedProject.md)|Gets a [PublishedProject](PublishedProject.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{PublishedProjectId}&#39;](#&#39;{PublishedProjectId}&#39;)|||&#x2713;|[PublishedProject](PublishedProject.md)|Gets a [PublishedProject](PublishedProject.md) from the collection with the specified PublishedProjectId.|
|[Add(ProjectCreationInformation parameters)](#Add_[ProjectCreationInformation]_ProjectCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Adds the [PublishedProject](PublishedProject.md) that is specified by the [ProjectCreationInformation](ProjectCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Gets a [PublishedProject](PublishedProject.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[PublishedProject](PublishedProject.md)|Gets a [PublishedProject](PublishedProject.md) from the collection with the Guid value.|
|[Remove(PublishedProject project)](#Remove_[PublishedProject]_PublishedProject.md__project_)|&#x2713;|&#x2713;||Boolean|Removes the specified [PublishedProject](PublishedProject.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||[QueueJob](QueueJob.md)|Updates the project collection.|
|[Validate()](#Validate__)|&#x2713;|&#x2713;|&#x2713;|void|Validates pending changes to the project and all of the entities that it contains without saving them.|

<br/>
#### Method Details

#### <a name="&#39;{PublishedProjectId}&#39;"></a>&#39;{PublishedProjectId}&#39;
 
Gets a [PublishedProject](PublishedProject.md) from the collection with the specified PublishedProjectId.

##### Syntax

```
PublishedProject http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{PublishedProjectId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|PublishedProjectId|String|the id of the PublishedProject|

##### Return Value

[PublishedProject](PublishedProject.md)

#### <a name="Add_[ProjectCreationInformation]_ProjectCreationInformation.md__parameters_"></a>Add([ProjectCreationInformation](ProjectCreationInformation.md) parameters)

Adds the [PublishedProject](PublishedProject.md) that is specified by the [ProjectCreationInformation](ProjectCreationInformation.md) object to the collection.

##### Syntax

```
PublishedProject Add(ProjectCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[ProjectCreationInformation](ProjectCreationInformation.md)|The properties that can be set when creating a published project.|

##### Return Value

[PublishedProject](PublishedProject.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)

Gets a [PublishedProject](PublishedProject.md) from the collection with the Id value.

##### Syntax

```
PublishedProject GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [PublishedProject](PublishedProject.md)|

##### Return Value
[PublishedProject](PublishedProject.md)<br />
The [PublishedProject](PublishedProject.md) with the specified guid.


#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a [PublishedProject](PublishedProject.md) from the collection with the Guid value.

##### Syntax

```
PublishedProject GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [PublishedProject](PublishedProject.md).|

##### Return Value

[PublishedProject](PublishedProject.md)<br />
The [PublishedProject](PublishedProject.md) with the specified ID.

#### <a name="Remove_[PublishedProject]_PublishedProject.md__project_"></a>Remove([PublishedProject](PublishedProject.md) project)

Removes the specified [PublishedProject](PublishedProject.md) from the collection.

##### Syntax

```
Boolean Remove(PublishedProject project)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|project|[PublishedProject](PublishedProject.md)|The [PublishedProject](PublishedProject.md) to remove.|

##### Return Value

Boolean

#### <a name="Update__"></a>Update()

Updates the project collection.

##### Syntax

```
QueueJob Update()
```

##### Parameters

None

##### Return Value
[QueueJob](QueueJob.md)<br />
The [QueueJob](QueueJob.md) includes the JobState property that identifies the result of the update request.

[QueueJob](QueueJob.md)

#### <a name="Validate__"></a>Validate()

Validates pending changes to the project and all of the entities that it contains without saving them.

##### Syntax

```
void Validate()
```

##### Parameters

None

##### Return Value

void

## Remarks

Project Server creates a virtual [PublishedProject](PublishedProject.md) object for each draft project that has not yet been published. A virtual published project ensures that a draft project can be retrieved through the ProjectCollection object, whether it has been published or not.

For example, if you create a draft project, and then read all projects with the CSOM, ProjectCollection object contains the unpublished draft project. 

You can determine whether a project has been published by the value of the PublishedProject.LastPublishedDate property, which is inherited from Project.LastPublishedDate. For an unpublished project, the LastPublishedDate property value is DateTime.Min (1/1/0001).


## <a name="seeAlso"></a>See Also

[ProjectContext](ProjectContext.md)<br/>
[ProjectCreationInformation](ProjectCreationInformation.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
