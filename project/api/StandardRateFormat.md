[comment]: # (Name:StandardRateFormat)
[comment]: # (Name:Microsoft.Office.Project.Server.Library.Resource+StandardRateFormat)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>StandardRateFormat enumeration

<a name="description"></a>Specifies the time unit of the resource rate; that is, the rate per time unit, such as dollars per hour.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum StandardRateFormat 
```
### JSOM

```javascript
PS.StandardRateFormat
```
### REST Interface

StandardRateFormat enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="Minute"></a>Minute|1|The resource rate is per minute.|
|<a name="Hour"></a>Hour|2|The resource rate is per hour.|
|<a name="Day"></a>Day|3|The resource rate is per day.|
|<a name="Week"></a>Week|4|The resource rate is per week.|
|<a name="Month"></a>Month|5|The resource rate is per month.|
|<a name="Year"></a>Year|7|The resource rate is per year.|
|<a name="Material"></a>Material|8|The resource is a material; it does not have a rate per time unit.|

## <a name="seeAlso"></a>See Also

[DraftProjectResource](DraftProjectResource.md)<br/>
[Project](Project.md)<br/>
[PublishedProjectResource](PublishedProjectResource.md)<br/>
