[comment]: # (Name:ConstraintType)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# ConstraintType

Specifies the constraint type for a task.



## Syntax

### CSOM

```C#
Class ConstraintType 
```
### JSOM/REST

```
PS.ConstraintType
```


## Members



|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|NotSpecified|0| The task constraint type is not specified. This constant is used in place of a DBNull value.|
|AsSoonAsPossible|1| As soon as possible (ASAP). This is the default value.|
|AsLateAsPossible|2| As late as possible (ALAP).|
|MustStartOn|3| Must start on (MSO).|
|MustFinishOn|4| Must finish on (MFO).|
|StartNoEarlierThan|5| Start no earlier than (SNET).|
|StartNoLaterThan|6| Start no later than (SNLT).|
|FinishNoEarlierThan|7| Finish no earlier than (FNET).|
|FinishNoLaterThan|8| Finish no later than (FNLT).
|




## See Also
