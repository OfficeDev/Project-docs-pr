[comment]: # (Name:EntityLink)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# EntityLink





## Syntax

### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/EntityLinks('EntityLink.Id')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Created|&#x2713;|&#x2713;|&#x2713;|DateTime||
|EntityLinkType|&#x2713;|&#x2713;|&#x2713;|[EntityLinkType](EntityLinkType.md)||
|Id|&#x2713;|&#x2713;|&#x2713;|Guid||
|Url|&#x2713;|&#x2713;|&#x2713;|String||





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void||



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 


#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
