[comment]: # (Name:LookupTable)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# LookupTable

Represents a lookup table.



## Syntax

### CSOM

```C#
Class LookupTable 
```
### JSOM

```
PS.LookupTable
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/LookupTables('{tableid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|AppAlternateId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the alternate lookup table GUID that is specified in an App package for Project Online.|
|Entries|&#x2713;|&#x2713;|&#x2713;|[LookupEntryCollection](LookupEntryCollection.md)|Gets the collection of entries in the lookup table.|
|FieldType|&#x2713;|&#x2713;|&#x2713;|[Type](Type.md)|Gets the custom field type that matches the values in the lookup table.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the lookup table.|
|Masks|&#x2713;|&#x2713;|&#x2713;|ReadOnlyCollection`1|Gets the collection of mask definitions for the levels of a hierarchical lookup table.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the lookup table.|
|SortOrder|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[SortOrder](SortOrder.md)|Gets or sets the sort-order for the entries in the table.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the LookupTable object.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the LookupTable object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
