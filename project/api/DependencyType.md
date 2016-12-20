[comment]: # (Name:DependencyType)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# DependencyType

Specifies the type of dependency to establish between two tasks.



## Syntax

### CSOM

```C#
Class DependencyType 
```
### JSOM/REST

```
PS.DependencyType
```


## Members



|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|FinishFinish|0| Finish to finish (FF) task link type. The successor task B cannot finish until the predecessor task A finishes.|
|FinishStart|1| This is the default value. Finish to start (FS) task link type. The predecessor task A must finish before the successor task B can start.|
|StartFinish|2| Start to finish (SF) task link type. The predecessor task A must start before the successor task B finishes. This is the least common of the four dependency types.|
|StartStart|3| Start to start (SS) task link type. The successor task B cannot start until the predecessor task A starts.
|




## See Also
