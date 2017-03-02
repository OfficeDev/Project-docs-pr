[comment]: # (Name:FixedCostAccrual)
[comment]: # (Name:Microsoft.ProjectServer.FixedCostAccrual)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>FixedCostAccrual enumeration

<a name="description"></a>Specifies how and when fixed costs are to be charged to the cost of a task.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum FixedCostAccrual 
```
### JSOM

```javascript
PS.FixedCostAccrual
```
### REST Interface

FixedCostAccrual enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NotSpecified"></a>NotSpecified|0|The fixed cost accrual mode is not specified. This constant is used in place of a DBNull value.|
|<a name="Start"></a>Start|1|Costs are accrued as soon as the task starts. A task begins when a date is entered in the ActualStart field.|
|<a name="End"></a>End|2|Costs are not accrued until the remaining work is zero.|
|<a name="Prorated"></a>Prorated|3|This is the default value. Costs accrue as work is scheduled to occur and as actual work is reported.|

## <a name="seeAlso"></a>See Also

[DraftProject](DraftProject.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
[Task](Task.md)<br/>
