[comment]: # (Name:EnterpriseResourceCostRateTableCollection)
[comment]: # (Name:Microsoft.ProjectServer.EnterpriseResourceCostRateTableCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EnterpriseResourceCostRateTableCollection class

inherits members from [ClientObjectCollection<EnterpriseResourceCostRateTable>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Collection of cost rate tables for the [EnterpriseResource](EnterpriseResource.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EnterpriseResourceCostRateTableCollection 
```
### JSOM

```javascript
PS.EnterpriseResourceCostRateTableCollection
```
### REST Interface

Supported.

```
PS.EnterpriseResourceCostRateTableCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceId}')/CostRateTables
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[EnterpriseResourceCostRateTable](EnterpriseResourceCostRateTable.md)|Gets a [EnterpriseResourceCostRateTable](EnterpriseResourceCostRateTable.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[EnterpriseResourceCostRateTable](EnterpriseResourceCostRateTable.md)|Gets a [EnterpriseResourceCostRateTable](EnterpriseResourceCostRateTable.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetByName(CostRateTableName name)](#GetByName_[CostRateTableName]_CostRateTableName.md__name_)|&#x2713;|&#x2713;||[EnterpriseResourceCostRateTable](EnterpriseResourceCostRateTable.md)|Returns the cost rate table with the given name.|

<br/>
#### Method Details

#### <a name="GetByName_[CostRateTableName]_CostRateTableName.md__name_"></a>GetByName([CostRateTableName](CostRateTableName.md) name)

Returns the cost rate table with the given name. 

##### Syntax

```
EnterpriseResourceCostRateTable GetByName(CostRateTableName name)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|name|[CostRateTableName](CostRateTableName.md)|Name of the cost rate table to retrieve.|

##### Return Value

[EnterpriseResourceCostRateTable](EnterpriseResourceCostRateTable.md)

## <a name="seeAlso"></a>See Also

[EnterpriseResource](EnterpriseResource.md)<br/>
[EnterpriseResourceCostRateTable](EnterpriseResourceCostRateTable.md)<br/>
