[comment]: # (Name:AccrueAt)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)


# <a name="name"></a>AccrueAt enumeration



<a name="description"></a>The cost accrual mode specifies how and when resource costs are to be charged to the cost of a task.

## <a name="syntax"></a>Syntax


### CSOM

```C#
enum AccrueAt 
```
### JSOM

```JavaScript
PS.AccrueAt
```
### REST Interface

AccrueAt enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.


## <a name="members"></a>Members



<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NotSpecified"></a>NotSpecified|0| The cost accrual mode is not specified. This constant is used in place of a DBNull value.|
|<a name="Start"></a>Start|1|Costs are accrued as soon as the task assignment starts. A task assignment begins when a date is entered in the [ActualStart](PublishedAssignment.md#ActualStart) field.|
|<a name="End"></a>End|2| Costs are not accrued until the remaining work is zero.|
|<a name="Prorated"></a>Prorated|3|Costs accrue as work is scheduled to occur and as actual work is reported. This is the default value.|

## <a name="seeAlso"></a>See Also

[DraftProjectResource](DraftProjectResource.md)<br/>
[EnterpriseResource](EnterpriseResource.md)<br/>
[PublishedProjectResource](PublishedProjectResource.md)<br/>
