[comment]: # (Name:LookupEntryCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# LookupEntryCollection

Represents a collection of [LookupEntry](67da167a-c3d9-c801-ca45-dc46221d7df0.md) objects for a lookup table.



## Syntax

### CSOM

```C#
Class LookupEntryCollection 
```
### JSOM

```
PS.LookupEntryCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/LookupTables('{tableid}')/Entries
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([LookupEntryCreationInformation](LookupEntryCreationInformation.md) parameters)](#Add_[LookupEntryCreationInformation]_LookupEntryCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[LookupEntry](LookupEntry.md)|Adds the lookup entry that is specified by the [LookupEntryCreationInformation](e69e0f6f-1d75-4b73-f523-f629e4d5ec7c.md) object to the collection.|
|[GetByAppAlternateId(String objectId)](#GetByAppAlternateId_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[LookupEntry](LookupEntry.md)|Gets a lookup entry from the collection by using the alternate lookup entry GUID that is specified in an App package for Project Server online.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[LookupEntry](LookupEntry.md)|Gets a lookup entry from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[LookupEntry](LookupEntry.md)|Returns the lookup entry that is specified by the [Id](060405f9-202e-2ab3-2d01-3757ae35223a.md) value.|
|[Remove([LookupEntry](LookupEntry.md) entry)](#Remove_[LookupEntry]_LookupEntry.md__entry_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified lookup entry from the collection.|



## Method Details


### <a id="Add_[LookupEntryCreationInformation]_LookupEntryCreationInformation.md__parameters_"></a>Add([LookupEntryCreationInformation](LookupEntryCreationInformation.md) parameters)
 
Adds the lookup entry that is specified by the [LookupEntryCreationInformation](e69e0f6f-1d75-4b73-f523-f629e4d5ec7c.md) object to the collection.

#### Syntax

```
LookupEntry Add(LookupEntryCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [LookupEntryCreationInformation](LookupEntryCreationInformation.md) | The properties of the lookup entry to create.


#### Return Value

[LookupEntry](LookupEntry.md)

### <a id="GetByAppAlternateId_String_objectId_"></a>GetByAppAlternateId(String objectId)
 
Gets a lookup entry from the collection by using the alternate lookup entry GUID that is specified in an App package for Project Server online.

#### Syntax

```
LookupEntry GetByAppAlternateId(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | A string object identifier.


#### Return Value

[LookupEntry](LookupEntry.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a lookup entry from the collection with the specified GUID.

#### Syntax

```
LookupEntry GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[LookupEntry](LookupEntry.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Returns the lookup entry that is specified by the [Id](060405f9-202e-2ab3-2d01-3757ae35223a.md) value.

#### Syntax

```
LookupEntry GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the lookup entry GUID.


#### Return Value

[LookupEntry](LookupEntry.md)

### <a id="Remove_[LookupEntry]_LookupEntry.md__entry_"></a>Remove([LookupEntry](LookupEntry.md) entry)
 
Removes the specified lookup entry from the collection.

#### Syntax

```
Boolean Remove(LookupEntry entry)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|entry| [LookupEntry](LookupEntry.md) | The lookup entry to remove.


#### Return Value

Boolean


## See Also
