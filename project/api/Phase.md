[comment]: # (Name:Phase)
[comment]: # (Name:Microsoft.ProjectServer.Phase)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>Phase class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a collection of stages that are grouped to identify a common set of activities in the project life cycle.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class Phase 
```
### JSOM

```javascript
PS.Phase
```
### REST Interface

Supported.

```
PS.Phase

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Phases('{phaseid}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets a phase description.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the object identifier as a GUID.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets a phase name.|
|<a name="Stages"></a>Stages|&#x2713;|&#x2713;|&#x2713;|[StageCollection](StageCollection.md)|Gets a collection of stages for a phase.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the phase object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the phase object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[PhaseCollection](PhaseCollection.md)<br/>
[PhaseCreationInformation](PhaseCreationInformation.md)<br/>
[Project](Project.md)<br/>
[Stage](Stage.md)<br/>
