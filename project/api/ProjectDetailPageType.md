[comment]: # (Name:ProjectDetailPageType)
[comment]: # (Name:Microsoft.Office.Project.Server.Library.ProjectDetailPages+PageType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectDetailPageType enumeration

<a name="description"></a>Specifies the type of project detail page (PDP).

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum ProjectDetailPageType 
```
### JSOM

```javascript
PS.ProjectDetailPageType
```
### REST Interface

ProjectDetailPageType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="None"></a>None|0|Indicates that the page usage is not specified.|
|<a name="ProjectDefault"></a>ProjectDefault|1|Indicates that the page can be used within a workflow stage or an enterprise project type (EPT).|
|<a name="NewProject"></a>NewProject|2|Indicates that the page can be used as the creation page for new projects, or as a page within a workflow state or an EPT.|
|<a name="WorkflowStatus"></a>WorkflowStatus|3|Indicates that the page can be used as a status page for workflows, or as a page within a workflow state or an EPT.|

## <a name="seeAlso"></a>See Also

[ProjectDetailPage](ProjectDetailPage.md)<br/>
