[comment]: # (Name:ProjectType)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-15 22:38:06Z)

# ProjectType

Specifies the type of project.



## Syntax

### CSOM

```C#
Class ProjectType 
```
### JSOM/REST

```
PS.ProjectType
```


## Members



|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|Void|-1||
|MinRequestValue|0||
|Project|0| A standard project.|
|Template|1| A project that is used as a template when creating other projects.|
|Global|2| The enterprise global project.|
|ResGlobal|3| The enterprise resource pool.|
|LightWeightProject|4| Deprecated, do not use.|
|InsertedProject|5| A subproject.|
|MasterProject|6| A master project, which contains one or more subprojects.|
|TimesheetAdminProject|7| Timesheet administrative project, used in upgrades from Microsoft Office Project Server 2007. For more information, see the Reporting database schema reference.|
|NewProject|100| Internal only; do not use.|
|NewOffset|100| Internal only; do not use.|
|NewTemplate|101| Internal only; do not use.|
|MaxRequestValue|101||
|NewGlobal|102| Internal only; do not use.|
|NewResGlobal|103| Internal only; do not use.|
|InactiveProject|1000| Internal only; do not use.|
|InactiveOffset|1000| Internal only; do not use.|
|InactiveTemplate|1001| Internal only; do not use.|
|InactiveGlobal|1002| Internal only; do not use.|




## See Also
