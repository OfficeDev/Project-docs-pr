[comment]: # (Name:LookupTableConstants)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupTableConstants enumeration

<a name="description"></a>The LookupTableConstants values can be used to help validate or set some properties of lookup table items,
## <a name="syntax"></a>Syntax

### CSOM

```C#
enum LookupTableConstants 
```
### JSOM

```JavaScript
PS.LookupTableConstants
```
### REST Interface

LookupTableConstants enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="AnyLengthSequence"></a>AnyLengthSequence|0|The length that is specified for a code mask sequence, if any length is acceptable.|
|<a name="NoSortOrder"></a>NoSortOrder|0|Specifies the default lookup table sort order, which is no sort order.|
|<a name="MinValueLength"></a>MinValueLength|1|The minimum length of an outline code value.|
|<a name="MinLevel"></a>MinLevel|1|The minimum number of levels in an outline code.|
|<a name="MaxSeparatorLength"></a>MaxSeparatorLength|3|The maximum length of any separator in a code mask.|
|<a name="MaxValueLength"></a>MaxValueLength|255|The maximum length of a description on an outline code lookup table item.|
|<a name="MaxDescriptionLength"></a>MaxDescriptionLength|255|The maximum length of a description on an outline code lookup table item.|
|<a name="MaxLevel"></a>MaxLevel|255|The maximum number of levels in an outline code.|


## <a name="seeAlso"></a>See Also

[LookupEntry](LookupEntry.md)<br/>
[LookupEntryValue](LookupEntryValue.md)<br/>
[LookupMask](LookupMask.md)<br/>
[LookupTableMaskSequence](LookupTableMaskSequence.md)<br/>