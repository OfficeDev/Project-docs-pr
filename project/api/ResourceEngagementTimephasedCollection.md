[comment]: # (Name:ResourceEngagementTimephasedCollection)
[comment]: # (Name:Microsoft.ProjectServer.ResourceEngagementTimephasedCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ResourceEngagementTimephasedCollection class

inherits members from [ClientObjectCollection<ResourceEngagementTimephasedPeriod>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ResourceEngagementTimephasedCollection 
```
### JSOM

```javascript
PS.ResourceEngagementTimephasedCollection
```
### REST Interface

Supported.

```
PS.ResourceEngagementTimephasedCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Engagements('{engagementid}')/GetTimephasedByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}',contourType='{contourType}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)|Gets a [ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)|Gets a [ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetByStart(DateTime date)](#GetByStart_DateTime_date_)|&#x2713;|&#x2713;||[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)||
|[GetByStartUrl(String date)](#GetByStartUrl_String_date_)|||&#x2713;|[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)||

<br/>
#### Method Details

#### <a name="GetByStart_DateTime_date_"></a>GetByStart(DateTime date)
 

##### Syntax

```
ResourceEngagementTimephasedPeriod GetByStart(DateTime date)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|date|DateTime||

##### Return Value

[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)

#### <a name="GetByStartUrl_String_date_"></a>GetByStartUrl(String date)
 

##### Syntax

```
ResourceEngagementTimephasedPeriod GetByStartUrl(String date)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|date|String||

##### Return Value

[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)

## <a name="seeAlso"></a>See Also

[ResourceEngagement](ResourceEngagement.md)<br/>
[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)<br/>
