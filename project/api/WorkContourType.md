[comment]: # (Name:WorkContourType)
[comment]: # (Name:Microsoft.Office.Project.Server.Library.Assignment+WorkContourType)
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

```JavaScript
PS.WorkContourType
```
### REST Interface

WorkContourType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="Flat"></a>Flat|0|The default contour with an even distribution of work.|
|<a name="BackLoaded"></a>BackLoaded|1|Peak activity happens at the end of the task.|
|<a name="FrontLoaded"></a>FrontLoaded|2|Peak activity is at the beginning of the task.|
|<a name="DoublePeak"></a>DoublePeak|3|A task that has two major periods of peak activity.|
|<a name="EarlyPeak"></a>EarlyPeak|4|The same as the Front-loaded but with a ramp up to peak activity.|
|<a name="LatePeak"></a>LatePeak|5|A Back-loaded contour with a ramp.|
|<a name="Bell"></a>Bell|6|A single peak in the middle of the task.|
|<a name="Turtle"></a>Turtle|7|A bell with a ramp up and ramp down.|
|<a name="UserDefined"></a>UserDefined|8|User-defined contour type.|

## <a name="seeAlso"></a>See Also

[Assignment](Assignment.md)<br/>
