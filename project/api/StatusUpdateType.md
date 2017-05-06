[comment]: # (Name:StatusUpdateType)
[comment]: # (Name:Microsoft.Office.Project.Server.Library.StatusUpdateType)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)

# <a name="name"></a>StatusUpdateType enumeration

<a name="description"></a>Gets or sets the value that specifies the type of transaction.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum StatusUpdateType 
```
### JSOM

```javascript
PS.StatusUpdateType
```
### REST Interface

StatusUpdateType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="Update"></a>Update|0|Task or assignment update.|
|<a name="Decline"></a>Decline|1|Update is declined.|
|<a name="CreateTask"></a>CreateTask|2|Create task.|
|<a name="Delegate"></a>Delegate|3|Delegated.|
|<a name="CreateAssignment"></a>CreateAssignment|4|Create assignment.|
|<a name="TeamDelegate"></a>TeamDelegate|5|Create individual assignments for each person on a team.|
|<a name="DeleteTask"></a>DeleteTask|6|Delete task.|
|<a name="DeleteAssignment"></a>DeleteAssignment|7|Delete assignment.|

## <a name="seeAlso"></a>See Also

[StatusAssignmentHistoryLine](StatusAssignmentHistoryLine.md)<br/>
