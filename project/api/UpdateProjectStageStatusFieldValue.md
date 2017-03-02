[comment]: # (Name:UpdateProjectStageStatusFieldValue)
[comment]: # (Name:Microsoft.Office.Project.Server.Library.UpdateProjectStageStatusFieldValue)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>UpdateProjectStageStatusFieldValue enumeration

<a name="description"></a>Specifies the status of the project stage in a Project Server workflow.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum UpdateProjectStageStatusFieldValue 
```
### JSOM

```javascript
PS.UpdateProjectStageStatusFieldValue
```
### REST Interface

UpdateProjectStageStatusFieldValue enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="None"></a>None|0|The workflow stage status field is empty.|
|<a name="WaitingForInput"></a>WaitingForInput|1|The workflow stage is waiting for input.|
|<a name="WaitingForApproval"></a>WaitingForApproval|2|The workflow stage is waiting for approval.|
|<a name="WorkflowProcessing"></a>WorkflowProcessing|3|The workflow stage is processing.|

## <a name="seeAlso"></a>See Also

[Project](Project.md)<br/>
[WorkflowActivities](WorkflowActivities.md)<br/>
