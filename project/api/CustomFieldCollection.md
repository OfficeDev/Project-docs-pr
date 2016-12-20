[comment]: # (Name:CustomFieldCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# CustomFieldCollection

Represents a collection of [CustomField](acf3db55-750f-609d-ee02-a0e8d2cc793d.md) objects.



## Syntax

### CSOM

```C#
Class CustomFieldCollection 
```
### JSOM

```
PS.CustomFieldCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/CustomFields
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([CustomFieldCreationInformation](CustomFieldCreationInformation.md) parameters)](#Add_[CustomFieldCreationInformation]_CustomFieldCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Adds the custom field that is specified by the [CustomFieldCreationInformation](f562b50c-ff5b-2a92-8569-7699df5d9f2d.md) object to the collection.|
|[GetByAppAlternateId(String objectId)](#GetByAppAlternateId_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Gets a custom field from the collection by using the alternate custom field GUID that is specified in an App package for Project Online.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)||
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[CustomField](CustomField.md)|Returns the custom field that is specified by the [Id](14b89fff-c0a0-da1d-fe00-a148a074ca76.md) value.|
|[Remove([CustomField](CustomField.md) field)](#Remove_[CustomField]_CustomField.md__field_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified custom field from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void|Updates the custom field collection.|



## Method Details


### <a name="Add_[CustomFieldCreationInformation]_CustomFieldCreationInformation.md__parameters_"></a>Add([CustomFieldCreationInformation](CustomFieldCreationInformation.md) parameters)
 
Adds the custom field that is specified by the [CustomFieldCreationInformation](f562b50c-ff5b-2a92-8569-7699df5d9f2d.md) object to the collection.

#### Syntax

```
CustomField Add(CustomFieldCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [CustomFieldCreationInformation](CustomFieldCreationInformation.md) | An object that contains the information for the creation of a custom field.


#### Return Value

[CustomField](CustomField.md)

### <a name="GetByAppAlternateId_String_objectId_"></a>GetByAppAlternateId(String objectId)
 
Gets a custom field from the collection by using the alternate custom field GUID that is specified in an App package for Project Online.

#### Syntax

```
CustomField GetByAppAlternateId(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The alternate custom field GUID.


#### Return Value

[CustomField](CustomField.md)

### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 


#### Syntax

```
CustomField GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | 


#### Return Value

[CustomField](CustomField.md)

### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Returns the custom field that is specified by the [Id](14b89fff-c0a0-da1d-fe00-a148a074ca76.md) value.

#### Syntax

```
CustomField GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The custom field GUID.


#### Return Value

[CustomField](CustomField.md)

### <a name="Remove_[CustomField]_CustomField.md__field_"></a>Remove([CustomField](CustomField.md) field)
 
Removes the specified custom field from the collection.

#### Syntax

```
Boolean Remove(CustomField field)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|field| [CustomField](CustomField.md) | The custom field to remove.


#### Return Value

Boolean

### <a name="Update__"></a>Update()
 
Updates the custom field collection.

#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
