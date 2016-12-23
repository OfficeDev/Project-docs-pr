[comment]: # (Name:CustomFieldType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>CustomFieldType enumeration

<a name="description"></a>Specifies the type for an enterprise custom field.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum CustomFieldType 
```
### JSOM

```JavaScript
PS.CustomFieldType
```
### REST Interface

CustomFieldType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="DATE"></a>DATE|4| A date value. HIWORD contains days offset from 1/1/84. LOWORD contains minute off-set, ranging from 0 to 1440, from 12:00 A.M. (midnight).|
|<a name="DURATION"></a>DURATION|6| Value in 1/10 minutes.|
|<a name="COST"></a>COST|9| Value in 1/100 dollars.|
|<a name="NUMBER"></a>NUMBER|15| A number value.|
|<a name="FLAG"></a>FLAG|17| Index into yes/no string table.|
|<a name="TEXT"></a>TEXT|21|A string value.|
|<a name="FINISHDATE"></a>FINISHDATE|27| A date value; if no time is included, the default finish time is used. HIWORD contains days offset from 1/1/84. LOWORD contains minute off-set, ranging from 0 to 1440, from 12:00 A.M. (midnight).|

## <a name="seeAlso"></a>See Also

[CustomField](CustomField.md)<br/>
[CustomFieldCreationInformation](CustomFieldCreationInformation.md)<br/>
[LookupTable](LookupTable.md)<br/>
