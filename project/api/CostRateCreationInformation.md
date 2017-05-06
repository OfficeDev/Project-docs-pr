[comment]: # (Name:CostRateCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.CostRateCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>CostRateCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating an (EnterpriseResourceCostRate)[EnterpriseResourceCostRate.md].

## <a name="syntax"></a>Syntax

### CSOM

```cs
class CostRateCreationInformation 
```
### JSOM

```javascript
PS.CostRateCreationInformation
```
### REST Interface

Supported.

```
PS.CostRateCreationInformation

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceId}')/CostRateTables('{CostRateTableName}')/CostRates/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'CostPerUse':'value', 
		'EffectiveDate':'value', 
		'OvertimeRate':'value', 
		'StandardRate':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="CostPerUse"></a>CostPerUse|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|A one-time cost incurred when a resource is used.|
|<a name="EffectiveDate"></a>EffectiveDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|The date and time when this resource rate becomes effective.|
|<a name="OvertimeRate"></a>OvertimeRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|The resource's hourly rate of pay for overtime.|
|<a name="StandardRate"></a>StandardRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|The resource's hourly rate of pay for regular, non-overtime work.|

## <a name="seeAlso"></a>See Also

[EnterpriseResourceCostRate](EnterpriseResourceCostRate.md)<br/>
[EnterpriseResourceCostRateCollection](EnterpriseResourceCostRateCollection.md)<br/>
