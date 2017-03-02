[comment]: # (Name:ProjectType)
[comment]: # (Name:Microsoft.Office.Project.Server.Library.Project+ProjectType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectType enumeration

<a name="description"></a>Specifies the type of project.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum ProjectType 
```
### JSOM

```javascript
PS.ProjectType
```
### REST Interface

ProjectType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="Void"></a>Void|-1|Internal only; do not use.|
|<a name="MinRequestValue"></a>MinRequestValue|0|Internal only; do not use.|
|<a name="Project"></a>Project|0|A standard project.|
|<a name="Template"></a>Template|1|A project that is used as a template when creating other projects.|
|<a name="Global"></a>Global|2|The enterprise global project.|
|<a name="ResGlobal"></a>ResGlobal|3|The enterprise resource pool.|
|<a name="LightWeightProject"></a>LightWeightProject|4|Deprecated, do not use.|
|<a name="InsertedProject"></a>InsertedProject|5|A subproject.|
|<a name="MasterProject"></a>MasterProject|6|A master project, which contains one or more subprojects.|
|<a name="TimesheetAdminProject"></a>TimesheetAdminProject|7|Timesheet administrative project, used in upgrades from Microsoft Office Project Server 2007. For more information, see the Reporting database schema reference.|
|<a name="NewProject"></a>NewProject|100|Internal only; do not use.|
|<a name="NewOffset"></a>NewOffset|100|Internal only; do not use.|
|<a name="NewTemplate"></a>NewTemplate|101|Internal only; do not use.|
|<a name="MaxRequestValue"></a>MaxRequestValue|101|Internal only; do not use.|
|<a name="NewGlobal"></a>NewGlobal|102|Internal only; do not use.|
|<a name="NewResGlobal"></a>NewResGlobal|103|Internal only; do not use.|
|<a name="InactiveProject"></a>InactiveProject|1000|Internal only; do not use.|
|<a name="InactiveOffset"></a>InactiveOffset|1000|Internal only; do not use.|
|<a name="InactiveTemplate"></a>InactiveTemplate|1001|Internal only; do not use.|
|<a name="InactiveGlobal"></a>InactiveGlobal|1002|Internal only; do not use.|

## <a name="seeAlso"></a>See Also

[Project](Project.md)<br/>
