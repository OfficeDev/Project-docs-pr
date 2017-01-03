[comment]: # (Name:LookupDuration)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupDuration class

inherits members from [LookupEntry](LookupEntry.md)<br/>

<a name="description"></a>Contains a data value for a lookup table of type Duration.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class LookupDuration 
```
### JSOM

```JavaScript
PS.LookupDuration
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.LookupDuration

http://<sitecollection>/<site>/api/ProjectServer/LookupTables('{tableid}')/Entries('{entryid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Value"></a>Value|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the string value in a lookup table of type Duration.|
|<a name="ValueMilliseconds"></a>ValueMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the duration in milliseconds, in a lookup table of typeDuration.|
|<a name="ValueTimeSpan"></a>ValueTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the duration as a TimeSpan value in a lookup table of typeDuration.|

## <a name="seeAlso"></a>See Also
[LookupEntry](LookupEntry.md)
