[comment]: # (Name:TimeSheetPeriod)
[comment]: # (Name:Microsoft.ProjectServer.TimeSheetPeriod)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>TimeSheetPeriod class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a defined period of time on a timesheet.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class TimeSheetPeriod 
```
### JSOM

```javascript
PS.TimeSheetPeriod
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.TimeSheetPeriod

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/TimeSheetPeriods('{periodid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="End"></a>End|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the end date of a timesheet period.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the timesheet period.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the timesheet period.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the start date of the timesheet period.|
|<a name="TimeSheet"></a>TimeSheet|&#x2713;|&#x2713;|&#x2713;|[TimeSheet](TimeSheet.md)|Gets the timesheet that is associated with the timesheet period.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[CreateTimeSheet()](#CreateTimeSheet__)|&#x2713;|&#x2713;|&#x2713;|[TimeSheet](TimeSheet.md)|Creates a new TimeSheet object.|

<br/>
#### Method Details

#### <a name="CreateTimeSheet__"></a>CreateTimeSheet()
 
Creates a new TimeSheet object.

##### Syntax

```
TimeSheet CreateTimeSheet()
```

##### Parameters

None

##### Return Value

[TimeSheet](TimeSheet.md)

## <a name="seeAlso"></a>See Also

[TimeSheet](TimeSheet.md)<br/>
[TimeSheetPeriodCollection](TimeSheetPeriodCollection.md)<br/>
