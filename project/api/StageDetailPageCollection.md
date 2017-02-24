[comment]: # (Name:StageDetailPageCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StageDetailPageCollection class

inherits members from [ClientObjectCollection<StageDetailPage>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of project detail pages (PDPs) that are visible in a workflow stage.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class StageDetailPageCollection 
```
### JSOM

```JavaScript
PS.StageDetailPageCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.StageDetailPageCollection

http://<sitecollection>/<site>/api/ProjectServer/Stages('{stageid}')/ProjectDetailPages
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[StageDetailPage](StageDetailPage.md)|Gets a [StageDetailPage](StageDetailPage.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[StageDetailPage](StageDetailPage.md)|Gets a [StageDetailPage](StageDetailPage.md) from the collection at the specified index.|

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{StageDetailPageId}&#39;](#&#39;{StageDetailPageId}&#39;)|||&#x2713;|[StageDetailPage](StageDetailPage.md)|Gets a [StageDetailPage](StageDetailPage.md) from the collection with the specified StageDetailPageId.|
|[Add(StageDetailPageCreationInformation parameters)](#Add_[StageDetailPageCreationInformation]_StageDetailPageCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[StageDetailPage](StageDetailPage.md)|Adds the [StageDetailPage](StageDetailPage.md) that is specified by the [StageDetailPageCreationInformation](StageDetailPageCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[StageDetailPage](StageDetailPage.md)|Gets a [StageDetailPage](StageDetailPage.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[StageDetailPage](StageDetailPage.md)|Gets a [StageDetailPage](StageDetailPage.md) from the collection with the Guid value.|
|[Remove(StageDetailPage pdp)](#Remove_[StageDetailPage]_StageDetailPage.md__pdp_)|&#x2713;|&#x2713;||Boolean|Removes the specified [StageDetailPage](StageDetailPage.md) from the collection.|

<br/>
#### Method Details

#### <a name="&#39;{StageDetailPageId}&#39;"></a>&#39;{StageDetailPageId}&#39;
 
Gets a [StageDetailPage](StageDetailPage.md) from the collection with the specified StageDetailPageId.

##### Syntax

```
StageDetailPage http://<sitecollection>/<site>/api/ProjectServer/Stages('{stageid}')/ProjectDetailPages('{StageDetailPageId}')
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|StageDetailPageId|String|the id of the StageDetailPage|

##### Return Value

[StageDetailPage](StageDetailPage.md)

#### <a name="Add_[StageDetailPageCreationInformation]_StageDetailPageCreationInformation.md__parameters_"></a>Add([StageDetailPageCreationInformation](StageDetailPageCreationInformation.md) parameters)
 
Adds the [StageDetailPage](StageDetailPage.md) that is specified by the [StageDetailPageCreationInformation](StageDetailPageCreationInformation.md) object to the collection.

##### Syntax

```
StageDetailPage Add(StageDetailPageCreationInformation parameters)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[StageDetailPageCreationInformation](StageDetailPageCreationInformation.md)|The properties that can be set when creating a stage detail page.|

##### Return Value

[StageDetailPage](StageDetailPage.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [StageDetailPage](StageDetailPage.md) from the collection with the Id value.

##### Syntax

```
StageDetailPage GetByGuid(Guid uid)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [StageDetailPage](StageDetailPage.md)|

##### Return Value

[StageDetailPage](StageDetailPage.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [StageDetailPage](StageDetailPage.md) from the collection with the Guid value.

##### Syntax

```
StageDetailPage GetById(String objectId)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [StageDetailPage](StageDetailPage.md).|

##### Return Value

[StageDetailPage](StageDetailPage.md)

#### <a name="Remove_[StageDetailPage]_StageDetailPage.md__pdp_"></a>Remove([StageDetailPage](StageDetailPage.md) pdp)
 
Removes the specified [StageDetailPage](StageDetailPage.md) from the collection.

##### Syntax

```
Boolean Remove(StageDetailPage pdp)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|pdp|[StageDetailPage](StageDetailPage.md)|The [StageDetailPage](StageDetailPage.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[Stage](Stage.md)<br/>
[StageDetailPage](StageDetailPage.md)<br/>
[StageDetailPageCreationInformation](StageDetailPageCreationInformation.md)<br/>
