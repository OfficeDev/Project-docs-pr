[comment]: # (Name:ProjectContext)
[comment]: # (Name:Microsoft.ProjectServer.PSContext)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>ProjectContext class

<a name="description"></a>Maintains the client-side context for development with a Project Web App instance, and contains the enterprise-wide collections of Project Server objects that exist in Project Web App.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class ProjectContext 
```
### JSOM

```javascript
PS.ProjectContext
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.ProjectContext

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Calendars"></a>Calendars|&#x2713;|&#x2713;|&#x2713;|[CalendarCollection](CalendarCollection.md)|Gets the collection of calendars for the Project Server instance.|
|<a name="CustomFields"></a>CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)|Gets the collection of enterprise custom field definitions in the Project Web App instance.|
|<a name="EngagementsTimephasedPageSize"></a>EngagementsTimephasedPageSize|&#x2713;|&#x2713;|&#x2713;|Integer||
|<a name="EnterpriseProjectTypes"></a>EnterpriseProjectTypes|&#x2713;|&#x2713;|&#x2713;|[EnterpriseProjectTypeCollection](EnterpriseProjectTypeCollection.md)|Gets the collection of enterprise project types (EPTs) in the Project Web App instance.|
|<a name="EnterpriseResources"></a>EnterpriseResources|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResourceCollection](EnterpriseResourceCollection.md)|Gets the collection of enterprise resources in a Project Web App instance.|
|<a name="EnterpriseResourcesPageSize"></a>EnterpriseResourcesPageSize|&#x2713;|&#x2713;|&#x2713;|Integer|The number of [EnterpriseResource](EnterpriseResource.md) that can be pulled down with child elements in a single request|
|<a name="EntityTypes"></a>EntityTypes|&#x2713;|&#x2713;|&#x2713;|[EntityTypes](EntityTypes.md)|Gets the types of Project Server entities that are exposed through the CSOM.|
|<a name="EventHandlers"></a>EventHandlers|&#x2713;|&#x2713;|&#x2713;|[EventHandlerCollection](EventHandlerCollection.md)|Gets the collection of event handlers that are defined in a Project Web App instance.|
|<a name="Events"></a>Events|&#x2713;|&#x2713;|&#x2713;|[EventCollection](EventCollection.md)|Gets the collection of event objects in a Project Web App instance.|
|<a name="IsDelegate"></a>IsDelegate|||&#x2713;|Boolean|Gets a value that indicates whether the current user has started a delegation session in PWA.  For CSOM/JSOM support see [ServiceStatus](ServiceStatus.md)|
|<a name="IsReadOnly"></a>IsReadOnly|||&#x2713;|Boolean|Gets a value that indicates whether the Project Server database is in read-only mode. For CSOM/JSOM support see [ServiceStatus](ServiceStatus.md)|
|<a name="LookupTables"></a>LookupTables|&#x2713;|&#x2713;|&#x2713;|[LookupTableCollection](LookupTableCollection.md)|Gets the collection of lookup table definitions in the Project Web App instance.|
|<a name="Phases"></a>Phases|&#x2713;|&#x2713;|&#x2713;|[PhaseCollection](PhaseCollection.md)|Gets the collection of Project Server workflow phases in the Project Web App instance.|
|<a name="ProjectDetailPages"></a>ProjectDetailPages|&#x2713;|&#x2713;|&#x2713;|[ProjectDetailPageCollection](ProjectDetailPageCollection.md)|Gets a collection of project detail pages in the Project Server instance.|
|<a name="Projects"></a>Projects|&#x2713;|&#x2713;|&#x2713;|[ProjectCollection](ProjectCollection.md)|Gets the collection of projects in the Project Web App instance.|
|<a name="ProjectsPageSize"></a>ProjectsPageSize|&#x2713;|&#x2713;|&#x2713;|Integer|The number of [PublishedProject](PublishedProject.md) objects that can be in a single request when also requesting child entities.|
|<a name="ServiceStatus"></a>ServiceStatus|&#x2713;|&#x2713;||[ServiceStatus](ServiceStatus.md)|Gets information about the status of the Project Server service.|
|<a name="Stages"></a>Stages|&#x2713;|&#x2713;|&#x2713;|[StageCollection](StageCollection.md)|Gets the collection of Project Server workflow stages in a Project Web App instance.|
|<a name="TimeSheetPeriods"></a>TimeSheetPeriods|&#x2713;|&#x2713;|&#x2713;|[TimeSheetPeriodCollection](TimeSheetPeriodCollection.md)|Gets a collection of time sheet periods.|
|<a name="WorkflowActivities"></a>WorkflowActivities|&#x2713;|&#x2713;|&#x2713;|[WorkflowActivities](WorkflowActivities.md)|Gets the methods that Project Server workflows can call at run time.|
|<a name="WorkflowDesigner"></a>WorkflowDesigner|&#x2713;|&#x2713;|&#x2713;|[WorkflowDesigner](WorkflowDesigner.md)|Gets a workflow designer that developers can call at design time.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetDeletedPublishedAssignments(DateTime deletedDate)](#GetDeletedPublishedAssignments_DateTime_deletedDate_)|&#x2713;|&#x2713;|&#x2713;|[DeletedPublishedAssignmentCollection](DeletedPublishedAssignmentCollection.md)||
|[StopDelegation()](#StopDelegation__)||&#x2713;|&#x2713;|void|	Gets a value that indicates whether the Project Server database is in read-only mode.  For CSOM/JSOM support see [ServiceStatus](ServiceStatus.md)|

<br/>
#### Method Details

#### <a name="GetDeletedPublishedAssignments_DateTime_deletedDate_"></a>GetDeletedPublishedAssignments(DateTime deletedDate)
 

##### Syntax

```
DeletedPublishedAssignmentCollection GetDeletedPublishedAssignments(DateTime deletedDate)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|deletedDate|DateTime|The earliest date to retrieve deleted published assignments from.|

##### Return Value

[DeletedPublishedAssignmentCollection](DeletedPublishedAssignmentCollection.md)

#### <a name="StopDelegation__"></a>StopDelegation()
 

##### Syntax

```
void StopDelegation()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[CalendarCollection](CalendarCollection.md)<br/>
[CustomFieldCollection](CustomFieldCollection.md)<br/>
[EnterpriseProjectTypeCollection](EnterpriseProjectTypeCollection.md)<br/>
[EnterpriseResourceCollection](EnterpriseResourceCollection.md)<br/>
[EntityTypes](EntityTypes.md)<br/>
[EventHandlerCollection](EventHandlerCollection.md)<br/>
[EventCollection](EventCollection.md)<br/>
[LookupTableCollection](LookupTableCollection.md)<br/>
[PhaseCollection](PhaseCollection.md)<br/>
[ProjectDetailPageCollection](ProjectDetailPageCollection.md)<br/>
[ProjectCollection](ProjectCollection.md)<br/>
[StageCollection](StageCollection.md)<br/>
[TimeSheetPeriodCollection](TimeSheetPeriodCollection.md)<br/>
[WorkflowActivities](WorkflowActivities.md)

