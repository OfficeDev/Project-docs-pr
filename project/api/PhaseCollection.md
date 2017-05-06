[comment]: # (Name:PhaseCollection)
[comment]: # (Name:Microsoft.ProjectServer.PhaseCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>PhaseCollection class

inherits members from [ClientObjectCollection<Phase>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of workflow [Phase](Phase.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class PhaseCollection 
```
### JSOM

```javascript
PS.PhaseCollection
```
### REST Interface

Supported.

```
PS.PhaseCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Phases
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[Phase](Phase.md)|Gets a [Phase](Phase.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[Phase](Phase.md)|Gets a [Phase](Phase.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{PhaseId}&#39;](#&#39;{PhaseId}&#39;)|||&#x2713;|[Phase](Phase.md)|Gets a [Phase](Phase.md) from the collection with the specified PhaseId.|
|[Add(PhaseCreationInformation parameters)](#Add_[PhaseCreationInformation]_PhaseCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[Phase](Phase.md)|Adds the [Phase](Phase.md) that is specified by the [PhaseCreationInformation](PhaseCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[Phase](Phase.md)|Gets a [Phase](Phase.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[Phase](Phase.md)|Gets a [Phase](Phase.md) from the collection with the Guid value.|
|[Remove(Phase phase)](#Remove_[Phase]_Phase.md__phase_)|&#x2713;|&#x2713;||Boolean|Removes the specified [Phase](Phase.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the phase collection.|

<br/>
#### Method Details

#### <a name="&#39;{PhaseId}&#39;"></a>&#39;{PhaseId}&#39;
 
Gets a [Phase](Phase.md) from the collection with the specified PhaseId.

##### Syntax

```
Phase http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Phases('{PhaseId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|PhaseId|String|the id of the Phase|

##### Return Value

[Phase](Phase.md)

#### <a name="Add_[PhaseCreationInformation]_PhaseCreationInformation.md__parameters_"></a>Add([PhaseCreationInformation](PhaseCreationInformation.md) parameters)
 
Adds the [Phase](Phase.md) that is specified by the [PhaseCreationInformation](PhaseCreationInformation.md) object to the collection.

##### Syntax

```
Phase Add(PhaseCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[PhaseCreationInformation](PhaseCreationInformation.md)|The properties that can be set when creating a phase.|

##### Return Value

[Phase](Phase.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [Phase](Phase.md) from the collection with the Id value.

##### Syntax

```
Phase GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [Phase](Phase.md)|

##### Return Value

[Phase](Phase.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [Phase](Phase.md) from the collection with the Guid value.

##### Syntax

```
Phase GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [Phase](Phase.md).|

##### Return Value

[Phase](Phase.md)

#### <a name="Remove_[Phase]_Phase.md__phase_"></a>Remove([Phase](Phase.md) phase)
 
Removes the specified [Phase](Phase.md) from the collection.

##### Syntax

```
Boolean Remove(Phase phase)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|phase|[Phase](Phase.md)|The [Phase](Phase.md) to remove.|

##### Return Value

Boolean

#### <a name="Update__"></a>Update()
 
Updates the phase collection.

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
[PhaseCreationInformation](PhaseCreationInformation.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
