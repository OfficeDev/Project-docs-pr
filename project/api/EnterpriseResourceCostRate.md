[comment]: # (Name:EnterpriseResourceCostRate)
[comment]: # (Name:Microsoft.ProjectServer.EnterpriseResourceCostRate)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EnterpriseResourceCostRate class

<a name="description"></a>Represents resource rate information in a [CostRateTable](CostRateTable.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EnterpriseResourceCostRate 
```
### JSOM

```javascript
PS.EnterpriseResourceCostRate
```
### REST Interface

Supported.

```
PS.EnterpriseResourceCostRate

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/?????
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="CostPerUse"></a>CostPerUse|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|A one-time cost incurred when a resource is used.|
|<a name="EffectiveStarting"></a>EffectiveStarting|&#x2713;|&#x2713;|&#x2713;|DateTime|The date and time when this resource rate becomes effective.|
|<a name="EffectiveUntil"></a>EffectiveUntil|&#x2713;|&#x2713;|&#x2713;|DateTime|The date and time when this resource rate no longer effective.|
|<a name="OvertimeRate"></a>OvertimeRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|The resource's hourly rate of pay for overtime.|
|<a name="StandardRate"></a>StandardRate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Double|The resource's hourly rate of pay for regular, non-overtime work.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;||Boolean|Deletes the enterprise resource cost rate object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the enterprise resource cost rate object.

##### Syntax

```
Boolean DeleteObject()
```

##### Parameters

None

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[CostRateCreationInformation](CostRateCreationInformation.md)<br/>
[CostRateTable](CostRateTable.md)<br/>
[EnterpriseResourceCostRateCollection](EnterpriseResourceCostRateCollection.md)<br/>
