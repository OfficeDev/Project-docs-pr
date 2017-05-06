[comment]: # (Name:LookupDuration)
[comment]: # (Name:Microsoft.ProjectServer.LookupDuration)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupDuration class

inherits members from [LookupEntry](LookupEntry.md)<br/>

<a name="description"></a>Contains a data value for a lookup table of type Duration.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class LookupDuration 
```
### JSOM

```javascript
PS.LookupDuration
```
### REST Interface

Supported.

```
PS.LookupDuration

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/LookupTables('{tableid}')/Entries('{entryid}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties

> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Value"></a>Value|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the string value in a lookup table of type Duration.|
|<a name="ValueMilliseconds"></a>ValueMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the duration in milliseconds, in a lookup table of typeDuration.|
|<a name="ValueTimeSpan"></a>ValueTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the duration as a TimeSpan value in a lookup table of typeDuration.|

## <a name="seeAlso"></a>See Also
[LookupEntry](LookupEntry.md)
