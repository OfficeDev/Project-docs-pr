[comment]: # (Name:LookupTableMaskSequence)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupTableMaskSequence enumeration

<a name="description"></a>Specifies the mask sequence, which is the type of data for a lookup table.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum LookupTableMaskSequence 
```
### JSOM

```JavaScript
PS.LookupTableMaskSequence
```
### REST Interface

LookupTableMaskSequence enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NUMBER_TEXT"></a>NUMBER_TEXT|0|Number data expressed as a string.|
|<a name="UPPERCASE"></a>UPPERCASE|1|Uppercase character data.|
|<a name="LOWERCASE"></a>LOWERCASE|2|Lowercase character data.|
|<a name="CHARACTERS"></a>CHARACTERS|3|Mixed uppercase and lowercase character data.|
|<a name="DATE"></a>DATE|4|Date data.|
|<a name="COST"></a>COST|5|Cost data.|
|<a name="DURATION"></a>DURATION|6|Duration data.|
|<a name="NUMBER_DECIMAL"></a>NUMBER_DECIMAL|7|Decimal number data.|
|<a name="FLAG"></a>FLAG|8|Flag data (yes/no values).|

## <a name="seeAlso"></a>See Also

[LookupMask](LookupMask.md)<br/>
