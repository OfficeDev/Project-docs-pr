[comment]: # (Name:LookupTableCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# LookupTableCollection

Represents a collection of [LookupTable](4ca341bf-80d1-6db8-d7ae-b78c4c0d86c2.md) objects.



## Syntax

### CSOM

```C#
Class LookupTableCollection 
```
### JSOM

```
PS.LookupTableCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/LookupTables
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([LookupTableCreationInformation](LookupTableCreationInformation.md) parameters)](#Add_[LookupTableCreationInformation]_LookupTableCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[LookupTable](LookupTable.md)|Adds the lookup table that is specified by the [LookupTableCreationInformation](94bf6aee-3a5b-ca47-5e45-8e799fd7cbb4.md) object to the collection.|
|[GetByAppAlternateId(String objectId)](#GetByAppAlternateId_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[LookupTable](LookupTable.md)|Get an element from the lookup table collection by using the alternate object GUID that is specified in an App package for Project Online.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[LookupTable](LookupTable.md)|Gets a lookup table from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[LookupTable](LookupTable.md)|Gets a lookup table from the collection with the [Id](c7a9c765-62b1-44d0-b263-f4f1e2b65e14.md) value.|
|[Remove([LookupTable](LookupTable.md) table)](#Remove_[LookupTable]_LookupTable.md__table_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified lookup table from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void|Updates the lookup table collection.|



## Method Details


### <a id="Add_[LookupTableCreationInformation]_LookupTableCreationInformation.md__parameters_"></a>Add([LookupTableCreationInformation](LookupTableCreationInformation.md) parameters)
 
Adds the lookup table that is specified by the [LookupTableCreationInformation](94bf6aee-3a5b-ca47-5e45-8e799fd7cbb4.md) object to the collection.

#### Syntax

```
LookupTable Add(LookupTableCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [LookupTableCreationInformation](LookupTableCreationInformation.md) | The properties of the lookup table to create.


#### Return Value

[LookupTable](LookupTable.md)

### <a id="GetByAppAlternateId_String_objectId_"></a>GetByAppAlternateId(String objectId)
 
Get an element from the lookup table collection by using the alternate object GUID that is specified in an App package for Project Online.

#### Syntax

```
LookupTable GetByAppAlternateId(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The alternate custom field GUID.


#### Return Value

[LookupTable](LookupTable.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a lookup table from the collection with the specified GUID.

#### Syntax

```
LookupTable GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[LookupTable](LookupTable.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a lookup table from the collection with the [Id](c7a9c765-62b1-44d0-b263-f4f1e2b65e14.md) value.

#### Syntax

```
LookupTable GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the lookup table GUID.


#### Return Value

[LookupTable](LookupTable.md)

### <a id="Remove_[LookupTable]_LookupTable.md__table_"></a>Remove([LookupTable](LookupTable.md) table)
 
Removes the specified lookup table from the collection.

#### Syntax

```
Boolean Remove(LookupTable table)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|table| [LookupTable](LookupTable.md) | The lookup table to remove.


#### Return Value

Boolean

### <a id="Update__"></a>Update()
 
Updates the lookup table collection.

#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
