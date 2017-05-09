[comment]: # (Name:StageCollection)
[comment]: # (Name:Microsoft.ProjectServer.StageCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StageCollection class

inherits members from [ClientObjectCollection<Stage>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of workflow [Stage](Stage.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StageCollection 
```
### JSOM

```javascript
PS.StageCollection
```
### REST Interface

Supported.

```
PS.StageCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Stages
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[Stage](Stage.md)|Gets a [Stage](Stage.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[Stage](Stage.md)|Gets a [Stage](Stage.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{StageId}&#39;](#&#39;{StageId}&#39;)|||&#x2713;|[Stage](Stage.md)|Gets a [Stage](Stage.md) from the collection with the specified StageId.|
|[Add(StageCreationInformation parameters)](#Add_[StageCreationInformation]_StageCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Adds the [Stage](Stage.md) that is specified by the [StageCreationInformation](StageCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets a [Stage](Stage.md) from the collection with the Guid value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets a [Stage](Stage.md) from the collection with the Id value.|
|[Remove(Stage stage)](#Remove_[Stage]_Stage.md__stage_)|&#x2713;|&#x2713;||Boolean|Removes the specified [Stage](Stage.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the stage collection.|

<br/>
#### Method Details

#### <a name="&#39;{StageId}&#39;"></a>&#39;{StageId}&#39;
 
Gets a [Stage](Stage.md) from the collection with the specified StageId.

##### Syntax

```
Stage http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Stages('{StageId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
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
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[StageCreationInformation](StageCreationInformation.md)|The properties that can be set when creating a stage.|

##### Return Value

[Stage](Stage.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [Stage](Stage.md) from the collection with the Guid value.

##### Syntax

```
Stage GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [Stage](Stage.md)|

##### Return Value

[Stage](Stage.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [Stage](Stage.md) from the collection with the Id value.

##### Syntax

```
Stage GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
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
> [!div class="mx-tdBreakAll"]
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
