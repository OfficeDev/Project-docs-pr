[comment]: # (Name:LookupEntry)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# LookupEntry

Represents a lookup table entry.



## Syntax

### CSOM

```C#
Class LookupEntry 
```
### JSOM

```
PS.LookupEntry
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/?????
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|AppAlternateId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the alternate GUID that is specified in an App package for Project Online.|
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the lookup table entry.|
|FullValue|&#x2713;|&#x2713;|&#x2713;|String|Gets the concatenated value of a hierarchical text lookup table entry.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID for the lookup table entry.|
|InternalName|&#x2713;|&#x2713;|&#x2713;|String|Gets the internal name of the lookup table entry. Reserved for internal use..|
|SortIndex|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal|Gets or sets an index number for the lookup table entry.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the LookupEntry object.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the LookupEntry object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
