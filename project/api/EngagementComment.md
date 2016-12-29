[comment]: # (Name:EngagementComment)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>EngagementComment class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```C#
class EngagementComment 
```
### JSOM

```JavaScript
PS.EngagementComment
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.EngagementComment

http://<sitecollection>/<site>/_api/ProjectServer/?????
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Author"></a>Author|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)||
|<a name="Created"></a>Created|&#x2713;|&#x2713;|&#x2713;|DateTime||
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid||
|<a name="Message"></a>Message|&#x2713;|&#x2713;|&#x2713;|String||

## <a name="seeAlso"></a>See Also

[EngagementCommentCollection](EngagementCommentCollection.md)<br/>
[ProjectEngagementComment](ProjectEngagementComment.md)<br/>
[ResourceEngagementComment](ResourceEngagementComment.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
