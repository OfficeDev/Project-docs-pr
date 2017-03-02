[comment]: # (Name:TimePhase)
[comment]: # (Name:Microsoft.ProjectServer.TimePhase)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TimePhase class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents assignment progress information that is distributed over time.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TimePhase 
```
### JSOM

```javascript
PS.TimePhase
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.TimePhase

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EnterpriseResources('{resourceid}')/Assignments/GetTimePhaseByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Assignments"></a>Assignments|&#x2713;|&#x2713;|&#x2713;|[StatusAssignmentCollection](StatusAssignmentCollection.md)|Gets the status of assignments associated with a timephase.|
|<a name="End"></a>End|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the end date of a timephase period.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the start date of the timephase period.|

## <a name="seeAlso"></a>See Also

[StatusAssignmentCollection](StatusAssignmentCollection.md)<br/>
