[comment]: # (Name:ResourceEngagementCollection)
[comment]: # (Name:Microsoft.ProjectServer.ResourceEngagementCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ResourceEngagementCollection class

inherits members from [ClientObjectCollection<ResourceEngagement>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ResourceEngagementCollection 
```
### JSOM

```javascript
PS.ResourceEngagementCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.ResourceEngagementCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Engagements
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[ResourceEngagement](ResourceEngagement.md)|Gets a [ResourceEngagement](ResourceEngagement.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[ResourceEngagement](ResourceEngagement.md)|Gets a [ResourceEngagement](ResourceEngagement.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{ResourceEngagementId}&#39;](#&#39;{ResourceEngagementId}&#39;)|||&#x2713;|[ResourceEngagement](ResourceEngagement.md)|Gets a [ResourceEngagement](ResourceEngagement.md) from the collection with the specified ResourceEngagementId.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[ResourceEngagement](ResourceEngagement.md)|Gets a [ResourceEngagement](ResourceEngagement.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[ResourceEngagement](ResourceEngagement.md)|Gets a [ResourceEngagement](ResourceEngagement.md) from the collection with the Guid value.|
|[Remove(Engagement engagement)](#Remove_[Engagement]_Engagement.md__engagement_)|&#x2713;|&#x2713;||Boolean|Removes the specified [ResourceEngagement](ResourceEngagement.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the resource engagement collection.|

<br/>
#### Method Details

#### <a name="&#39;{ResourceEngagementId}&#39;"></a>&#39;{ResourceEngagementId}&#39;
 
Gets a [ResourceEngagement](ResourceEngagement.md) from the collection with the specified ResourceEngagementId.

##### Syntax

```
ResourceEngagement http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Engagements('{ResourceEngagementId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|ResourceEngagementId|String|the id of the ResourceEngagement|

##### Return Value

[ResourceEngagement](ResourceEngagement.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [ResourceEngagement](ResourceEngagement.md) from the collection with the Id value.

##### Syntax

```
ResourceEngagement GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [ResourceEngagement](ResourceEngagement.md)|

##### Return Value

[ResourceEngagement](ResourceEngagement.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [ResourceEngagement](ResourceEngagement.md) from the collection with the Guid value.

##### Syntax

```
ResourceEngagement GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [ResourceEngagement](ResourceEngagement.md).|

##### Return Value

[ResourceEngagement](ResourceEngagement.md)

#### <a name="Remove_[Engagement]_Engagement.md__engagement_"></a>Remove([Engagement](Engagement.md) engagement)
 
Removes the specified [ResourceEngagement](ResourceEngagement.md) from the collection.

##### Syntax

```
Boolean Remove(Engagement engagement)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|engagement|[Engagement](Engagement.md)|The [ResourceEngagement](ResourceEngagement.md) to remove.|

##### Return Value

Boolean

#### <a name="Update__"></a>Update()
 
Updates the resource engagement collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[EnterpriseResource](EnterpriseResource.md)<br/>
[ResourceEngagement](ResourceEngagement.md)<br/>
