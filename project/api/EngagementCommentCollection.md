[comment]: # (Name:EngagementCommentCollection)
[comment]: # (Name:Microsoft.ProjectServer.EngagementCommentCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EngagementCommentCollection class

inherits members from [ClientObjectCollection<EngagementComment>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EngagementCommentCollection 
```
### JSOM

```javascript
PS.EngagementCommentCollection
```
### REST Interface

Supported.

```
PS.EngagementCommentCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/?????
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[EngagementComment](EngagementComment.md)|Gets a [EngagementComment](EngagementComment.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[EngagementComment](EngagementComment.md)|Gets a [EngagementComment](EngagementComment.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add(String comment)](#Add_String_comment_)|&#x2713;|&#x2713;|&#x2713;|[EngagementComment](EngagementComment.md)||

<br/>
#### Method Details

#### <a name="Add_String_comment_"></a>Add(String comment)
 

##### Syntax

```
EngagementComment Add(String comment)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|comment|String||

##### Return Value

[EngagementComment](EngagementComment.md)

## <a name="seeAlso"></a>See Also

[Engagement](Engagement.md)<br/>
[EngagementComment](EngagementComment.md)<br/>
