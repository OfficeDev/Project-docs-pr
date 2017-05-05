[comment]: # (Name:ProjectEngagementCollection)
[comment]: # (Name:Microsoft.ProjectServer.ProjectEngagementCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectEngagementCollection class

inherits members from [ClientObjectCollection<ProjectEngagement>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectEngagementCollection 
```
### JSOM

```javascript
PS.ProjectEngagementCollection
```
### REST Interface

Supported.

```
PS.ProjectEngagementCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Engagements
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[ProjectEngagement](ProjectEngagement.md)|Gets a [ProjectEngagement](ProjectEngagement.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[ProjectEngagement](ProjectEngagement.md)|Gets a [ProjectEngagement](ProjectEngagement.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{ProjectEngagementId}&#39;](#&#39;{ProjectEngagementId}&#39;)|||&#x2713;|[ProjectEngagement](ProjectEngagement.md)|Gets a [ProjectEngagement](ProjectEngagement.md) from the collection with the specified ProjectEngagementId.|
|[Add(ProjectEngagementCreationInformation parameters)](#Add_[ProjectEngagementCreationInformation]_ProjectEngagementCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[ProjectEngagement](ProjectEngagement.md)|Adds the [ProjectEngagement](ProjectEngagement.md) that is specified by the [ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[ProjectEngagement](ProjectEngagement.md)|Gets a [ProjectEngagement](ProjectEngagement.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[ProjectEngagement](ProjectEngagement.md)|Gets a [ProjectEngagement](ProjectEngagement.md) from the collection with the Guid value.|
|[Remove(Engagement engagement)](#Remove_[Engagement]_Engagement.md__engagement_)|&#x2713;|&#x2713;||Boolean|Removes the specified [ProjectEngagement](ProjectEngagement.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the project engagement collection.|

<br/>
#### Method Details

#### <a name="&#39;{ProjectEngagementId}&#39;"></a>&#39;{ProjectEngagementId}&#39;
 
Gets a [ProjectEngagement](ProjectEngagement.md) from the collection with the specified ProjectEngagementId.

##### Syntax

```
ProjectEngagement http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Engagements('{ProjectEngagementId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|ProjectEngagementId|String|the id of the ProjectEngagement|

##### Return Value

[ProjectEngagement](ProjectEngagement.md)

#### <a name="Add_[ProjectEngagementCreationInformation]_ProjectEngagementCreationInformation.md__parameters_"></a>Add([ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md) parameters)
 
Adds the [ProjectEngagement](ProjectEngagement.md) that is specified by the [ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md) object to the collection.

##### Syntax

```
ProjectEngagement Add(ProjectEngagementCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md)|The properties that can be set when creating a project engagement.|

##### Return Value

[ProjectEngagement](ProjectEngagement.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [ProjectEngagement](ProjectEngagement.md) from the collection with the Id value.

##### Syntax

```
ProjectEngagement GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [ProjectEngagement](ProjectEngagement.md)|

##### Return Value

[ProjectEngagement](ProjectEngagement.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [ProjectEngagement](ProjectEngagement.md) from the collection with the Guid value.

##### Syntax

```
ProjectEngagement GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [ProjectEngagement](ProjectEngagement.md).|

##### Return Value

[ProjectEngagement](ProjectEngagement.md)

#### <a name="Remove_[Engagement]_Engagement.md__engagement_"></a>Remove([Engagement](Engagement.md) engagement)
 
Removes the specified [ProjectEngagement](ProjectEngagement.md) from the collection.

##### Syntax

```
Boolean Remove(Engagement engagement)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|engagement|[Engagement](Engagement.md)|The [ProjectEngagement](ProjectEngagement.md) to remove.|

##### Return Value

Boolean

#### <a name="Update__"></a>Update()
 
Updates the project engagement collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[Project](Project.md)<br/>
[ProjectEngagement](ProjectEngagement.md)<br/>
[ProjectEngagementCreationInformation](ProjectEngagementCreationInformation.md)<br/>
