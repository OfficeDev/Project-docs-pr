[comment]: # (Name:LookupMask)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>LookupMask class

<a name="description"></a>Represents a mask definition for the levels of a hierarchical lookup table.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class LookupMask 
```
### JSOM

```JavaScript
PS.LookupMask
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.LookupMask

http://<sitecollection>/<site>/api/ProjectServer/LookupTables('{tableid}')/Masks
http://<sitecollection>/<site>/api/ProjectServer/LookupTables('{tableid}')/Entries('{entryid}')/Mask (LookupText)

```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Length"></a>Length|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the number of characters in the mask sequence or, if the mask sequence can be of any length, gets or sets the zero value of LookupTableConstants.AnyLengthSequence.|
|<a name="MaskType"></a>MaskType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[MaskSequence](MaskSequence.md)|Gets or sets the mask segment type.|
|<a name="Separator"></a>Separator|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the separator string that is used in the concatenation of parent table entry values at each level of the table mask.|

## <a name="seeAlso"></a>See Also

[LookupText](LookupText.md)<br/>
