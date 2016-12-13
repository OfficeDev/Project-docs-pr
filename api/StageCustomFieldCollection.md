[comment]: # (Name:StageCustomFieldCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# StageCustomFieldCollection

Represents a collection of [StageCustomField](ba506544-b74f-12ec-c4a8-214bf0be1d9a.md) objects, which are custom fields in a workflow stage.



## Syntax

### CSOM

```C#
Class StageCustomFieldCollection 
```
### JSOM

```
PS.StageCustomFieldCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Stages('{stageid}')/CustomFields
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([StageCustomFieldCreationInformation](StageCustomFieldCreationInformation.md) creationInfo)](#Add_[StageCustomFieldCreationInformation]_StageCustomFieldCreationInformation.md__creationInfo_)|&#x2713;|&#x2713;|&#x2713;|[StageCustomField](StageCustomField.md)|Adds the custom field that is specified by the [StageCustomFieldCreationInformation](e2eff307-e918-7cd7-e5f8-6828ac9fb82d.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[StageCustomField](StageCustomField.md)|Gets a stage custom field from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[StageCustomField](StageCustomField.md)|Gets a stage custom field from the collection with the [Id](a17f3213-48ec-dc7f-bb50-4f8550506ae8.md) value.|
|[Remove([StageCustomField](StageCustomField.md) field)](#Remove_[StageCustomField]_StageCustomField.md__field_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified stage custom field from the collection.|



## Method Details


### <a id="Add_[StageCustomFieldCreationInformation]_StageCustomFieldCreationInformation.md__creationInfo_"></a>Add([StageCustomFieldCreationInformation](StageCustomFieldCreationInformation.md) creationInfo)
 
Adds the custom field that is specified by the [StageCustomFieldCreationInformation](e2eff307-e918-7cd7-e5f8-6828ac9fb82d.md) object to the collection.

#### Syntax

```
StageCustomField Add(StageCustomFieldCreationInformation creationInfo)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|creationInfo| [StageCustomFieldCreationInformation](StageCustomFieldCreationInformation.md) | The properties of the custom field to add to the stage.


#### Return Value

[StageCustomField](StageCustomField.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a stage custom field from the collection with the specified GUID.

#### Syntax

```
StageCustomField GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[StageCustomField](StageCustomField.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a stage custom field from the collection with the [Id](a17f3213-48ec-dc7f-bb50-4f8550506ae8.md) value.

#### Syntax

```
StageCustomField GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the stage custom field GUID.


#### Return Value

[StageCustomField](StageCustomField.md)

### <a id="Remove_[StageCustomField]_StageCustomField.md__field_"></a>Remove([StageCustomField](StageCustomField.md) field)
 
Removes the specified stage custom field from the collection.

#### Syntax

```
Boolean Remove(StageCustomField field)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|field| [StageCustomField](StageCustomField.md) | The custom field to remove.


#### Return Value

Boolean


## See Also
