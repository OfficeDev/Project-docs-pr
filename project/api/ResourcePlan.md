[comment]: # (Name:ResourcePlan)
[comment]: # (Name:Microsoft.ProjectServer.ResourcePlan)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ResourcePlan class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a high-level look at what resources might be needed for a project.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ResourcePlan 
```
### JSOM

```javascript
PS.ResourcePlan
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.ResourcePlan

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Assignments"></a>Assignments|&#x2713;|&#x2713;|&#x2713;|[PlanAssignmentCollection](PlanAssignmentCollection.md)|Gets a collection of PlanAssignment objects that are associated with the resource plan.|
|<a name="Finish"></a>Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the end date of the resource plan.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the resource plan.|
|<a name="Start"></a>Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the start date of the resource plan.|
|<a name="UtilizationDate"></a>UtilizationDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time of resource utilization for the current resource plan.|
|<a name="UtilizationType"></a>UtilizationType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[ProjectUtilizationType](ProjectUtilizationType.md)|Gets or sets the type of resource utilization for the current resource plan.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Deletes the resource plan object.|
|[ForceCheckIn()](#ForceCheckIn__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Checks in the project resource plan in case it was left checked out in Project Server.|
|[Publish()](#Publish__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Publishes the project resource plan and makes it visible to other users in Project Server.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Saves changes from the project resource plan back to Project Server.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the resource plan object.

##### Syntax

```
QueueJob DeleteObject()
```

##### Parameters

None

##### Return Value

[QueueJob](QueueJob.md)

#### <a name="ForceCheckIn__"></a>ForceCheckIn()
 
Checks in the project resource plan in case it was left checked out in Project Server.

##### Syntax

```
QueueJob ForceCheckIn()
```

##### Parameters

None

##### Return Value

[QueueJob](QueueJob.md)

#### <a name="Publish__"></a>Publish()
 
Publishes the project resource plan and makes it visible to other users in Project Server.

##### Syntax

```
QueueJob Publish()
```

##### Parameters

None

##### Return Value

[QueueJob](QueueJob.md)

#### <a name="Update__"></a>Update()
 
Saves changes from the project resource plan back to Project Server.

##### Syntax

```
QueueJob Update()
```

##### Parameters

None

##### Return Value

[QueueJob](QueueJob.md)

## <a name="seeAlso"></a>See Also

[Project](Project.md)<br/>
