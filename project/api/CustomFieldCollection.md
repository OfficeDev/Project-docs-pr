[comment]: # (Name:CustomFieldCollection)
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

This resource supports GET and POST HTTP commands.

```
PS.CustomFieldCollection

http://<sitecollection>/<site>/api/ProjectServer/CustomFields
```

## <a name="members"></a>Members

### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{CustomFieldId}&#39;](#&#39;{CustomFieldId}&#39;)|||&#x2713;|[CustomField](CustomField.md)|Gets a [CustomField](CustomField.md) from the collection with the specified CustomFieldId.|
|[Add(CustomFieldCreationInformation parameters)](#Add_[CustomFieldCreationInformation]_CustomFieldCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Adds the custom field that is specified by the [CustomFieldCreationInformation](CustomFieldCreationInformation.md) object to the collection.|
|[GetByAppAlternateId(String objectId)](#GetByAppAlternateId_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Gets a custom field from the collection by using the alternate custom field GUID that is specified in an App package for Project Online.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Returns the custom field that is specified by the Guid value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Returns the custom field that is specified by the Id value.|
|[Remove(CustomField field)](#Remove_[CustomField]_CustomField.md__field_)|&#x2713;|&#x2713;||Boolean|Removes the specified custom field from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the custom field collection.|

<br/>
#### Method Details

#### <a name="&#39;{CustomFieldId}&#39;"></a>&#39;{CustomFieldId}&#39;



Gets a [CustomField](CustomField.md) from the collection with the specified CustomFieldId.

##### Syntax

```

CustomField http://<sitecollection>/<site>/api/ProjectServer/CustomFields('{CustomFieldId}')

```

##### Parameters

None

##### Return Value

[CustomField](CustomField.md)

#### <a name="Add_[CustomFieldCreationInformation]_CustomFieldCreationInformation.md__parameters_"></a>Add([CustomFieldCreationInformation](CustomFieldCreationInformation.md) parameters)

Adds the custom field that is specified by the [CustomFieldCreationInformation](CustomFieldCreationInformation.md) object to the collection.

##### Syntax

```

CustomField Add(CustomFieldCreationInformation parameters)

```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [CustomFieldCreationInformation](CustomFieldCreationInformation.md) | An object that contains the information for the creation of a custom field.

##### Return Value

[CustomField](CustomField.md)

#### <a name="GetByAppAlternateId_String_objectId_"></a>GetByAppAlternateId(String objectId)

Gets a custom field from the collection by using the alternate custom field GUID that is specified in an App package for Project Online.

##### Syntax

```

CustomField GetByAppAlternateId(String objectId)

```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The alternate custom field GUID.

##### Return Value

[CustomField](CustomField.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 


##### Syntax

```
CustomField GetByGuid(Guid uid)
```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | 

##### Return Value

[CustomField](CustomField.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)

Returns the custom field that is specified by the Id value.

##### Syntax

```
CustomField GetById(String objectId)
```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The custom field GUID.

##### Return Value

[CustomField](CustomField.md)

#### <a name="Remove_[CustomField]_CustomField.md__field_"></a>Remove([CustomField](CustomField.md) field)

Removes the specified custom field from the collection.

##### Syntax

```

Boolean Remove(CustomField field)

```

##### Parameters

|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|field| [CustomField](CustomField.md) | The custom field to remove.

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
