[comment]: # (Name:EntityLinksCollection)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# EntityLinksCollection





## Syntax

### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/EntityLinks
```


## Members






### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add([EntityLinkCreationInformation](EntityLinkCreationInformation.md) parameters)](#Add_[EntityLinkCreationInformation]_EntityLinkCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[EntityLink](EntityLink.md)||
|[GetByGuid(Guid id)](#GetByGuid_Guid_id_)|&#x2713;|&#x2713;|&#x2713;|[EntityLink](EntityLink.md)||
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|void||



## Method Details


### <a id="Add_[EntityLinkCreationInformation]_EntityLinkCreationInformation.md__parameters_"></a>Add([EntityLinkCreationInformation](EntityLinkCreationInformation.md) parameters)
 


#### Syntax

```
EntityLink Add(EntityLinkCreationInformation parameters)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters| [EntityLinkCreationInformation](EntityLinkCreationInformation.md) | 


#### Return Value

[EntityLink](EntityLink.md)

### <a id="GetByGuid_Guid_id_"></a>GetByGuid(Guid id)
 


#### Syntax

```
EntityLink GetByGuid(Guid id)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|id| Guid | 


#### Return Value

[EntityLink](EntityLink.md)

### <a id="Update__"></a>Update()
 


#### Syntax

```
void Update()
```

#### Parameters

None

#### Return Value

void


## See Also
