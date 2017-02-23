[comment]: # (Name:TrackingMode)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)

# <a name="name"></a>TrackingMode enumeration

<a name="description"></a>Specifies the modes for tracking task progress.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum TrackingMode 
```
### JSOM

```JavaScript
PS.TrackingMode
```
### REST Interface

TrackingMode enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="None"></a>None|0|Use free-form tracking for tasks, where resources can report hours by using any method (actual hours, percent complete, or timephased).|
|<a name="TimePhased"></a>TimePhased|1|Use timephased tracking for tasks, by hours of work done per period.|
|<a name="PercentComplete"></a>PercentComplete|2|Track tasks by percentage of work complete.|
|<a name="ActualHours"></a>ActualHours|3|Track tasks by actual hours of work done and work remaining.|

## <a name="seeAlso"></a>See Also

[DraftProject](DraftProject.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
