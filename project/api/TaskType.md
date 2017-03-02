[comment]: # (Name:TaskType)
[comment]: # (Name:Microsoft.Office.Project.Scheduling.TaskType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>TaskType enumeration

<a name="description"></a>Specifies whether the task type in a project is fixed units, fixed work, or fixed duration.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum TaskType 
```
### JSOM

```javascript
PS.TaskType
```
### REST Interface

TaskType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="FixedUnits"></a>FixedUnits|0|The task is fixed units (Default).  The number of Assignment Units remains constant, regardless of the amount of work or the duration on the task.|
|<a name="FixedDuration"></a>FixedDuration|1|The task is fixed duration.  The duration of the task remains constant, regardless of the number of resources (Assignment Units) that are assigned or the amount of work|
|<a name="FixedWork"></a>FixedWork|2|The task is fixed work.  The amount of work remains constant, regardless of any change in duration or the number of resources (Assignment Units) that are assigned to the task.|
|<a name="Dummy"></a>Dummy|1000|The task is a placeholder; for internal use only.|

## <a name="seeAlso"></a>See Also

[DraftProject](DraftProject.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
[Task](Task.md)<br/>
