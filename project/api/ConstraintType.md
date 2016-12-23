[comment]: # (Name:ConstraintType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>ConstraintType enumeration

<a name="description"></a>Specifies the constraint type for a task.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum ConstraintType 
```
### JSOM

```JavaScript
PS.ConstraintType
```
### REST Interface

ConstraintType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NotSpecified"></a>NotSpecified|0| The task constraint type is not specified. This constant is used in place of a DBNull value.|
|<a name="AsSoonAsPossible"></a>AsSoonAsPossible|1| As soon as possible (ASAP). This is the default value.|
|<a name="AsLateAsPossible"></a>AsLateAsPossible|2| As late as possible (ALAP).|
|<a name="MustStartOn"></a>MustStartOn|3| Must start on (MSO).|
|<a name="MustFinishOn"></a>MustFinishOn|4| Must finish on (MFO).|
|<a name="StartNoEarlierThan"></a>StartNoEarlierThan|5| Start no earlier than (SNET).|
|<a name="StartNoLaterThan"></a>StartNoLaterThan|6| Start no later than (SNLT).|
|<a name="FinishNoEarlierThan"></a>FinishNoEarlierThan|7| Finish no earlier than (FNET).|
|<a name="FinishNoLaterThan"></a>FinishNoLaterThan|8| Finish no later than (FNLT).
|

## <a name="seeAlso"></a>See Also

[DraftTask](DraftTask.md)<br/>
[PublishedTask](PublishedTask.md)<br/>
