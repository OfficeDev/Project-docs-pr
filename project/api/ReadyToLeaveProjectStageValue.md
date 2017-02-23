[comment]: # (Name:ReadyToLeaveProjectStageValue)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>ReadyToLeaveProjectStageValue enumeration

<a name="description"></a>Specifies the project stage requirements in a Project Server workflow, to help determine whether the workflow is ready to leave the stage.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum ReadyToLeaveProjectStageValue 
```
### JSOM

```JavaScript
PS.ReadyToLeaveProjectStageValue
```
### REST Interface

ReadyToLeaveProjectStageValue enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="Ready"></a>Ready|0|The stage is complete; the workflow is ready to leave the project stage.|
|<a name="RequiresFieldsAndDrivers"></a>RequiresFieldsAndDrivers|1|The workflow stage is not complete; it requires fields and drivers.|
|<a name="RequiresDrivers"></a>RequiresDrivers|2|The workflow stage is not complete; it requires drivers.|
|<a name="RequiresFields"></a>RequiresFields|3|The workflow stage is not complete; it requires field values.|

## <a name="seeAlso"></a>See Also

[Project](Project.md)<br/>
[WorkflowActivities](WorkflowActivities.md)<br/>
