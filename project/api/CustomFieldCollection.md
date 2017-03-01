[comment]: # (Name:CustomFieldCollection)
[comment]: # (Name:Microsoft.ProjectServer.CustomFieldCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>CustomFieldCollection class

inherits members from [ClientObjectCollection<CustomField>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [CustomField](CustomField.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class CustomFieldCollection 
```
### JSOM

```JavaScript
PS.CustomFieldCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.CustomFieldCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/CustomFields
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
[!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[CustomField](CustomField.md)|Gets a [CustomField](CustomField.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[CustomField](CustomField.md)|Gets a [CustomField](CustomField.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
[!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{CustomFieldId}&#39;](#&#39;{CustomFieldId}&#39;)|||&#x2713;|[CustomField](CustomField.md)|Gets a [CustomField](CustomField.md) from the collection with the specified CustomFieldId.|
|[Add(CustomFieldCreationInformation parameters)](#Add_[CustomFieldCreationInformation]_CustomFieldCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Adds the [CustomField](CustomField.md) that is specified by the [CustomFieldCreationInformation](CustomFieldCreationInformation.md) object to the collection.|
|[GetByAppAlternateId(String objectId)](#GetByAppAlternateId_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Gets a custom field from the collection by using the alternate custom field GUID that is specified in an App package for Project Online.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Gets a [CustomField](CustomField.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Gets a [CustomField](CustomField.md) from the collection with the Guid value.|
|[Remove(CustomField field)](#Remove_[CustomField]_CustomField.md__field_)|&#x2713;|&#x2713;||Boolean|Removes the specified [CustomField](CustomField.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the custom field collection.|

<br/>
#### Method Details

#### <a name="&#39;{CustomFieldId}&#39;"></a>&#39;{CustomFieldId}&#39;



Gets a [CustomField](CustomField.md) from the collection with the specified CustomFieldId.

##### Syntax

```
CustomField http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/CustomFields('{CustomFieldId}')
```

##### Parameters
[!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|CustomFieldId|String|the id of the CustomField|

##### Return Value

[CustomField](CustomField.md)

#### <a name="Add_[CustomFieldCreationInformation]_CustomFieldCreationInformation.md__parameters_"></a>Add([CustomFieldCreationInformation](CustomFieldCreationInformation.md) parameters)

Adds the [CustomField](CustomField.md) that is specified by the [CustomFieldCreationInformation](CustomFieldCreationInformation.md) object to the collection.

##### Syntax

```

CustomField Add(CustomFieldCreationInformation parameters)

```

##### Parameters
[!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[CustomFieldCreationInformation](CustomFieldCreationInformation.md)|The properties that can be set when creating a custom field.|

##### Return Value

[CustomField](CustomField.md)

#### <a name="GetByAppAlternateId_String_objectId_"></a>GetByAppAlternateId(String objectId)

Gets a custom field from the collection by using the alternate custom field GUID that is specified in an App package for Project Online.

##### Syntax

```

CustomField GetByAppAlternateId(String objectId)

```

##### Parameters
[!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The alternate custom field GUID.|

##### Return Value

[CustomField](CustomField.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [CustomField](CustomField.md) from the collection with the Id value.

##### Syntax

```
CustomField GetByGuid(Guid uid)
```

##### Parameters
[!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [CustomField](CustomField.md)|

##### Return Value

[CustomField](CustomField.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Gets a [CustomField](CustomField.md) from the collection with the Guid value.

##### Syntax

```
CustomField GetById(String objectId)
```

##### Parameters
[!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [CustomField](CustomField.md).|

##### Return Value

[CustomField](CustomField.md)

#### <a name="Remove_[CustomField]_CustomField.md__field_"></a>Remove([CustomField](CustomField.md) field)

Removes the specified [CustomField](CustomField.md) from the collection.

##### Syntax

```

Boolean Remove(CustomField field)

```

##### Parameters
[!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|field|[CustomField](CustomField.md)|The [CustomField](CustomField.md) to remove.|

##### Return Value

Boolean

#### <a name="Update__"></a>Update()


 
Updates the custom field collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[Assignment](Assignment.md)<br/>
[CustomField](CustomField.md)<br/>
[CustomFieldCreationInformation](CustomFieldCreationInformation.md)<br/>
[EnterpriseResource](EnterpriseResource.md)<br/>
[PlanAssignment](PlanAssignment.md)<br/>
[Project](Project.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
[ProjectResource](ProjectResource.md)<br/>
[StatusAssignment](StatusAssignment.md)<br/>
[StatusTask](StatusTask.md)<br/>
[Task](Task.md)<br/>
