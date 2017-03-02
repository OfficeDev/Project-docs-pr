[comment]: # (Name:EntityLink)
[comment]: # (Name:Microsoft.ProjectServer.EntityLink)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EntityLink class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.EntityLink

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/EntityLinks('EntityLink.Id')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Created"></a>Created|&#x2713;|&#x2713;|&#x2713;|DateTime||
|<a name="EntityLinkType"></a>EntityLinkType|&#x2713;|&#x2713;|&#x2713;|[EntityLinkType](EntityLinkType.md)||
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid||
|<a name="Url"></a>Url|&#x2713;|&#x2713;|&#x2713;|String||

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the entity link object.|

<br/>
#### Method Details
 
#### <a name="DeleteObject__"></a>DeleteObject()

Deletes the entity link object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[EntityLinkCreationInformation](EntityLinkCreationInformation.md)<br/>
[EntityLinksCollection](EntityLinksCollection.md)<br/>
[ProjectEntityLinksCollection](ProjectEntityLinksCollection.md)<br/>
[TaskEntityLinksCollection](TaskEntityLinksCollection.md)<br/>
