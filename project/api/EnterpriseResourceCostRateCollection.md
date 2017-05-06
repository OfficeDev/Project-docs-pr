[comment]: # (Name:EnterpriseResourceCostRateCollection)
[comment]: # (Name:Microsoft.ProjectServer.EnterpriseResourceCostRateCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EnterpriseResourceCostRateCollection class

inherits members from [ClientObjectCollection<EnterpriseResourceCostRate>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Collection of [EnterpriseResourceCostRates](EnterpriseResourceCostRate.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EnterpriseResourceCostRateCollection 
```
### JSOM

```javascript
PS.EnterpriseResourceCostRateCollection
```
### REST Interface

Supported.

```
PS.EnterpriseResourceCostRateCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceId}')/CostRateTables('{CostRateTableName}')/CostRates
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[EnterpriseResourceCostRate](EnterpriseResourceCostRate.md)|Gets a [EnterpriseResourceCostRate](EnterpriseResourceCostRate.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[EnterpriseResourceCostRate](EnterpriseResourceCostRate.md)|Gets a [EnterpriseResourceCostRate](EnterpriseResourceCostRate.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add(CostRateCreationInformation parameters)](#Add_[CostRateCreationInformation]_CostRateCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResourceCostRate](EnterpriseResourceCostRate.md)|Adds the [EnterpriseResourceCostRate](EnterpriseResourceCostRate.md) that is specified by the [CostRateCreationInformation](CostRateCreationInformation.md) object to the collection.|
|[GetByDateUrl(String date)](#GetByDateUrl_String_date_)|||&#x2713;|[EnterpriseResourceCostRate](EnterpriseResourceCostRate.md)|Return the cost rate that is effective after the date provided.|
|[Remove(EnterpriseResourceCostRate costRate)](#Remove_[EnterpriseResourceCostRate]_EnterpriseResourceCostRate.md__costRate_)|&#x2713;|&#x2713;||Boolean|Removes the specified [EnterpriseResourceCostRate](EnterpriseResourceCostRate.md) from the collection.|

<br/>
#### Method Details

#### <a name="Add_[CostRateCreationInformation]_CostRateCreationInformation.md__parameters_"></a>Add([CostRateCreationInformation](CostRateCreationInformation.md) parameters)
 
Adds the [EnterpriseResourceCostRate](EnterpriseResourceCostRate.md) that is specified by the [CostRateCreationInformation](CostRateCreationInformation.md) object to the collection.

##### Syntax

```
EnterpriseResourceCostRate Add(CostRateCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[CostRateCreationInformation](CostRateCreationInformation.md)|The properties that can be set when creating a enterprise resource cost rate.|

##### Return Value

[EnterpriseResourceCostRate](EnterpriseResourceCostRate.md)

#### <a name="GetByDateUrl_String_date_"></a>GetByDateUrl(String date)

Return the cost rate that is effective after the date provided.

##### Syntax

```
EnterpriseResourceCostRate GetByDateUrl(String date)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|date|String|Effective date.|

##### Return Value

[EnterpriseResourceCostRate](EnterpriseResourceCostRate.md)

#### <a name="Remove_[EnterpriseResourceCostRate]_EnterpriseResourceCostRate.md__costRate_"></a>Remove([EnterpriseResourceCostRate](EnterpriseResourceCostRate.md) costRate)
 
Removes the specified [EnterpriseResourceCostRate](EnterpriseResourceCostRate.md) from the collection.

##### Syntax

```
Boolean Remove(EnterpriseResourceCostRate costRate)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|costRate|[EnterpriseResourceCostRate](EnterpriseResourceCostRate.md)|The [EnterpriseResourceCostRate](EnterpriseResourceCostRate.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[CostRateCreationInformation](CostRateCreationInformation.md)<br/>
[EnterpriseResourceCostRate](EnterpriseResourceCostRate.md)<br/>
[EnterpriseResourceCostRateTable](EnterpriseResourceCostRateTable.md)<br/>
