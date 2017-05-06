[comment]: # (Name:LookupMask)
[comment]: # (Name:Microsoft.ProjectServer.LookupMask)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupMask class

<a name="description"></a>Represents a mask definition for the levels of a hierarchical lookup table.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class LookupMask 
```
### JSOM

```javascript
PS.LookupMask
```
### REST Interface

Supported.

```
PS.LookupMask

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/LookupTables('{tableid}')/Masks
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Length"></a>Length|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the number of characters in the mask sequence or, if the mask sequence can be of any length, gets or sets the zero value of LookupTableConstants.AnyLengthSequence.|
|<a name="MaskType"></a>MaskType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[LookupTableMaskSequence](LookupTableMaskSequence.md)|Gets or sets the mask segment type.|
|<a name="Separator"></a>Separator|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the separator string that is used in the concatenation of parent table entry values at each level of the table mask.|

## <a name="seeAlso"></a>See Also

[LookupText](LookupText.md)<br/>
