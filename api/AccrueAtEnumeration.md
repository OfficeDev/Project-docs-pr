
# AccrueAt enumeration
The cost accrual mode specifies how and when resource costs are to be charged to the cost of a task.

 **Namespace:**[Microsoft.ProjectServer.Client](e79057b8-4161-453c-1035-02e38725305c.md) **Assembly:**Microsoft.ProjectServer.Client (in Microsoft.ProjectServer.Client.dll)
## Syntax


```C#
Public Enumeration AccrueAt
```


## Members

| Member name	| Description |
|:------ |:----- |
|NotSpecified	|Value=0. The cost accrual mode is not specified. This constant is used in place of a DBNull value.|
|Start |Value=1. Costs are accrued as soon as the task assignment starts. A task assignment begins when a date is entered in the ActualStart field.|
|End |Value=2. Costs are not accrued until the remaining work is zero.|
|Prorated |Value=3. Costs accrue as work is scheduled to occur and as actual work is reported. This is the default value. |
<br />


**Here is a 3-column version of the same info. Included so you can see an alternative layout.**


|Member name |Value |Description |
|:------ |:----: |:----- |
|NotSpecified	|0 |The cost accrual mode is not specified. This constant is used in place of a DBNull value.|
|Start |1 |Costs are accrued as soon as the task assignment starts. A task assignment begins when a date is entered in the ActualStart field.|
|End |2 |Costs are not accrued until the remaining work is zero.|
|Prorated |3 |Costs accrue as work is scheduled to occur and as actual work is reported. This is the default value. |


## Remarks

The AccrueAt enumeration in the CSOM is equivalent to **AccrueAt** in theMicrosoft.Office.Project.Server.Library namespace. TheAccrueAt constants can be used with the[DraftProjectResource.CostAccrual](e3ee589e-517c-d752-444d-9fe447d7fe39.md) property and the[PublishedProjectResource.CostAccrual](c7fd5b9f-c706-b157-c948-d047521904fb.md) property.


## See also


#### Reference


[Microsoft.ProjectServer.Client namespace](e79057b8-4161-453c-1035-02e38725305c.md)