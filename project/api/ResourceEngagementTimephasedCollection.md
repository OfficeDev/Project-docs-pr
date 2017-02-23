[comment]: # (Name:ResourceEngagementTimephasedCollection)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>ResourceEngagementTimephasedCollection class

inherits members from [ClientObjectCollection<ResourceEngagementTimephasedPeriod>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```C#
class ResourceEngagementTimephasedCollection 
```
### JSOM

```JavaScript
PS.ResourceEngagementTimephasedCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.ResourceEngagementTimephasedCollection

http://<sitecollection>/<site>/api/ProjectServer/EnterpriseResources('{resourceid}')/Engagements('{engagementid}')/GetTimephasedByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}',contourType='{contourType}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)|Gets a [ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)|Gets a [ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md) from the collection at the specified index.|

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
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
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|date|String||

##### Return Value

[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)

## <a name="seeAlso"></a>See Also

[ResourceEngagement](ResourceEngagement.md)<br/>
[ResourceEngagementTimephasedPeriod](ResourceEngagementTimephasedPeriod.md)<br/>
