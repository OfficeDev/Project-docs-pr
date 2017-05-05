[comment]: # (Name:ProjectDetailPage)
[comment]: # (Name:Microsoft.ProjectServer.ProjectDetailPage)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectDetailPage class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a project detail page (PDP), which is a Web Part page for creating, viewing, or managing the properties of projects in Project Web App.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectDetailPage 
```
### JSOM

```javascript
PS.ProjectDetailPage
```
### REST Interface

Supported.

```
PS.ProjectDetailPage

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/ProjectDetailPages('{pageid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the project detail page.|
|<a name="Item"></a>Item|&#x2713;|&#x2713;|&#x2713;|SPListItem|Gets an item from the list of items on the project detail page.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the title or name of the project detail page.|
|<a name="PageType"></a>PageType|&#x2713;|&#x2713;|&#x2713;|[ProjectDetailPageType](ProjectDetailPageType.md)|Gets the type of the project detail page.|

## <a name="seeAlso"></a>See Also

[ProjectDetailPageCollection](ProjectDetailPageCollection.md)<br/>
[SPListItem](https://msdn.microsoft.com/library/microsoft.sharepoint.splistitem)<br/>
[Stage](Stage.md)<br/>
[StageDetailPage](StageDetailPage.md)<br/>
