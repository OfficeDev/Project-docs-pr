[comment]: # (Name:LookupDate)
[comment]: # (Name:Microsoft.ProjectServer.LookupDate)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupDate class

inherits members from [LookupEntry](LookupEntry.md)<br/>

<a name="description"></a>Contains a data value for a lookup table of type Date.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class LookupDate 
```
### JSOM

```javascript
PS.LookupDate
```
### REST Interface

Supported.

```
PS.LookupDate

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/LookupTables('{tableid}')/Entries('{entryid}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Value"></a>Value|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a data value of type Date.|

## <a name="seeAlso"></a>See Also

[LookupEntry](LookupEntry.md)