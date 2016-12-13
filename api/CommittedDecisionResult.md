[comment]: # (Name:CommittedDecisionResult)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 18:12:21Z)

# CommittedDecisionResult

Specifies whether an item is included in an optimizer function or a planner function for project portfolio analysis.



## Syntax

### CSOM

```C#
Class CommittedDecisionResult 
```
### JSOM/REST

```
PS.CommittedDecisionResult
```


## Members



|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|NotSpecified|0| The committed decision result is not specified. This constant is used in place of a DBNull value.|
|ForcedIn|1| The item is forced into the function, regardless of other filters.|
|ForcedOut|2| The item is forced out of the function, regardless of other filters.|
|CommittedOut|3| The item is not included in the function.|
|CommittedIn|4| The item is included in the function.
|




## See Also
