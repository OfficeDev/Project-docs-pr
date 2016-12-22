[comment]: # (Name:CommittedDecisionResult)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>CommittedDecisionResult enumeration

<a name="description"></a>Specifies whether an item is included in an optimizer function or a planner function for project portfolio analysis.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum CommittedDecisionResult 
```
### JSOM

```
PS.CommittedDecisionResult
```
### REST Interface

CommittedDecisionResult enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NotSpecified"></a>NotSpecified|0| The committed decision result is not specified. This constant is used in place of a DBNull value.|
|<a name="ForcedIn"></a>ForcedIn|1| The item is forced into the function, regardless of other filters.|
|<a name="ForcedOut"></a>ForcedOut|2| The item is forced out of the function, regardless of other filters.|
|<a name="CommittedOut"></a>CommittedOut|3| The item is not included in the function.|
|<a name="CommittedIn"></a>CommittedIn|4| The item is included in the function.
|

## <a name="seeAlso"></a>See Also

[Project](Project.md)<br/>
