[comment]: # (Name:EntityLinksCollection)
[comment]: # (Name:Microsoft.ProjectServer.EntityLinksCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EntityLinksCollection class

inherits members from [ClientObjectCollection<EntityLink>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.EntityLinksCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/EntityLinks
```

## <a name="members"></a>Members

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{EntityLinkId}&#39;](#&#39;{EntityLinkId}&#39;)|||&#x2713;|[EntityLink](EntityLink.md)|Gets a [EntityLink](EntityLink.md) from the collection with the specified EntityLinkId.|
|[Add(EntityLinkCreationInformation parameters)](#Add_[EntityLinkCreationInformation]_EntityLinkCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[EntityLink](EntityLink.md)|Adds the [EntityLink](EntityLink.md) that is specified by the [EntityLinkCreationInformation](EntityLinkCreationInformation.md) object to the collection.|
|[GetByGuid(Guid id)](#GetByGuid_Guid_id_)|&#x2713;|&#x2713;|&#x2713;|[EntityLink](EntityLink.md)|Gets a [EntityLink](EntityLink.md) from the collection with the Id value.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the entity links collection.|

<br/>
#### Method Details

#### <a name="&#39;{EntityLinkId}&#39;"></a>&#39;{EntityLinkId}&#39;
 
Gets a [EntityLink](EntityLink.md) from the collection with the specified EntityLinkId.

##### Syntax

```
EntityLink http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/EntityLinks('{EntityLinkId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|EntityLinkId|String|the id of the EntityLink|

##### Return Value

[EntityLink](EntityLink.md)

#### <a name="Add_[EntityLinkCreationInformation]_EntityLinkCreationInformation.md__parameters_"></a>Add([EntityLinkCreationInformation](EntityLinkCreationInformation.md) parameters)
 
Adds the [EntityLink](EntityLink.md) that is specified by the [EntityLinkCreationInformation](EntityLinkCreationInformation.md) object to the collection.

##### Syntax

```
EntityLink Add(EntityLinkCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[EntityLinkCreationInformation](EntityLinkCreationInformation.md)|The properties that can be set when creating a entity link.|

##### Return Value

[EntityLink](EntityLink.md)

#### <a name="GetByGuid_Guid_id_"></a>GetByGuid(Guid id)
 
Gets a [EntityLink](EntityLink.md) from the collection with the Id value.

##### Syntax

```
EntityLink GetByGuid(Guid id)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id|Guid||

##### Return Value

[EntityLink](EntityLink.md)

#### <a name="Update__"></a>Update()
 
Updates the entity links collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[EntityLink](EntityLink.md)<br/>
[EntityLinkCreationInformation](EntityLinkCreationInformation.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
[PublishedTask](PublishedTask.md)<br/>
