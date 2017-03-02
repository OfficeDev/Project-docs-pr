[comment]: # (Name:QueueMsgType)
[comment]: # (Name:Microsoft.Office.Project.Server.Library.QueueConstants+QueueMsgType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>QueueMsgType enumeration

<a name="description"></a>Specifies the queue message type, for sending a job to the Project Server Queue System.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum QueueMsgType 
```
### JSOM

```javascript
PS.QueueMsgType
```
### REST Interface

QueueMsgType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="Unknown"></a>Unknown|0|Unknown queue message type.|
|<a name="ACProjectSave"></a>ACProjectSave|1|Save jobs in the queue.|
|<a name="AdSyncERP"></a>AdSyncERP|2|Do an Active Directory Domain Services synchronization for enterprise resource planning.|
|<a name="AdSyncGroup"></a>AdSyncGroup|3|Do an Active Directory Domain Services synchronization.|
|<a name="ArchiveCategories"></a>ArchiveCategories|4|Archive the security categories.|
|<a name="ArchiveCustomFields"></a>ArchiveCustomFields|5|Archive the custom fields.|
|<a name="ArchiveGlobalProject"></a>ArchiveGlobalProject|6|Archive the enterprise global data.|
|<a name="ArchiveResources"></a>ArchiveResources|7|Archive the enterprise resources.|
|<a name="ArchiveSystemSettings"></a>ArchiveSystemSettings|8|Archive the system settings.|
|<a name="ArchiveViews"></a>ArchiveViews|9|Archive the views.|
|<a name="BumpPriority"></a>BumpPriority|10|Increase the job priority.|
|<a name="CBSProjRendezvous"></a>CBSProjRendezvous|11|Make a Cube Build Service project congregation.|
|<a name="CBSRequest"></a>CBSRequest|12|Make the Cube Build Service request.|
|<a name="CBSTsRendezvous"></a>CBSTsRendezvous|13|Create the Cube Build Service timesheet congregation.|
|<a name="CreateProposalProject"></a>CreateProposalProject|14|Obsolete. Not used in Project Server 2010 or Project Server 2013. Create the project proposal.|
|<a name="CreateWssSite"></a>CreateWssSite|15|Create the SharePoint site.|
|<a name="DeleteWssSite"></a>DeleteWssSite|16|Delete the SharePoint site.|
|<a name="LWPUpgradeToProject"></a>LWPUpgradeToProject|17|Obsolete. Not used in Project Server 2010 or Project Server 2013. Upgrade the SharePoint project to a Project Server project.|
|<a name="NotificationMessage"></a>NotificationMessage|18|Send the notification message.|
|<a name="ProjectArchive"></a>ProjectArchive|19|Archive the project.|
|<a name="ProjectArchiveRetentionDelete"></a>ProjectArchiveRetentionDelete|20|Set the project archive retention policy to delete.|
|<a name="ProjectCheckIn"></a>ProjectCheckIn|21|Check in the project.|
|<a name="ProjectCreate"></a>ProjectCreate|22|Create the project.|
|<a name="ProjectDelete"></a>ProjectDelete|23|Delete the project.|
|<a name="ProjectPublish"></a>ProjectPublish|24|Publish the project.|
|<a name="ProjectRename"></a>ProjectRename|25|Rename the project.|
|<a name="ProjectRestore"></a>ProjectRestore|26|Restore the project from the Archive database.|
|<a name="ProjectReversePublish"></a>ProjectReversePublish|27|Undo the project publication.|
|<a name="ProjectUpdate"></a>ProjectUpdate|28|Update the project.|
|<a name="ProjectUpdateTeam"></a>ProjectUpdateTeam|29|Update the project team.|
|<a name="PublishNotifications"></a>PublishNotifications|30|Publish the notifications.|
|<a name="QueueCleanup"></a>QueueCleanup|31|Clean the queue.|
|<a name="ReportingAttributeCubeSettingsSync"></a>ReportingAttributeCubeSettingsSync|32|Synchronize the cube settings with the Reporting database.|
|<a name="ReportingBaseCalendarSync"></a>ReportingBaseCalendarSync|33|Synchronize the base calendar with the Reporting database.|
|<a name="ReportingCustomFieldMetadataSync"></a>ReportingCustomFieldMetadataSync|34|Synchronize the custom field metadata with the Reporting database.|
|<a name="ReportingEntityUserViewRefresh"></a>ReportingEntityUserViewRefresh|35|Refresh the user view entity with the Reporting database.|
|<a name="ReportingFiscalPeriodsSync"></a>ReportingFiscalPeriodsSync|36|Synchronize the fiscal periods with the Reporting database.|
|<a name="ReportingLookupTableSync"></a>ReportingLookupTableSync|37|Synchronize the lookup table with the Reporting database.|
|<a name="ReportingProjectDelete"></a>ReportingProjectDelete|38|Delete the project in the Reporting database.|
|<a name="ReportingProjectPublish"></a>ReportingProjectPublish|39|Mark the project as published in the Reporting database.|
|<a name="ReportingResourcesCapacityRangeSync"></a>ReportingResourcesCapacityRangeSync|40|Synchronize the resource capacity range with the Reporting database.|
|<a name="ReportingResourceSync"></a>ReportingResourceSync|41|Synchronize the resource data with the Reporting database.|
|<a name="ReportingTimesheetAdjust"></a>ReportingTimesheetAdjust|42|Adjust the timesheet data in the Reporting database.|
|<a name="ReportingTimesheetClassSync"></a>ReportingTimesheetClassSync|43|Synchronize the timesheet class with the Reporting database.|
|<a name="ReportingTimesheetDelete"></a>ReportingTimesheetDelete|44|Delete the timesheet in the Reporting database.|
|<a name="ReportingTimesheetPeriodDelete"></a>ReportingTimesheetPeriodDelete|45|Delete the timesheet period in the Reporting database.|
|<a name="ReportingTimesheetPeriodSync"></a>ReportingTimesheetPeriodSync|46|Synchronize the timesheet period with the Reporting database.|
|<a name="ReportingTimesheetSave"></a>ReportingTimesheetSave|47|Save the timesheet in the Reporting database.|
|<a name="ReportingTimesheetStatusSync"></a>ReportingTimesheetStatusSync|48|Synchronize the timesheet status with the Reporting database.|
|<a name="ReportingWSSSync"></a>ReportingWSSSync|49|Synchronize the SharePoint data with the Reporting database.|
|<a name="ResourcePlanCheckIn"></a>ResourcePlanCheckIn|50|Check in the resource plan.|
|<a name="ResourcePlanDelete"></a>ResourcePlanDelete|51|Delete the resource plan.|
|<a name="ResourcePlanPublish"></a>ResourcePlanPublish|52|Publish the resource plan.|
|<a name="ResourcePlanSave"></a>ResourcePlanSave|53|Save the resource plan.|
|<a name="RestoreCategories"></a>RestoreCategories|54|Restore the security categories.|
|<a name="RestoreCustomFields"></a>RestoreCustomFields|55|Restore the custom fields.|
|<a name="RestoreGlobalProject"></a>RestoreGlobalProject|56|Restore the enterprise global project data.|
|<a name="RestoreResources"></a>RestoreResources|57|Restore the resources.|
|<a name="RestoreSystemSettings"></a>RestoreSystemSettings|58|Restore the system settings.|
|<a name="RestoreViews"></a>RestoreViews|59|Restore the views.|
|<a name="RulesProcessAll"></a>RulesProcessAll|60|Process all rules.|
|<a name="RulesProcessAllAutoForManager"></a>RulesProcessAllAutoForManager|61|Automatically process all rules for the manager.|
|<a name="RulesProcessAllForManager"></a>RulesProcessAllForManager|62|Process all rules for the manager.|
|<a name="RulesProcessSingleForManager"></a>RulesProcessSingleForManager|63|Process the single rule for the manager.|
|<a name="StatusApproval"></a>StatusApproval|64|Approve the status.|
|<a name="Timer1"></a>Timer1|65|Internal use only.|
|<a name="Timer10"></a>Timer10|66|Internal use only.|
|<a name="Timer2"></a>Timer2|67|Internal use only.|
|<a name="Timer3"></a>Timer3|68|Internal use only.|
|<a name="Timer4"></a>Timer4|69|Internal use only.|
|<a name="Timer5"></a>Timer5|70|Internal use only.|
|<a name="Timer6"></a>Timer6|71|Internal use only.|
|<a name="Timer7"></a>Timer7|72|Internal use only.|
|<a name="Timer8"></a>Timer8|73|Internal use only.|
|<a name="Timer9"></a>Timer9|74|Internal use only.|
|<a name="TimerMessage"></a>TimerMessage|75|Internal use only. Send a timer message.|
|<a name="TimerRzNotify"></a>TimerRzNotify|76|Internal use only.|
|<a name="TimerRzProj"></a>TimerRzProj|77|Internal use only.|
|<a name="TimerRzTS"></a>TimerRzTS|78|Internal use only.|
|<a name="TimesheetMessage"></a>TimesheetMessage|79|Send the timesheet message.|
|<a name="TimesheetDelete"></a>TimesheetDelete|80|Delete the timesheet.|
|<a name="TimesheetRecall"></a>TimesheetRecall|81|Recall the timesheet.|
|<a name="TimesheetReview"></a>TimesheetReview|82|Review the timesheet.|
|<a name="TimesheetSubmit"></a>TimesheetSubmit|83|Submit the timesheet.|
|<a name="TimesheetUpdate"></a>TimesheetUpdate|84|Update the timesheet.|
|<a name="ReportingSyncGlobalData"></a>ReportingSyncGlobalData|85|Synchronize the enterprise global data with the Reporting database.|
|<a name="SynchronizeMembershipForWssSite"></a>SynchronizeMembershipForWssSite|86|Obsolete. Not used for development with Project Server. Synchronize membership for the SharePoint site.|
|<a name="SynchronizeSingleUserMembershipInWss"></a>SynchronizeSingleUserMembershipInWss|87|Obsolete. Not used for development with Project Server. Synchronize membership for the SharePoint site.|
|<a name="ReportingRefresh"></a>ReportingRefresh|88|Refresh the Reporting database.|
|<a name="UpdateScheduledProject"></a>UpdateScheduledProject|89|Obsolete. Not used in Project Server 2013. Update the scheduled project.|
|<a name="WorkflowStartWorkflow"></a>WorkflowStartWorkflow|90|Start the workflow.|
|<a name="AnalysisDelete"></a>AnalysisDelete|91|Delete the project portfolio analysis.|
|<a name="AnalysisCreate"></a>AnalysisCreate|92|Create the project portfolio analysis.|
|<a name="AnalysisUpdate"></a>AnalysisUpdate|93|Update the project portfolio analysis.|
|<a name="PlannerSolutionCreate"></a>PlannerSolutionCreate|94|Create the Planner solution.|
|<a name="PlannerSolutionDelete"></a>PlannerSolutionDelete|95|Delete the Planner solution.|
|<a name="OptimizerSolutionCreate"></a>OptimizerSolutionCreate|96|Create the Optimizer solution.|
|<a name="OptimizerSolutionDelete"></a>OptimizerSolutionDelete|97|Delete the Optimizer solution.|
|<a name="TimesheetLineApproval"></a>TimesheetLineApproval|98|Approve the timesheet line.|
|<a name="PeriodicTasks"></a>PeriodicTasks|99|Set the periodic tasks.|
|<a name="PDPUpdateProjectImpacts"></a>PDPUpdateProjectImpacts|100|Update the project impacts in a project detail page.|
|<a name="ExchangeSyncTasks"></a>ExchangeSyncTasks|101|Synchronize tasks with Microsoft Exchange.|
|<a name="ReportingAttributeCubeDepartmentSync"></a>ReportingAttributeCubeDepartmentSync|102|Synchronize the cube department with the Reporting database.|
|<a name="ReportingTimesheetProjectAggregation"></a>ReportingTimesheetProjectAggregation|103|Aggregate the timesheet project in the Reporting database.|
|<a name="ReportingTimesheetAssignmentsUpgrade"></a>ReportingTimesheetAssignmentsUpgrade|104|Upgrade the timesheet assignments in the Reporting database.|
|<a name="WorkflowCheckinNotify"></a>WorkflowCheckinNotify|105|Send a notification about the workflow check in.|
|<a name="WorkflowChangeWorkflow"></a>WorkflowChangeWorkflow|106|Change the workflow.|
|<a name="ProjectPublishSummary"></a>ProjectPublishSummary|107|Publish the project summary.|
|<a name="ReportingOlapDatabaseSettingsSync"></a>ReportingOlapDatabaseSettingsSync|108|Synchronize the OLAP database settings for reporting.|
|<a name="ReportingWorkflowMetadataSync"></a>ReportingWorkflowMetadataSync|109|Synchronize the workflow metadata with the Reporting database.|
|<a name="ReportWorkflowProjectDataSync"></a>ReportWorkflowProjectDataSync|110|Synchronize the workflow project data with the Reporting database.|
|<a name="ReportEptSync"></a>ReportEptSync|111|Synchronize the enterprise project template with the Reporting database.|
|<a name="ReportingSummaryPublish"></a>ReportingSummaryPublish|112|Synchronize the published project summary with the Reporting database.|
|<a name="ReportingSolutionCommitedDecisionSync"></a>ReportingSolutionCommitedDecisionSync|113|Synchronize the solution committed decision with the Reporting database.|
|<a name="WorkflowCommitNotify"></a>WorkflowCommitNotify|114|Send a notification about the workflow commit action.|
|<a name="ReportingTimesheetAssignmentsRefresh"></a>ReportingTimesheetAssignmentsRefresh|115|Refresh the timesheet assignments in the Reporting database.|
|<a name="UpdateProjectSitePath"></a>UpdateProjectSitePath|116|Update the project site path.|
|<a name="AddSingleUserMembershipInWss"></a>AddSingleUserMembershipInWss|117|Obsolete. Not used for development with Project Server. Add the single user membership in SharePoint Server.|
|<a name="DeleteSingleUserMembershipInWss"></a>DeleteSingleUserMembershipInWss|118|Obsolete. Not used for development with Project Server. Delete the single user membership in SharePoint.|
|<a name="TimeSheetUpdateResourceNonWorkingTime"></a>TimeSheetUpdateResourceNonWorkingTime|119|Update resource nonworking time in the timesheet.|
|<a name="SyncProjectEnterpriseEntities"></a>SyncProjectEnterpriseEntities|120|Obsolete. Not used in Project Server 2013. Synchronize the enterprise entities in the project.|
|<a name="LastMessage"></a>LastMessage|121|End of the queue messages. Internal use only.|
|<a name="ExchangeCalOofSync"></a>ExchangeCalOofSync|122|Synchronize the resource calendar with out-of-office periods in Microsoft Exchange.|
|<a name="PreparePSPermissionSynchronization"></a>PreparePSPermissionSynchronization|123|Prepare to synchronize the global Project Server permission.|
|<a name="PSPermissionSynchronizePWASite"></a>PSPermissionSynchronizePWASite|124|Synchronize the Project Web App site with the Project Server permission.|
|<a name="PSPermissionSynchronizeProjectSite"></a>PSPermissionSynchronizeProjectSite|125|Synchronize the Project Server permission with the project site.|
|<a name="PreparePSProjectPermissionSynchronization"></a>PreparePSProjectPermissionSynchronization|126|Prepare to synchronize the project-level permission.|
|<a name="ScheduleWebPartSave"></a>ScheduleWebPartSave|127|Schedule web part save.|
|<a name="ProjectImportTaskList"></a>ProjectImportTaskList|128|Protect import task list.|
|<a name="TimesheetUpdateSRAForResource"></a>TimesheetUpdateSRAForResource|129|ActiveMonitorCheck|
|<a name="ActiveMonitorCheck"></a>ActiveMonitorCheck|130|Internal use only.|
|<a name="ManagedModeTaskSynchronization"></a>ManagedModeTaskSynchronization|131||
|<a name="ResourcePlanMigrate"></a>ResourcePlanMigrate|132|Migrating Resource Plans to Resource Engagements.|
|<a name="ReportingWSSIssueSync"></a>ReportingWSSIssueSync|133|Synchronize the SharePoint Issue data with the Reporting endpoint.|
|<a name="ReportingWSSRiskSync"></a>ReportingWSSRiskSync|134|Synchronize the SharePoint Risk data with the Reporting endpoint.|
|<a name="ReportingWSSDocSync"></a>ReportingWSSDocSync|135|Synchronize the SharePoint linked Docs data with the Reporting endpoint.|

## <a name="seeAlso"></a>See Also

[QueueJob](QueueJob.md)<br/>
