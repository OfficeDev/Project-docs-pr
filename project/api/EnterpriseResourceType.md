[comment]: # (Name:EnterpriseResourceType)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)

# <a name="name"></a>EnterpriseResourceType enumeration

<a name="description"></a>Represents the different types of enterprise resources.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum EnterpriseResourceType 
```
### JSOM

```JavaScript
PS.EnterpriseResourceType
```
### REST Interface

EnterpriseResourceType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NotSpecified"></a>NotSpecified|0|Type is not specified|
|<a name="Work"></a>Work|1|People and equipment resources that perform work to accomplish a task.|
|<a name="Material"></a>Material|2|The supplies or other consumable items that are used to complete tasks in a project.|
|<a name="Cost"></a>Cost|3|Costs that used to complete tasks|

## <a name="seeAlso"></a>See Also

[EnterpriseResource](EnterpriseResource.md)<br/>
[EnterpriseResourceCreationInformation](EnterpriseResourceCreationInformation.md)<br/>
[PlanAssignment](PlanAssignment.md)<br/>
