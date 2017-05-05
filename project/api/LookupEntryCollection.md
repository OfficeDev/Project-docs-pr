[comment]: # (Name:LookupEntryCollection)
[comment]: # (Name:Microsoft.ProjectServer.LookupEntryCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupEntryCollection class

inherits members from [ClientObjectCollection<LookupEntry>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [LookupEntry](LookupEntry.md) objects for a lookup table.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class LookupEntryCollection 
```
### JSOM

```javascript
PS.LookupEntryCollection
```
### REST Interface

Supported.

```
PS.LookupEntryCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/LookupTables('{tableid}')/Entries
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[LookupEntry](LookupEntry.md)|Gets a [LookupEntry](LookupEntry.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[LookupEntry](LookupEntry.md)|Gets a [LookupEntry](LookupEntry.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{LookupEntryId}&#39;](#&#39;{LookupEntryId}&#39;)|||&#x2713;|[LookupEntry](LookupEntry.md)|Gets a [LookupEntry](LookupEntry.md) from the collection with the specified LookupEntryId.|
|[Add(LookupEntryCreationInformation parameters)](#Add_[LookupEntryCreationInformation]_LookupEntryCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[LookupEntry](LookupEntry.md)|Adds the [LookupEntry](LookupEntry.md) that is specified by the [LookupEntryCreationInformation](LookupEntryCreationInformation.md) object to the collection.|
|[GetByAppAlternateId(String objectId)](#GetByAppAlternateId_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[LookupEntry](LookupEntry.md)|Gets a lookup entry from the collection by using the alternate lookup entry GUID that is specified in an App package for Project Server online.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[LookupEntry](LookupEntry.md)|Gets a [LookupEntry](LookupEntry.md) from the collection with the Id value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[LookupEntry](LookupEntry.md)|Gets a [LookupEntry](LookupEntry.md) from the collection with the Guid value.|
|[Remove(LookupEntry entry)](#Remove_[LookupEntry]_LookupEntry.md__entry_)|&#x2713;|&#x2713;||Boolean|Removes the specified [LookupEntry](LookupEntry.md) from the collection.|

<br/>
#### Method Details

#### <a name="&#39;{LookupEntryId}&#39;"></a>&#39;{LookupEntryId}&#39;
 
Gets a [LookupEntry](LookupEntry.md) from the collection with the specified LookupEntryId.

##### Syntax

```
LookupEntry http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/LookupTables('{tableid}')/Entries('{LookupEntryId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|LookupEntryId|String|the id of the LookupEntry|

##### Return Value

[LookupEntry](LookupEntry.md)

#### <a name="Add_[LookupEntryCreationInformation]_LookupEntryCreationInformation.md__parameters_"></a>Add([LookupEntryCreationInformation](LookupEntryCreationInformation.md) parameters)
 
Adds the [LookupEntry](LookupEntry.md) that is specified by the [LookupEntryCreationInformation](LookupEntryCreationInformation.md) object to the collection.

##### Syntax

```
LookupEntry Add(LookupEntryCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[LookupEntryCreationInformation](LookupEntryCreationInformation.md)|The properties that can be set when creating a lookup entry.|

##### Return Value

[LookupEntry](LookupEntry.md)

#### <a name="GetByAppAlternateId_String_objectId_"></a>GetByAppAlternateId(String objectId)
 
Gets a lookup entry from the collection by using the alternate lookup entry GUID that is specified in an App package for Project Server online.

##### Syntax

```
LookupEntry GetByAppAlternateId(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|A string object identifier.|

##### Return Value

[LookupEntry](LookupEntry.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [LookupEntry](LookupEntry.md) from the collection with the Id value.

##### Syntax

```
LookupEntry GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [LookupEntry](LookupEntry.md)|

##### Return Value

[LookupEntry](LookupEntry.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [LookupEntry](LookupEntry.md) from the collection with the Guid value.

##### Syntax

```
LookupEntry GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [LookupEntry](LookupEntry.md).|

##### Return Value

[LookupEntry](LookupEntry.md)

#### <a name="Remove_[LookupEntry]_LookupEntry.md__entry_"></a>Remove([LookupEntry](LookupEntry.md) entry)
 
Removes the specified [LookupEntry](LookupEntry.md) from the collection.

##### Syntax

```
Boolean Remove(LookupEntry entry)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|entry|[LookupEntry](LookupEntry.md)|The [LookupEntry](LookupEntry.md) to remove.|

##### Return Value

Boolean

## <a name="seeAlso"></a>See Also

[CustomField](CustomField.md)<br/>
[LookupEntry](LookupEntry.md)<br/>
[LookupEntryCreationInformation](LookupEntryCreationInformation.md)<br/>
[LookupTable](LookupTable.md)<br/>
[WorkflowDesignerField](WorkflowDesignerField.md)<br/>
