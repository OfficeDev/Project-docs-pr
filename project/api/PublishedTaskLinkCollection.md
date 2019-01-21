[comment]: # (Name:PublishedTaskLinkCollection)
[comment]: # (Name:Microsoft.ProjectServer.PublishedTaskLinkCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PublishedTaskLinkCollection class

inherits members from [ClientObjectCollection<PublishedTaskLink>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of task links in a published project.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PublishedTaskLinkCollection 
```
### JSOM

```javascript
PS.PublishedTaskLinkCollection
```
### REST Interface

Supported.

```
PS.PublishedTaskLinkCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectid}')/TaskLinks
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[PublishedTaskLink](PublishedTaskLink.md)|Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[PublishedTaskLink](PublishedTaskLink.md)|Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{PublishedTaskLinkId}&#39;](#&#39;{PublishedTaskLinkId}&#39;)|||&#x2713;|[PublishedTaskLink](PublishedTaskLink.md)|Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the specified PublishedTaskLinkId.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLink](PublishedTaskLink.md)|Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the Guid value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[PublishedTaskLink](PublishedTaskLink.md)|Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the Id value.|

<br/>
#### Method Details

#### <a name="&#39;{PublishedTaskLinkId}&#39;"></a>&#39;{PublishedTaskLinkId}&#39;
 
Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the specified PublishedTaskLinkId.

##### Syntax

```
PublishedTaskLink http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectid}')/TaskLinks('{PublishedTaskLinkId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|PublishedTaskLinkId|String|the id of the PublishedTaskLink|

##### Return Value

[PublishedTaskLink](PublishedTaskLink.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the Guid value.

##### Syntax

```
PublishedTaskLink GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [PublishedTaskLink](PublishedTaskLink.md)|

##### Return Value

[PublishedTaskLink](PublishedTaskLink.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [PublishedTaskLink](PublishedTaskLink.md) from the collection with the Id value.

##### Syntax

```
PublishedTaskLink GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [PublishedTaskLink](PublishedTaskLink.md).|

##### Return Value

[PublishedTaskLink](PublishedTaskLink.md)

## <a name="seeAlso"></a>See Also

[PublishedProject](PublishedProject.md)<br/>
[PublishedTask](PublishedTask.md)<br/>
[PublishedTaskLink](PublishedTaskLink.md)<br/>
