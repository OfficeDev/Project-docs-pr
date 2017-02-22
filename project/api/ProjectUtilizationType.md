[comment]: # (Name:ProjectUtilizationType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectUtilizationType enumeration

<a name="description">Specifies the type of resource utilization.</a>

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum ProjectUtilizationType 
```
### JSOM

```JavaScript
PS.ProjectUtilizationType
```
### REST Interface

ProjectUtilizationType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="ProjectPlan"></a>ProjectPlan|0|Summary resource assignments are derived from the project assignments.|
|<a name="ResourceEngagements"></a>ResourceEngagements|1|Summary resource assignments are derived from resource engagements.|
|<a name="ProjectPlanUntil"></a>ProjectPlanUntil|2|Summary resource assignments are derived from the project assignments up to the utilization date and then from resource engagements.|

## <a name="seeAlso"></a>See Also

[DraftProject](DraftProject.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
[ResourcePlan](ResourcePlan.md)<br/>
