[comment]: # (Name:EnterpriseResourceCollection)
[comment]: # (Name:Microsoft.ProjectServer.EnterpriseResourceCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EnterpriseResourceCollection class

inherits members from [ClientObjectCollection<EnterpriseResource>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [EnterpriseResource](EnterpriseResource.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EnterpriseResourceCollection 
```
### JSOM

```javascript
PS.EnterpriseResourceCollection
```

### REST Interface

Supported.

```
PS.EnterpriseResourceCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/EnterpriseResources
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[EnterpriseResource](EnterpriseResource.md)|Gets a [EnterpriseResource](EnterpriseResource.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[EnterpriseResource](EnterpriseResource.md)|Gets a [EnterpriseResource](EnterpriseResource.md) from the collection at the specified index.|
|<a name="Self"></a>Self|||&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets the enterprise resource object for the current user.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:----- |:-----: |:-----: |:-----: |:----- |:----- |
|[Add(EnterpriseResourceCreationInformation ercinfo)](#add)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Adds the enterprise resource that is specified by the [EnterpriseResourceCreationInformation](EnterpriseResourceCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Get an enterprise resource from the collection with the specified GUID.|
|[GetById(String Id)](#getbyid)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets an enterprise resource from the collection with the Name value.|
|[GetByUser(SPUser user)](#getbyuser)|&#x2713;|&#x2713;||[EnterpriseResource](EnterpriseResource.md)|Returns an enterprise resource from the collection linked to the SharePoint user.|
|[Remove(EnterpriseResource resource)](#remove)|&#x2713;|&#x2713;||Boolean|Removes the specified enterprise resource from a project.|
|[Self()](#self)|||&#x2713;|[EnterpriseResource](EnterpriseResource.md)|Gets the enterprise resource object for the current user.|
|[Update()](#update)|&#x2713;|&#x2713;|&#x2713;|Void|Updates the enterprise resource collection.|


<br/>
#### Method Details

#### <a name="&#39;{EnterpriseResourceId}&#39;"></a>&#39;{EnterpriseResourceId}&#39;
 
Gets a [EnterpriseResource](EnterpriseResource.md) from the collection with the specified EnterpriseResourceId.

##### Syntax

```
EnterpriseResource http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/EnterpriseResources('{EnterpriseResourceId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|EnterpriseResourceId|String|the id of the EnterpriseResource|

##### Return Value

[EnterpriseResource](EnterpriseResource.md)

#### <a name="Add_[EnterpriseResourceCreationInformation]_EnterpriseResourceCreationInformation.md__parameters_"></a>Add([EnterpriseResourceCreationInformation](EnterpriseResourceCreationInformation.md) parameters)

Adds the [EnterpriseResource](EnterpriseResource.md) that is specified by the [EnterpriseResourceCreationInformation](EnterpriseResourceCreationInformation.md) object to the collection.

##### Syntax

```
EnterpriseResource Add(EnterpriseResourceCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[EnterpriseResourceCreationInformation](EnterpriseResourceCreationInformation.md)|The properties that can be set when creating a enterprise resource.|

##### Return Value

[EnterpriseResource](EnterpriseResource.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)

Gets a [EnterpriseResource](EnterpriseResource.md) from the collection with the Id value.

##### Syntax

```
EnterpriseResource GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [EnterpriseResource](EnterpriseResource.md)|

##### Return Value

[EnterpriseResource](EnterpriseResource.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a [EnterpriseResource](EnterpriseResource.md) from the collection with the Guid value.

##### Syntax

```
EnterpriseResource GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [EnterpriseResource](EnterpriseResource.md).|

##### Return Value

[EnterpriseResource](EnterpriseResource.md)

#### <a name="GetByUser_[SPUser]_https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx__user_"></a>GetByUser([SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx) user)

Returns an element from the collection linked to the SharePoint user.

##### Syntax

```
EnterpriseResource GetByUser(SPUser user)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|user|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|An object of type User.|

##### Return Value

[EnterpriseResource](EnterpriseResource.md)

#### <a name="Remove_[EnterpriseResource]_EnterpriseResource.md__resource_"></a>Remove([EnterpriseResource](EnterpriseResource.md) resource)

Removes the specified [EnterpriseResource](EnterpriseResource.md) from the collection.

##### Syntax

```
Boolean Remove(EnterpriseResource resource)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|resource|[EnterpriseResource](EnterpriseResource.md)|The [EnterpriseResource](EnterpriseResource.md) to remove.|

##### Return Value

Boolean
True if the object is removed from the collection; otherwise, False.



### <a name="self"></a> Self()

Gets the current enterprise resource from the collection.

#### Syntax

```
Self()
```

#### Parameters

none

#### Return Value

[EnterpriseResource](EnterpriseResource.md)<br />
An [EnterpriseResource](EnterpriseResource.md) object.


#### <a name="Update__"></a>Update()

Updates the enterprise resource collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[EnterpriseResource](EnterpriseResource.md)<br/>
[EnterpriseResourceCreationInformation](EnterpriseResourceCreationInformation.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
