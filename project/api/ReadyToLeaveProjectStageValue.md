[comment]: # (Name:ReadyToLeaveProjectStageValue)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-15 22:38:07Z)

# ReadyToLeaveProjectStageValue

Specifies the project stage requirements in a Project Server workflow, to help determine whether the workflow is ready to leave the stage.



## Syntax

### CSOM

```C#
Class ReadyToLeaveProjectStageValue 
```
### JSOM/REST

```
PS.ReadyToLeaveProjectStageValue
```


## Members



|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|Ready|0| The stage is complete; the workflow is ready to leave the project stage.|
|RequiresFieldsAndDrivers|1| The workflow stage is not complete; it requires fields and drivers.|
|RequiresDrivers|2| The workflow stage is not complete; it requires drivers.|
|RequiresFields|3| The workflow stage is not complete; it requires field values.
|




## See Also
