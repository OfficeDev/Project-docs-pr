[comment]: # (Name:ResourceType)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)

# <a name="name"></a>ResourceType enumeration

<a name="description"></a>Specifies the types of resources.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum ResourceType 
```
### JSOM

```JavaScript
PS.ResourceType
```
### REST Interface

ResourceType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="WinProjSummaryResource"></a>WinProjSummaryResource|-4|Internal use only; do not use.|
|<a name="WinProjUnassignedResource"></a>WinProjUnassignedResource|-3|Internal use only; do not use.|
|<a name="WinProjUnknownResource"></a>WinProjUnknownResource|-2|Internal use only; do not use.|
|<a name="WinProjScratchpadResource"></a>WinProjScratchpadResource|-1|Internal use only; do not use.|
|<a name="PureUser"></a>PureUser|1|Pure user, such as Admins. Cannot be assigned to Project tasks; can use Project Web Access.|
|<a name="WorkResource"></a>WorkResource|2|Work resource. This is the default value. Can be assigned to Project tasks; can log on to Project Web Access.|
|<a name="CAN_LOG_IN_MAXIMUM"></a>CAN_LOG_IN_MAXIMUM|20|Any resource with a resource-type value less than this value can log on to Project Web Access.|
|<a name="GenericWorkResource"></a>GenericWorkResource|20|Generic work resource. Can be assigned to Project tasks; cannot log on to Project Web Access.|
|<a name="MaterialResource"></a>MaterialResource|21|Material resource. Can be assigned to Project tasks; cannot log on to Project Web Access.|
|<a name="GenericMaterialResource"></a>GenericMaterialResource|22|Generic material resource. Can be assigned to Project tasks; cannot log on to Project Web Access.|
|<a name="CostResources"></a>CostResources|25|Cost resource. Can be assigned to Project tasks; cannot log on to Project Web Access.|
|<a name="GenericCostResources"></a>GenericCostResources|26|Generic cost resource. Can be assigned to Project tasks; cannot log on to Project Web Access.|
|<a name="IS_NONBUDGET_TYPE_MAXIMUM"></a>IS_NONBUDGET_TYPE_MAXIMUM|50|Any resource value less than this value is not a budget resource.|
|<a name="BudgetWorkResource"></a>BudgetWorkResource|50|Budget work resource. Can be assigned only to Project summary tasks; cannot log on to Project Web Access.|
|<a name="BudgetCostResource"></a>BudgetCostResource|51|Budget cost resource. Can be assigned only to Project summary tasks; cannot log on to Project Web Access.|
|<a name="BudgetMaterialResource"></a>BudgetMaterialResource|52|Budget material resource. Can be assigned only to Project summary tasks; cannot log on to Project Web Access.|
|<a name="GenericBudgetWorkResource"></a>GenericBudgetWorkResource|53|Generic budget work resource. Can be assigned only to Project summary tasks; cannot log on to Project Web Access.|
|<a name="GenericBudgetCostResource"></a>GenericBudgetCostResource|54|Generic budget cost resource. Can be assigned only to Project summary tasks; cannot log on to Project Web Access.|
|<a name="GenericBudgetMaterialResource"></a>GenericBudgetMaterialResource|55|Generic budget material resource. Can be assigned only to Project summary tasks; cannot log on to Project Web Access.|
|<a name="INACTIVATED_OFFSET"></a>INACTIVATED_OFFSET|100|An inactive resource has the value of this enumeration added to its resource-type value.|

## <a name="seeAlso"></a>See Also

