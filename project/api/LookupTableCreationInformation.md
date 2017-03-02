[comment]: # (Name:LookupTableCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.LookupTableCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupTableCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [LookupTable](LookupTable.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class LookupTableCreationInformation 
```
### JSOM

```javascript
PS.LookupTableCreationInformation
```
### REST Interface

This resource supports POST HTTP commands.

```
PS.LookupTableCreationInformation

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/LookupTables/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'Entries':'value', 
		'Id':'value', 
		'Masks':'value', 
		'Name':'value', 
		'SortOrder':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Entries"></a>Entries|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|ReadOnlyCollection`1|Gets or sets the collection of entries in the lookup table.|
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the lookup table.|
|<a name="Masks"></a>Masks|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Collection([LookupMask](LookupMake.md))|Gets or sets the collection of mask definitions for the levels of a hierarchical lookup table.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the lookup table.|
|<a name="SortOrder"></a>SortOrder|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[LookupTableSortOrder](LookupTableSortOrder.md)|Gets or sets the sort order for the entries in the table.|

## <a name="seeAlso"></a>See Also

[LookupMask](LookupMask.md)<br/>
[LookupTable](LookupTable.md)<br/>
[LookupTableCollection](LookupTableCollection.md)<br/>
