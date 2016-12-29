[comment]: # (Name:CustomFieldRollupType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>CustomFieldRollupType enumeration

<a name="description"></a>Specifies the summary roll-up type for a custom field.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum CustomFieldRollupType 
```
### JSOM

```JavaScript
PS.CustomFieldRollupType
```
### REST Interface

CustomFieldRollupType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NotSpecified"></a>NotSpecified|0||
|<a name="Max"></a>Max|1||
|<a name="Min"></a>Min|2| Minimum.|
|<a name="Count"></a>Count|3| Count.|
|<a name="Sum"></a>Sum|4| Sum.|
|<a name="Average"></a>Average|5| Average.|
|<a name="AverageSublevel"></a>AverageSublevel|6| Average sublevel.|
|<a name="CountSublevel"></a>CountSublevel|7| Count sublevel.|
|<a name="CountNonSummary"></a>CountNonSummary|8| Count non-summary.|
|<a name="StdDev"></a>StdDev|9| Standard deviation.|
|<a name="Formula"></a>Formula|10| Formula.|
|<a name="None"></a>None|11|None.|

## <a name="seeAlso"></a>See Also

[CustomField](CustomField.md)<br/>
