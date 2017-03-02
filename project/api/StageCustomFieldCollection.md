[comment]: # (Name:StageCustomFieldCollection)
[comment]: # (Name:Microsoft.ProjectServer.StageCustomFieldCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StageCustomFieldCollection class

inherits members from [ClientObjectCollection<StageCustomField>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [StageCustomField](StageCustomField.md) objects, which are custom fields in a workflow stage.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StageCustomFieldCollection 
```
### JSOM

```javascript
PS.StageCustomFieldCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.StageCustomFieldCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Stages('{stageid}')/CustomFields
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[StageCustomField](StageCustomField.md)|Gets a [StageCustomField](StageCustomField.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[StageCustomField](StageCustomField.md)|Gets a [StageCustomField](StageCustomField.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{StageCustomFieldId}&#39;](#&#39;{StageCustomFieldId}&#39;)|||&#x2713;|[StageCustomField](StageCustomField.md)|Gets a [StageCustomField](StageCustomField.md) from the collection with the specified StageCustomFieldId.|
|[Add(StageCustomFieldCreationInformation creationInfo)](#Add_[StageCustomFieldCreationInformation]_StageCustomFieldCreationInformation.md__creationInfo_)|&#x2713;|&#x2713;|&#x2713;|[StageCustomField](StageCustomField.md)|Adds the [StageCustomField](StageCustomField.md) that is specified by the [StageCustomFieldCreationInformation](StageCustomFieldCreationInformation.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[StageCustomField](StageCustomField.md)|Gets a [StageCustomField](StageCustomField.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[StageCustomField](StageCustomField.md)|Gets a [StageCustomField](StageCustomField.md) from the collection with the Guid value.|
|[Remove(StageCustomField field)](#Remove_[StageCustomField]_StageCustomField.md__field_)|&#x2713;|&#x2713;||Boolean|Removes the specified [StageCustomField](StageCustomField.md) from the collection.|

<br/>
#### Method Details

#### <a name="&#39;{StageCustomFieldId}&#39;"></a>&#39;{StageCustomFieldId}&#39;
 
Gets a [StageCustomField](StageCustomField.md) from the collection with the specified StageCustomFieldId.

##### Syntax

```
StageCustomField http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Stages('{stageid}')/CustomFields('{StageCustomFieldId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|StageCustomFieldId|String|the id of the StageCustomField|

##### Return Value

[StageCustomField](StageCustomField.md)

#### <a name="Add_[StageCustomFieldCreationInformation]_StageCustomFieldCreationInformation.md__creationInfo_"></a>Add([StageCustomFieldCreationInformation](StageCustomFieldCreationInformation.md) creationInfo)
 
Adds the [StageCustomField](StageCustomField.md) that is specified by the [StageCustomFieldCreationInformation](StageCustomFieldCreationInformation.md) object to the collection.

##### Syntax

```
StageCustomField Add(StageCustomFieldCreationInformation creationInfo)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|creationInfo|[StageCustomFieldCreationInformation](StageCustomFieldCreationInformation.md)|The properties that can be set when creating a stage custom field.|

##### Return Value

[StageCustomField](StageCustomField.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [StageCustomField](StageCustomField.md) from the collection with the Id value.

##### Syntax

```
StageCustomField GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [StageCustomField](StageCustomField.md)|

##### Return Value

[StageCustomField](StageCustomField.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [StageCustomField](StageCustomField.md) from the collection with the Guid value.

##### Syntax

```
StageCustomField GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [StageCustomField](StageCustomField.md).|

##### Return Value

[StageCustomField](StageCustomField.md)

#### <a name="Remove_[StageCustomField]_StageCustomField.md__field_"></a>Remove([StageCustomField](StageCustomField.md) field)
 
Removes the specified [StageCustomField](StageCustomField.md) from the collection.

##### Syntax

```
Boolean Remove(StageCustomField field)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|field|[StageCustomField](StageCustomField.md)|The [StageCustomField](StageCustomField.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[Stage](Stage.md)<br/>
[StageCustomField](StageCustomField.md)<br/>
[StageCustomFieldCreationInformation](StageCustomFieldCreationInformation.md)<br/>
