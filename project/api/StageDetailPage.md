[comment]: # (Name:StageDetailPage)
[comment]: # (Name:Microsoft.ProjectServer.StageDetailPage)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StageDetailPage class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a project detail page (PDP) for a workflow stage.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StageDetailPage 
```
### JSOM

```javascript
PS.StageDetailPage
```
### REST Interface

Supported.

```
PS.StageDetailPage

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Stages('{stageid}')/ProjectDetailPages('{pageid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the PDP. Read-write String.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the PDP. Read-only Guid.|
|<a name="Page"></a>Page|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[ProjectDetailPage](ProjectDetailPage.md)|Gets or sets the PDP in a workflow stage. Read/write ProjectDetailPage.|
|<a name="Position"></a>Position|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the position of the PDP relative to the other PDPs that are displayed in the workflow stage.|
|<a name="RequiresAttention"></a>RequiresAttention|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the PDP requires attention.|
|<a name="Stage"></a>Stage|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets a link to the related workflow stage for the PDP. Read-only Stage. Read-only Stage.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the stage detail page object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the stage detail page object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[StageDetailPageCollection](StageDetailPageCollection.md)<br/>
[StageDetailPageCreationInformation](StageDetailPageCreationInformation.md)<br/>
