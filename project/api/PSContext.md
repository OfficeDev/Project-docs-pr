[comment]: # (Name:PSContext)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# PSContext





## Syntax

### CSOM

```C#
Class PSContext 
```
### JSOM

```
PS.PSContext
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Calendars|&#x2713;|&#x2713;|&#x2713;|[CalendarCollection](CalendarCollection.md)||
|CustomFields|&#x2713;|&#x2713;|&#x2713;|[CustomFieldCollection](CustomFieldCollection.md)||
|EngagementsTimephasedPageSize|&#x2713;|&#x2713;|&#x2713;|Integer||
|EnterpriseProjectTypes|&#x2713;|&#x2713;|&#x2713;|[EnterpriseProjectTypeCollection](EnterpriseProjectTypeCollection.md)||
|EnterpriseResources|&#x2713;|&#x2713;|&#x2713;|[EnterpriseResourceCollection](EnterpriseResourceCollection.md)||
|EnterpriseResourcesPageSize|&#x2713;|&#x2713;|&#x2713;|Integer||
|EntityTypes|&#x2713;|&#x2713;|&#x2713;|[EntityTypes](EntityTypes.md)||
|EventHandlers|&#x2713;|&#x2713;|&#x2713;|[EventHandlerCollection](EventHandlerCollection.md)||
|Events|&#x2713;|&#x2713;|&#x2713;|[EventCollection](EventCollection.md)||
|IsDelegate|&#x2713;|&#x2713;|&#x2713;|Boolean||
|IsReadOnly|&#x2713;|&#x2713;|&#x2713;|Boolean||
|LookupTables|&#x2713;|&#x2713;|&#x2713;|[LookupTableCollection](LookupTableCollection.md)||
|Phases|&#x2713;|&#x2713;|&#x2713;|[PhaseCollection](PhaseCollection.md)||
|ProjectDetailPages|&#x2713;|&#x2713;|&#x2713;|[ProjectDetailPageCollection](ProjectDetailPageCollection.md)||
|Projects|&#x2713;|&#x2713;|&#x2713;|[ProjectCollection](ProjectCollection.md)||
|ProjectsPageSize|&#x2713;|&#x2713;|&#x2713;|Integer||
|Stages|&#x2713;|&#x2713;|&#x2713;|[StageCollection](StageCollection.md)||
|TimeSheetPeriods|&#x2713;|&#x2713;|&#x2713;|[TimeSheetPeriodCollection](TimeSheetPeriodCollection.md)||
|UserPermissions|||&#x2713;|[UserPermissionCollection](UserPermissionCollection.md)||
|WorkflowActivities|&#x2713;|&#x2713;|&#x2713;|[WorkflowActivities](WorkflowActivities.md)||
|WorkflowDesigner|&#x2713;|&#x2713;|&#x2713;|[WorkflowDesigner](WorkflowDesigner.md)||





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetDeletedPublishedAssignments(DateTime deletedDate)](#GetDeletedPublishedAssignments_DateTime_deletedDate_)|&#x2713;|&#x2713;|&#x2713;|[DeletedPublishedAssignmentCollection](DeletedPublishedAssignmentCollection.md)||
|[StopDelegation()](#StopDelegation__)|&#x2713;|&#x2713;|&#x2713;|void||



## Method Details


### <a id="GetDeletedPublishedAssignments_DateTime_deletedDate_"></a>GetDeletedPublishedAssignments(DateTime deletedDate)
 


#### Syntax

```
DeletedPublishedAssignmentCollection GetDeletedPublishedAssignments(DateTime deletedDate)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|deletedDate| DateTime | 


#### Return Value

[DeletedPublishedAssignmentCollection](DeletedPublishedAssignmentCollection.md)

### <a id="StopDelegation__"></a>StopDelegation()
 


#### Syntax

```
void StopDelegation()
```

#### Parameters

None

#### Return Value

void


## See Also
