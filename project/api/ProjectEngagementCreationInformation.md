[comment]: # (Name:ProjectEngagementCreationInformation)
[comment]: # (Name:Microsoft.ProjectServer.ProjectEngagementCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectEngagementCreationInformation class

inherits members from [EngagementCreationInformation](EngagementCreationInformation.md)<br/>

<a name="description"></a>Contains the properties that can be set when creating a [ProjectEngagement](ProjectEngagement.md).

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectEngagementCreationInformation 
```
### JSOM

```javascript
PS.ProjectEngagementCreationInformation
```
### REST Interface

Supported.

```
PS.ProjectEngagementCreationInformation

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/Projects('{projectid}')/Engagements/Add
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'ResourceId':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Resource"></a>Resource|&#x2713;&#x02B7;|&#x2713;&#x02B7;||[EnterpriseResource](EnterpriseResource.md)||
|<a name="ResourceId"></a>ResourceId|||&#x2713;&#x02B7;|Guid||

## <a name="seeAlso"></a>See Also

[ProjectEngagement](ProjectEngagement.md)<br/>
[ProjectEngagementCollection](ProjectEngagementCollection.md)<br/>
