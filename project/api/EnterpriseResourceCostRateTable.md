[comment]: # (Name:EnterpriseResourceCostRateTable)
[comment]: # (Name:Microsoft.ProjectServer.EnterpriseResourceCostRateTable)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EnterpriseResourceCostRateTable class

<a name="description"></a>Contains the cost rates and effective dates for the [EnterpriseResource](EnterpriseResource.md) cost rate table.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EnterpriseResourceCostRateTable 
```
### JSOM

```javascript
PS.EnterpriseResourceCostRateTable
```
### REST Interface

Supported.

```
PS.EnterpriseResourceCostRateTable

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceId}')/CostRateTables('{CostRateTableName}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="CostRates"></a>CostRates|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResourceCostRateCollection](EnterpriseResourceCostRateCollection.md)|Cost rates that have been configured in the rate table.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|[CostRateTableName](CostRateTableName.md)|Name of the cost rate table.|

## <a name="seeAlso"></a>See Also

[EnterpriseResourceCostRateTableCollection](EnterpriseResourceCostRateTableCollection.md)<br/>
