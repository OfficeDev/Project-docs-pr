[comment]: # (Name:LookupMask)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# LookupMask

Represents a mask definition for the levels of a hierarchical lookup table.



## Syntax

### CSOM

```C#
Class LookupMask 
```
### JSOM

```
PS.LookupMask
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
|Length|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the number of characters in the mask sequence or, if the mask sequence can be of any length, gets or sets the zero value of LookupTableConstants.AnyLengthSequence.|
|MaskType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[MaskSequence](MaskSequence.md)|Gets or sets the mask segment type.|
|Separator|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the separator string that is used in the concatenation of parent table entry values at each level of the table mask.|






## See Also
