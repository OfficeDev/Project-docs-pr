[comment]: # (Name:DeletedPublishedAssignmentCollection)
[comment]: # (Name:Microsoft.ProjectServer.DeletedPublishedAssignmentCollection)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>DeletedPublishedAssignmentCollection class

inherits members from [ClientObjectCollection<DeletedPublishedAssignment>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Retrieves the published assignments that have been deleted from the draft project and the project has been published.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class DeletedPublishedAssignmentCollection 
```
### JSOM

```javascript
PS.DeletedPublishedAssignmentCollection
```
### REST Interface

Supported.

```
PS.DeletedPublishedAssignmentCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/GetDeletedPublishedAssignments('datetime')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[DeletedPublishedAssignment](DeletedPublishedAssignment.md)|Gets a [DeletedPublishedAssignment](DeletedPublishedAssignment.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[DeletedPublishedAssignment](DeletedPublishedAssignment.md)|Gets a [DeletedPublishedAssignment](DeletedPublishedAssignment.md) from the collection at the specified index.|

## <a name="seeAlso"></a>See Also

[DeletedPublishedAssignment](DeletedPublishedAssignment.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
