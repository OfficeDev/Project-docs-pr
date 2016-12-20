[comment]: # (Name:WorkContourType)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)

# <a name="name"></a>WorkContourType enumeration

<a name="description"></a>Indicates how to distribute work for an assignment across the duration of the assignment.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum WorkContourType 
```
### JSOM

```
PS.WorkContourType
```
### REST Interface

WorkContourType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="Flat"></a>Flat|0||
|<a name="BackLoaded"></a>BackLoaded|1||
|<a name="FrontLoaded"></a>FrontLoaded|2||
|<a name="DoublePeak"></a>DoublePeak|3||
|<a name="EarlyPeak"></a>EarlyPeak|4||
|<a name="LatePeak"></a>LatePeak|5||
|<a name="Bell"></a>Bell|6||
|<a name="Turtle"></a>Turtle|7||
|<a name="UserDefined"></a>UserDefined|8||

## <a name="seeAlso"></a>See Also

[Assignment](Assignment.md)<br/>
