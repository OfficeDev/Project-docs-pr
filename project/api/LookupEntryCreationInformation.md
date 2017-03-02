[comment]: # (Name:LookupEntryCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.LookupEntryCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupEntryCreationInformation class

<a name="description"></a>Provides information for the creation of a lookup table entry.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class LookupEntryCreationInformation 
```
### JSOM

```javascript
PS.LookupEntryCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.LookupEntryCreationInformation

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/LookupTables('{tableid}')/Entries/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Description':'value', 
		'Id':'value', 
		'ParentId':'value', 
		'SortIndex':'value', 
		'Value':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the lookup table entry.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the lookup table entry.|
|<a name="ParentId"></a>ParentId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the parent lookup table entry in a hierarchical text lookup table.|
|<a name="SortIndex"></a>SortIndex|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal|Gets or sets an index number for the lookup table entry.|
|<a name="Value"></a>Value|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[LookupEntryValue](LookupEntryValue.md)|Gets or sets the value of the lookup table entry.|

## <a name="seeAlso"></a>See Also

[LookupEntry](LookupEntry.md)<br/>
[LookupEntryCollection](LookupEntryCollection.md)<br/>
