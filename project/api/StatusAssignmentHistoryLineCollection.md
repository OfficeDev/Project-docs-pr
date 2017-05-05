[comment]: # (Name:StatusAssignmentHistoryLineCollection)
[comment]: # (Name:Microsoft.ProjectServer.StatusAssignmentHistoryLineCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StatusAssignmentHistoryLineCollection class

inherits members from [ClientObjectCollection<StatusAssignmentHistoryLine>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents information about assignment history.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StatusAssignmentHistoryLineCollection 
```
### JSOM

```javascript
PS.StatusAssignmentHistoryLineCollection 
```
### REST Interface

Supported.

```
PS.StatusAssignmentHistoryLineCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Assignments/History
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md)|Gets a [StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md)|Gets a [StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md)|Gets a [StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md) from the collection with the Guid value.|

<br/>
#### Method Details
 
#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a [StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md) from the collection with the Guid value.

##### Syntax

```
StatusAssignmentHistoryLine GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md).|

##### Return Value

[StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md)

## <a name="seeAlso"></a>See Also

[StatusAssignment](StatusAssignment.md)<br/>
[StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md)<br/>
