[comment]: # (Name:EnterpriseProjectTypeCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# EnterpriseProjectTypeCollection

Represents a collection of [EnterpriseProjectType](db9e7200-331b-5f48-8a46-33cd53f916fd.md) (EPT) objects.



## Syntax

### CSOM

```C#
Class EnterpriseProjectTypeCollection 
```
### JSOM

```
PS.EnterpriseProjectTypeCollection
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/EnterpriseProjectTypes
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([EnterpriseProjectTypeCreationInformation](EnterpriseProjectTypeCreationInformation.md) parameters)](#Add_[EnterpriseProjectTypeCreationInformation]_EnterpriseProjectTypeCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseProjectType](EnterpriseProjectType.md)|Adds the enterprise project type (EPT) that is specified by the [EnterpriseProjectTypeCreationInformation](3f494850-19db-4f13-b10b-148db10519b2.md) object to the collection.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseProjectType](EnterpriseProjectType.md)|Gets an enterprise project type (EPT) from the collection with the specified GUID.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[EnterpriseProjectType](EnterpriseProjectType.md)|Gets an enterprise project type (EPT) from the collection with the [Id](48bd5e4c-738e-a342-ae20-b3af29bda639.md) value.|
|[Remove([EnterpriseProjectType](EnterpriseProjectType.md) ept)](#Remove_[EnterpriseProjectType]_EnterpriseProjectType.md__ept_)|&#x2713;|&#x2713;|&#x2713;|Boolean|Removes the specified enterprise project type (EPT) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void|Updates the enterprise project type (EPT) collection.|



## Method Details


### <a id="Add_[EnterpriseProjectTypeCreationInformation]_EnterpriseProjectTypeCreationInformation.md__parameters_"></a>Add([EnterpriseProjectTypeCreationInformation](EnterpriseProjectTypeCreationInformation.md) parameters)
 
Adds the enterprise project type (EPT) that is specified by the [EnterpriseProjectTypeCreationInformation](3f494850-19db-4f13-b10b-148db10519b2.md) object to the collection.

#### Syntax

```
EnterpriseProjectType Add(EnterpriseProjectTypeCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [EnterpriseProjectTypeCreationInformation](EnterpriseProjectTypeCreationInformation.md) | The properties of the EPT to create.


#### Return Value

[EnterpriseProjectType](EnterpriseProjectType.md)

### <a id="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets an enterprise project type (EPT) from the collection with the specified GUID.

#### Syntax

```
EnterpriseProjectType GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid| Guid | A GUID value.


#### Return Value

[EnterpriseProjectType](EnterpriseProjectType.md)

### <a id="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets an enterprise project type (EPT) from the collection with the [Id](48bd5e4c-738e-a342-ae20-b3af29bda639.md) value.

#### Syntax

```
EnterpriseProjectType GetById(String objectId)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId| String | The string representation of the EPT GUID.


#### Return Value

[EnterpriseProjectType](EnterpriseProjectType.md)

### <a id="Remove_[EnterpriseProjectType]_EnterpriseProjectType.md__ept_"></a>Remove([EnterpriseProjectType](EnterpriseProjectType.md) ept)
 
Removes the specified enterprise project type (EPT) from the collection.

#### Syntax

```
Boolean Remove(EnterpriseProjectType ept)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|ept| [EnterpriseProjectType](EnterpriseProjectType.md) | The EPT to remove.


#### Return Value

Boolean

### <a id="Update__"></a>Update()
 
Updates the enterprise project type (EPT) collection.

#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
