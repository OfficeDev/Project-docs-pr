[comment]: # (Name:FixedCostAccrual)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# FixedCostAccrual

Specifies how and when fixed costs are to be charged to the cost of a task.



## Syntax

### CSOM

```C#
Class FixedCostAccrual 
```
### JSOM/REST

```
PS.FixedCostAccrual
```


## Members



|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|NotSpecified|0| The fixed cost accrual mode is not specified. This constant is used in place of a DBNull value.|
|Start|1| Costs are accrued as soon as the task starts. A task begins when a date is entered in the ActualStart field.|
|End|2| Costs are not accrued until the remaining work is zero.|
|Prorated|3| This is the default value. Costs accrue as work is scheduled to occur and as actual work is reported.
|




## See Also
