[comment]: # (Name:UtilizationType)
[comment]: # (Name:Microsoft.Office.Project.Server.Library.ResourcePlan+UtilizationType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>UtilizationType enumeration

<a name="description"></a>Specifies the type of resource use for the current resource plan.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum UtilizationType 
```
### JSOM

```javascript
PS.UtilizationType
```
### REST Interface

UtilizationType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="FromProjectPlan"></a>FromProjectPlan|0|Not supported. Summary resource assignments are derived from the project assignments.|
|<a name="FromResourcePlan"></a>FromResourcePlan|1|Not supported. Summary resource assignments are derived from the resource plan assignments.|
|<a name="FromProjectPlanThenResourcePlan"></a>FromProjectPlanThenResourcePlan|2|Not supported. Summary resource assignments are derived from the project assignments through the utilization date, then from the resource plan assignments after the utilization date.|

## <a name="seeAlso"></a>See Also

