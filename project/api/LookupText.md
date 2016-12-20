[comment]: # (Name:LookupText)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# LookupText

Defines an entry in a lookup table of type Text.



## Syntax

### CSOM

```C#
Class LookupText 
```
### JSOM

```
PS.LookupText
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/LookupTables('{tableid}')/Entries('{entryid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|HasChildren|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether an entry in a hierarchical text lookup table has descendants.|
|Mask|&#x2713;|&#x2713;|&#x2713;|[LookupMask](LookupMask.md)|Gets the mask for an entry in a hierarhical text lookup table.|
|Parent|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[LookupText](LookupText.md)|Gets or sets the GUID of a parent entry in a hierarchical text lookup table.|
|Value|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets a data value of type Text.|






## See Also
