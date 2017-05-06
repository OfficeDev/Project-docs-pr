[comment]: # (Name:ProjectDetailPageCollection)
[comment]: # (Name:Microsoft.ProjectServer.ProjectDetailPageCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectDetailPageCollection class

inherits members from [ClientObjectCollection<ProjectDetailPage>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of project detail pages (PDPs).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectDetailPageCollection 
```
### JSOM

```javascript
PS.ProjectDetailPageCollection
```
### REST Interface

Supported.

```
PS.ProjectDetailPageCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/ProjectDetailPages
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[ProjectDetailPage](ProjectDetailPage.md)|Gets a [ProjectDetailPage](ProjectDetailPage.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[ProjectDetailPage](ProjectDetailPage.md)|Gets a [ProjectDetailPage](ProjectDetailPage.md) from the collection at the specified index.|
|<a name="List"></a>List|&#x2713;|&#x2713;|&#x2713;|SPList|Gets a list of available project detail pages.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{ProjectDetailPageId}&#39;](#&#39;{ProjectDetailPageId}&#39;)|||&#x2713;|[ProjectDetailPage](ProjectDetailPage.md)|Gets a [ProjectDetailPage](ProjectDetailPage.md) from the collection with the specified ProjectDetailPageId.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[ProjectDetailPage](ProjectDetailPage.md)|Gets a [ProjectDetailPage](ProjectDetailPage.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[ProjectDetailPage](ProjectDetailPage.md)|Gets a [ProjectDetailPage](ProjectDetailPage.md) from the collection with the Guid value.|

<br/>
#### Method Details

#### <a name="&#39;{ProjectDetailPageId}&#39;"></a>&#39;{ProjectDetailPageId}&#39;
 
Gets a [ProjectDetailPage](ProjectDetailPage.md) from the collection with the specified ProjectDetailPageId.

##### Syntax

```
ProjectDetailPage http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/ProjectDetailPages('{ProjectDetailPageId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|ProjectDetailPageId|String|the id of the ProjectDetailPage|

##### Return Value

[ProjectDetailPage](ProjectDetailPage.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [ProjectDetailPage](ProjectDetailPage.md) from the collection with the Id value.

##### Syntax

```
ProjectDetailPage GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [ProjectDetailPage](ProjectDetailPage.md)|

##### Return Value

[ProjectDetailPage](ProjectDetailPage.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [ProjectDetailPage](ProjectDetailPage.md) from the collection with the Guid value.

##### Syntax

```
ProjectDetailPage GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [ProjectDetailPage](ProjectDetailPage.md).|

##### Return Value

[ProjectDetailPage](ProjectDetailPage.md)

## <a name="seeAlso"></a>See Also

[EnterpriseProjectType](EnterpriseProjectType.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
[ProjectDetailPage](ProjectDetailPage.md)<br/>
[SPList](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.splist.aspx)<br/>
