[comment]: # (Name:LookupEntryCreationInformation)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# LookupEntryCreationInformation

Provides information for the creation of a lookup table entry.



## Syntax

### CSOM

```C#
Class LookupEntryCreationInformation 
```
### JSOM

```
PS.LookupEntryCreationInformation
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
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the lookup table entry.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the lookup table entry.|
|ParentId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the parent lookup table entry in a hierarchical text lookup table.|
|SortIndex|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal|Gets or sets an index number for the lookup table entry.|
|Value|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[LookupEntryValue](LookupEntryValue.md)|Gets or sets the value of the lookup table entry.|






## See Also
