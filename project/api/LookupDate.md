[comment]: # (Name:LookupDate)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupDate class

inherits members from [LookupEntry](LookupEntry.md)<br/>

<a name="description"></a>Contains a data value for a lookup table of type Date.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class LookupDate 
```
### JSOM

```JavaScript
PS.LookupDate
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.LookupDate

http://<sitecollection>/<site>/api/ProjectServer/LookupTables('{tableid}')/Entries('{entryid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Value"></a>Value|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets a data value of type Date.|

## <a name="seeAlso"></a>See Also

[LookupEntry](LookupEntry.md)