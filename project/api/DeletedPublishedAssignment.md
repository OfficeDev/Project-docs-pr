[comment]: # (Name:DeletedPublishedAssignment)
[comment]: # (Name:Microsoft.ProjectServer.DeletedPublishedAssignment)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>DeletedPublishedAssignment class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents an published assignment that has been deleted from the draft project and the project has been published.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class DeletedPublishedAssignment 
```
### JSOM

```javascript
PS.DeletedPublishedAssignment
```
### REST Interface

Supported.

Endpoint returns a collection of published assignments.  No way to query for specific assignments or projects.

```
PS.DeletedPublishedAssignment

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/GetDeletedPublishedAssignments('datetime')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
[!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="DeletedDate"></a>DeletedDate|&#x2713;|&#x2713;|&#x2713;|DateTime|When the assignment was deleted.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|The Id of the assignment.|
|<a name="ProjectId"></a>ProjectId|&#x2713;|&#x2713;|&#x2713;|Guid|The Id of the project the assignment was from.|

## <a name="seeAlso"></a>See Also

[DeletedPublishedAssignmentCollection](DeletedPublishedAssignmentCollection.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
