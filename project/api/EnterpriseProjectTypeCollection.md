[comment]: # (Name:EnterpriseProjectTypeCollection)
[comment]: # (Name:Microsoft.ProjectServer.EnterpriseProjectTypeCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EnterpriseProjectTypeCollection class

inherits members from [ClientObjectCollection<EnterpriseProjectType>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [EnterpriseProjectType](EnterpriseProjectType.md) (EPT) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EnterpriseProjectTypeCollection 
```
### JSOM

```javascript
PS.EnterpriseProjectTypeCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.EnterpriseProjectTypeCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/EnterpriseProjectTypes
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[EnterpriseProjectType](EnterpriseProjectType.md)|Gets a [EnterpriseProjectType](EnterpriseProjectType.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[EnterpriseProjectType](EnterpriseProjectType.md)|Gets a [EnterpriseProjectType](EnterpriseProjectType.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{EnterpriseProjectTypeId}&#39;](#&#39;{EnterpriseProjectTypeId}&#39;)|||&#x2713;|[EnterpriseProjectType](EnterpriseProjectType.md)|Gets a [EnterpriseProjectType](EnterpriseProjectType.md) from the collection with the specified EnterpriseProjectTypeId.|
|[Add(EnterpriseProjectTypeCreationInformation parameters)](#Add_[EnterpriseProjectTypeCreationInformation]_EnterpriseProjectTypeCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseProjectType](EnterpriseProjectType.md)|Adds the [EnterpriseProjectType](EnterpriseProjectType.md) that is specified by the [EnterpriseProjectTypeCreationInformation](EnterpriseProjectTypeCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseProjectType](EnterpriseProjectType.md)|Gets a [EnterpriseProjectType](EnterpriseProjectType.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseProjectType](EnterpriseProjectType.md)|Gets a [EnterpriseProjectType](EnterpriseProjectType.md) from the collection with the Guid value.|
|[Remove(EnterpriseProjectType ept)](#Remove_[EnterpriseProjectType]_EnterpriseProjectType.md__ept_)|&#x2713;|&#x2713;||Boolean|Removes the specified [EnterpriseProjectType](EnterpriseProjectType.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the enterprise project type collection.|

<br/>
#### Method Details

#### <a name="&#39;{EnterpriseProjectTypeId}&#39;"></a>&#39;{EnterpriseProjectTypeId}&#39;
 
Gets a [EnterpriseProjectType](EnterpriseProjectType.md) from the collection with the specified EnterpriseProjectTypeId.

##### Syntax

```
EnterpriseProjectType http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/EnterpriseProjectTypes('{EnterpriseProjectTypeId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|EnterpriseProjectTypeId|String|the id of the EnterpriseProjectType|

##### Return Value

[EnterpriseProjectType](EnterpriseProjectType.md)

#### <a name="Add_[EnterpriseProjectTypeCreationInformation]_EnterpriseProjectTypeCreationInformation.md__parameters_"></a>Add([EnterpriseProjectTypeCreationInformation](EnterpriseProjectTypeCreationInformation.md) parameters)
 
Adds the [EnterpriseProjectType](EnterpriseProjectType.md) that is specified by the [EnterpriseProjectTypeCreationInformation](EnterpriseProjectTypeCreationInformation.md) object to the collection.

##### Syntax

```
EnterpriseProjectType Add(EnterpriseProjectTypeCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[EnterpriseProjectTypeCreationInformation](EnterpriseProjectTypeCreationInformation.md)|The properties that can be set when creating a enterprise project type.|

##### Return Value

[EnterpriseProjectType](EnterpriseProjectType.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [EnterpriseProjectType](EnterpriseProjectType.md) from the collection with the Id value.

##### Syntax

```
EnterpriseProjectType GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [EnterpriseProjectType](EnterpriseProjectType.md)|

##### Return Value

[EnterpriseProjectType](EnterpriseProjectType.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [EnterpriseProjectType](EnterpriseProjectType.md) from the collection with the Guid value.

##### Syntax

```
EnterpriseProjectType GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [EnterpriseProjectType](EnterpriseProjectType.md).|

##### Return Value

[EnterpriseProjectType](EnterpriseProjectType.md)

#### <a name="Remove_[EnterpriseProjectType]_EnterpriseProjectType.md__ept_"></a>Remove([EnterpriseProjectType](EnterpriseProjectType.md) ept)
 
Removes the specified [EnterpriseProjectType](EnterpriseProjectType.md) from the collection.

##### Syntax

```
Boolean Remove(EnterpriseProjectType ept)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|ept|[EnterpriseProjectType](EnterpriseProjectType.md)|The [EnterpriseProjectType](EnterpriseProjectType.md) to remove.|

##### Return Value

Boolean

#### <a name="Update__"></a>Update()
 
Updates the enterprise project type collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[EnterpriseProjectType](EnterpriseProjectType.md)<br/>
[EnterpriseProjectTypeCreationInformation](EnterpriseProjectTypeCreationInformation.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
