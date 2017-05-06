[comment]: # (Name:ResourceEngagementCommentCollection)
[comment]: # (Name:Microsoft.ProjectServer.ResourceEngagementCommentCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ResourceEngagementCommentCollection class

inherits members from [ClientObjectCollection<EngagementComment>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ResourceEngagementCommentCollection 
```
### JSOM

```javascript
PS.ResourceEngagementCommentCollection
```
### REST Interface

Supported.

```
PS.ResourceEngagementCommentCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Engagements('{engagementid}')/Comments
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[EngagementComment](EngagementComment.md)|Gets a [EngagementComment](EngagementComment.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[EngagementComment](EngagementComment.md)|Gets a [EngagementComment](EngagementComment.md) from the collection at the specified index.|

## <a name="seeAlso"></a>See Also

[EngagementComment](EngagementComment.md)<br/>
