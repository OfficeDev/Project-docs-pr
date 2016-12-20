
# AccrueAt enumeration
The cost accrual mode specifies how and when resource costs are to be charged to the cost of a task.

## Syntax

CSOM

```C#
Public Enumeration AccrueAt
```

JSOM/REST

```
PS.AccrueAt
```

## Members

|Member name |Value |Description |
|:------ |:----: |:----- |
|NotSpecified	|0 |The cost accrual mode is not specified. This constant is used in place of a DBNull value.|
|Start |1 |Costs are accrued as soon as the task assignment starts. A task assignment begins when a date is entered in the ActualStart field.|
|End |2 |Costs are not accrued until the remaining work is zero.|
|Prorated |3 |Costs accrue as work is scheduled to occur and as actual work is reported. This is the default value. |

