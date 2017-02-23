[comment]: # (Name:StageCollection)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>StageCollection class

inherits members from [ClientObjectCollection<Stage>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of workflow [Stage](Stage.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class StageCollection 
```
### JSOM

```JavaScript
PS.StageCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.StageCollection

http://<sitecollection>/<site>/api/ProjectServer/Stages
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[Stage](Stage.md)|Gets a [Stage](Stage.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[Stage](Stage.md)|Gets a [Stage](Stage.md) from the collection at the specified index.|

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{StageId}&#39;](#&#39;{StageId}&#39;)|||&#x2713;|[Stage](Stage.md)|Gets a [Stage](Stage.md) from the collection with the specified StageId.|
|[Add(StageCreationInformation parameters)](#Add_[StageCreationInformation]_StageCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Adds the [Stage](Stage.md) that is specified by the [StageCreationInformation](StageCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets a [Stage](Stage.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets a [Stage](Stage.md) from the collection with the Guid value.|
|[Remove(Stage stage)](#Remove_[Stage]_Stage.md__stage_)|&#x2713;|&#x2713;||Boolean|Removes the specified [Stage](Stage.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the stage collection.|

<br/>
#### Method Details

#### <a name="&#39;{StageId}&#39;"></a>&#39;{StageId}&#39;
 
Gets a [Stage](Stage.md) from the collection with the specified StageId.

##### Syntax

```
Stage http://<sitecollection>/<site>/api/ProjectServer/Stages('{StageId}')
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|StageId|String|the id of the Stage|

##### Return Value

[Stage](Stage.md)

#### <a name="Add_[StageCreationInformation]_StageCreationInformation.md__parameters_"></a>Add([StageCreationInformation](StageCreationInformation.md) parameters)
 
Adds the [Stage](Stage.md) that is specified by the [StageCreationInformation](StageCreationInformation.md) object to the collection.

##### Syntax

```
Stage Add(StageCreationInformation parameters)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[StageCreationInformation](StageCreationInformation.md)|The properties that can be set when creating a stage.|

##### Return Value

[Stage](Stage.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [Stage](Stage.md) from the collection with the Id value.

##### Syntax

```
Stage GetByGuid(Guid uid)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [Stage](Stage.md)|

##### Return Value

[Stage](Stage.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [Stage](Stage.md) from the collection with the Guid value.

##### Syntax

```
Stage GetById(String objectId)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [Stage](Stage.md).|

##### Return Value

[Stage](Stage.md)

#### <a name="Remove_[Stage]_Stage.md__stage_"></a>Remove([Stage](Stage.md) stage)
 
Removes the specified [Stage](Stage.md) from the collection.

##### Syntax

```
Boolean Remove(Stage stage)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|stage|[Stage](Stage.md)|The [Stage](Stage.md) to remove.|

##### Return Value

Boolean

#### <a name="Update__"></a>Update()
 
Updates the stage collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[Phase](Phase.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
[Stage](Stage.md)<br/>
[StageCreationInformation](StageCreationInformation.md)<br/>
