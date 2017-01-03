[comment]: # (Name:LookupTableSortOrder)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupTableSortOrder enumeration

<a name="description"></a>Specifies the sort order for a lookup table.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum LookupTableSortOrder 
```
### JSOM

```JavaScript
PS.LookupTableSortOrder
```
### REST Interface

LookupTableSortOrder enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="UserDefined"></a>UserDefined|0|Custom sort; the user specifies the preferred ordering of lookup table values.|
|<a name="Ascending"></a>Ascending|1|Ascending sort; for example, A comes before B.|
|<a name="Descending"></a>Descending|2|Descending sort; for example, B comes before A.|

## <a name="seeAlso"></a>See Also

[LookupTable](LookupTable.md)<br/>
[LookupTableCreationInformation](LookupTableCreationInformation.md)<br/>
