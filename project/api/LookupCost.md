[comment]: # (Name:LookupCost)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupCost class

inherits members from [LookupEntry](LookupEntry.md)<br/>

<a name="description"></a>Contains a data value for a lookup table of type Cost.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class LookupCost 
```
### JSOM

```JavaScript
PS.LookupCost
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.LookupCost

http://<sitecollection>/<site>/api/ProjectServer/LookupTables('{tableid}')/Entries('{entryid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Value"></a>Value|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal|Gets or sets a data value of type Cost.|

## <a name="seeAlso"></a>See Also

[LookupEntry](LookupEntry.md)