[comment]: # (Name:ServiceStatus)
[comment]: # (Name:Microsoft.ProjectServer.ServiceStatus)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ServiceStatus class

<a name="description"></a>Provides information about the status of the Project Server service.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ServiceStatus 
```
### JSOM

```javascript
PS.ServiceStatus
```
### REST Interface

See [ProjectContext](ProjectContext.md) for the REST properties/methods.
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="IsDelegate"></a>IsDelegate|&#x2713;|&#x2713;||Boolean|Gets a value that indicates whether the current user has started a delegation session in PWA.|
|<a name="IsReadOnly"></a>IsReadOnly|&#x2713;|&#x2713;||Boolean|Gets a value that indicates whether the Project Server database is in read-only mode.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[StopDelegation()](#StopDelegation__)|&#x2713;|&#x2713;||void|Stops the current delegation session.|

<br/>
#### Method Details

#### <a name="StopDelegation__"></a>StopDelegation()
 
Stops the current delegation session.

##### Syntax

```
void StopDelegation()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

