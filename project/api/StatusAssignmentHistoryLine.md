[comment]: # (Name:StatusAssignmentHistoryLine)
[comment]: # (Name:Microsoft.ProjectServer.StatusAssignmentHistoryLine)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StatusAssignmentHistoryLine class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents assignment history information for a transaction.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StatusAssignmentHistoryLine 
```
### JSOM

```javascript
PS.StatusAssignmentHistoryLine
```
### REST Interface

Supported.

```
PS.StatusAssignmentHistoryLine

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Assignments/History('{transactionId}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Author"></a>Author|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the author that created the transaction.|
|<a name="Comment"></a>Comment|&#x2713;|&#x2713;|&#x2713;|String|Gets the comment made by the author for the transaction.|
|<a name="Decision"></a>Decision|&#x2713;|&#x2713;|&#x2713;|[StatusApprovalType](StatusApprovalType.md)|Gets the decision the project manager has taken for the transaction.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the transactionn Guid.|
|<a name="Submitted"></a>Submitted|&#x2713;|&#x2713;|&#x2713;|DateTime|Specifies the date when the transaction was submitted.|
|<a name="UpdateType"></a>UpdateType|&#x2713;|&#x2713;|&#x2713;|[StatusUpdateType](StatusUpdateType.md)|Gets the type of transaction.|

## <a name="seeAlso"></a>See Also

[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
[StatusAssignmentHistoryLineCollection](StatusAssignmentHistoryLineCollection.md)<br/>
