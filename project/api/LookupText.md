[comment]: # (Name:LookupText)
[comment]: # (Name:Microsoft.ProjectServer.LookupText)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupText class

inherits members from [LookupEntry](LookupEntry.md)<br/>

<a name="description"></a>Defines an entry in a lookup table of type Text.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class LookupText 
```
### JSOM

```javascript
PS.LookupText
```
### REST Interface

Supported.

```
PS.LookupText

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/LookupTables('{tableid}')/Entries('{entryid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="HasChildren"></a>HasChildren|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether an entry in a hierarchical text lookup table has descendants.|
|<a name="Mask"></a>Mask|&#x2713;|&#x2713;|&#x2713;|[LookupMask](LookupMask.md)|Gets the mask for an entry in a hierarhical text lookup table.|
|<a name="Parent"></a>Parent|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[LookupText](LookupText.md)|Gets or sets the GUID of a parent entry in a hierarchical text lookup table.|
|<a name="Value"></a>Value|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets a data value of type Text.|

## <a name="seeAlso"></a>See Also

[LookupEntry](LookupEntry.md)