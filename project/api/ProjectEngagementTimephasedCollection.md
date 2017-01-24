[comment]: # (Name:ProjectEngagementTimephasedCollection)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>ProjectEngagementTimephasedCollection class

inherits members from [ClientObjectCollection<ProjectEngagementTimephasedPeriod>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```C#
class ProjectEngagementTimephasedCollection 
```
### JSOM

```JavaScript
PS.ProjectEngagementTimephasedCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.ProjectEngagementTimephasedCollection

http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/Engagements('{engagementid}')/GetTimephasedByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}',contourType='{contourType}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)|Gets a [ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)|Gets a [ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md) from the collection at the specified index.|

### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetByStart(DateTime date)](#GetByStart_DateTime_date_)|&#x2713;|&#x2713;||[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)||
|[GetByStartUrl(String date)](#GetByStartUrl_String_date_)|||&#x2713;|[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)||

<br/>
#### Method Details

#### <a name="GetByStart_DateTime_date_"></a>GetByStart(DateTime date)
 

##### Syntax

```
ProjectEngagementTimephasedPeriod GetByStart(DateTime date)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|date|DateTime||

##### Return Value

[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)

#### <a name="GetByStartUrl_String_date_"></a>GetByStartUrl(String date)
 

##### Syntax

```
ProjectEngagementTimephasedPeriod GetByStartUrl(String date)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|date|String||

##### Return Value

[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)

## <a name="seeAlso"></a>See Also

[ProjectEngagement](ProjectEngagement.md)<br/>
[ProjectEngagementTimephasedPeriod](ProjectEngagementTimephasedPeriod.md)<br/>
