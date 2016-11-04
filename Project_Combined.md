# Project 
Contains inheritable properties and methods common to draft and published projects.

## Members

The members listed consist of the methods and properties defined for the Project object. 

Three different interfaces are available:

* CSOM - client-side library providing support for .NET applications
* JSOM - JavaScript object model library that provides support for AddIn development
* REST - HTTP command-based interface that provides language-agnostic functionality

The tables for methods and properties identify the name used in each library, the return or data type (if a value is exchanged), and a description of the individual method or property. 


### Methods

The  **Project** object has the following methods.

|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----|:-----|:-----|:-----|
|[EnterProjectStage](c7143697-4fc2-74fb-29fc-cd42732b51a1.md)|[enterProjectStage](d638c4ce-306f-0c3d-d916-b4017991759a.md)|[enterProjectStage ]()|n/a|Switches the project to the specified stage in a Project Server workflow.|
|[GetResourcePlan](0f5d5c37-4ac1-cae9-0f3e-50cab1143f76.md)|[getResourcePlan](22aff753-0076-59e7-33b0-8e0c3bacecac.md)|[getResourcePlan]()|[ResourcePlan](e2a04dbe-dbf7-78ca-6ea3-aebad7a37170.md)|Gets resource plan data for a project by filtering project data with date range and timescale parameters.|
|[LeaveProjectStage](717120ce-cd62-9cca-ae8d-5efbfdab8e0d.md)|[leaveProjectStage](899c243e-4174-8ed6-ebda-a063b993ddbe.md)|[leaveProjectStage ]()|n/a|Sets the project complete and leaves the current workflow stage.|
|[ReadyToLeaveProjectStage](6a6ccf05-107e-fbdb-a80e-f033e39da285.md)|[readyToLeaveProjectStage](ee41655d-3fe9-4be6-8305-3a2c170bf340.md)|[readyToLeaveProjectStage ]()|Collection of constants|Checks whether the current workflow stage requirements are met and the project is ready to move to the next stage.|
|[SetCustomFieldValue](50c84c98-109a-fafb-8818-ade8b85d7bbc.md)|[setCustomFieldValue](1cdac745-0653-cf6e-b21c-d26fafee79c6.md)|[setCustomFieldValue ]()|n/a|Sets a custom field on the project.|
|[UpdateIdeaListItemStatus](bf8a2304-d8d7-7c02-ff97-c61cfe077edd.md)|[updateIdeaListItemStatus](a5a787fd-d797-1708-deee-eaf17d81be92.md)|[updateIdeaListItemStatus ]()|n/a|Updates the Project Server Status column in the idea list with a status message.|
|[UpdateProjectStageStatus](0d00f09e-dcd4-21d2-a2c2-041bb91b4cde.md)|[updateProjectStageStatus](85d9a8eb-09d0-a340-179d-0b6ee1e709d7.md)|[updateProjectStageStatus ]()|n/a|Updates the status of a workflow stage for the project.|


### Properties

The  **Project** object has the following properties.

|**CSOM**|**JSOM (get_, set_)**|**REST**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|:-----|
|[ApprovedEnd](7487f3d8-c8bf-b4a1-66b4-dac2340bf051.md) #|[ApprovedEnd](811e4d0b-2369-f68a-5729-b6152db3a554.md) #|[ApprovedEnd](811e4d0b-2369-f68a-5729-b6152db3a554.md) #|DateTime|Gets the approved end date in the project portfolio planner.|
|[ApprovedStart](9ade7e8b-404f-b0ea-b0b2-b04622580b77.md) #|[ApprovedStart](4969a2da-3107-cab5-b8df-fddfb9d65578.md) #|[ApprovedStart](4969a2da-3107-cab5-b8df-fddfb9d65578.md) #|DateTime|Gets the approved start date in the project portfolio planner.|
|[CalculateActualCosts](8e4785dd-c3a9-8a07-84df-bd258d3e4ed5.md) *,#|[CalculateActualCosts](c8623e88-435b-ed3f-6ab7-ce6fb1a317af.md) *,#|[CalculateActualCosts](c8623e88-435b-ed3f-6ab7-ce6fb1a317af.md) *,#|Boolean|Gets a value that indicates whether the project automatically calculates actual and remaining work and costs. |
|[CalculatesActualCosts](e9d37dd7-7e55-f397-b418-fb0e3c5109e3.md) *,#|[CalculatesActualCosts](94da91ea-9b82-e628-1b6b-d83478e894c4.md) *,#|[CalculatesActualCosts](94da91ea-9b82-e628-1b6b-d83478e894c4.md) *,#|Boolean|Gets a value that indicates whether the project always calculates actual costs. |
|[CheckedOutBy](41a1d8aa-fe7b-119c-f8fe-2d9b2de43cb6.md) #|[CheckedOutBy](d0f89c29-51ae-122e-9606-a56050efa259.md) #|[CheckedOutBy](d0f89c29-51ae-122e-9606-a56050efa259.md) #|User|Gets the enterprise resource who has the project checked out.|
|[CheckedOutDate](f38c6a7e-9e51-74d2-5f7d-5222288a4470.md) #|[CheckedOutDate](7933c082-b11b-ff5b-d5de-b4c4c513d335.md) #|[CheckedOutDate](7933c082-b11b-ff5b-d5de-b4c4c513d335.md) #|DateTime|Gets the date when project was checked out.|
|[CheckOutDescription](0e188b22-664b-561b-21ee-0253adc25a03.md) #|[CheckOutDescription](83ddd70d-8f64-b5ef-933d-afd9e9931949.md) #|[CheckOutDescription](83ddd70d-8f64-b5ef-933d-afd9e9931949.md) #|String|Gets the description of the current checkout action for the project.|
|[CheckOutId](b9bb69b3-ce95-3a40-78bf-72e750084b29.md) #|[CheckOutId](a9abf00c-ecbd-6576-abc6-5565a49849e2.md) #|[CheckOutId](a9abf00c-ecbd-6576-abc6-5565a49849e2.md) #|Guid|Gets the session GUID that is associated with the current check out.|
|[CreatedDate](562c7bf3-d9e0-ce8c-92a2-bed3982079dd.md) #|[CreatedDate](c1f90a09-d83a-5a11-21ad-855c7d76cae2.md) #|[CreatedDate](c1f90a09-d83a-5a11-21ad-855c7d76cae2.md) #|DateTime|Gets the date when the project was created.|
|[CriticalSlackLimit](752e1504-6653-b6c2-604a-5f720b2378b8.md) *,#|[CriticalSlackLimit](306108bf-1cb7-6d28-4b7f-1e36a23ee6b5.md) *,#|[CriticalSlackLimit](306108bf-1cb7-6d28-4b7f-1e36a23ee6b5.md) *,#|Integer|Gets the number of days that a task can go past its end date before the project marks that task as critical. |
|[CustomFields](058d8e47-6825-4ceb-4eaa-b717f62dea0b.md) #|[CustomFields](6c6afddb-ac7a-2c97-cda3-e902fecb72b1.md) #|[CustomFields](6c6afddb-ac7a-2c97-cda3-e902fecb72b1.md) #|[CustomFieldCollection class](39c70b02-09d2-d60e-94d9-ea538846124a.md)|Gets the collection of project custom fields that have values set for the project.|
|[DefaultFinishTime](f744fe10-c47b-8c5f-1e32-787af95f94c5.md) *,#|[DefaultFinishTime](d05a9902-a281-0c8c-4d36-bc30128a06cf.md) *,#|[DefaultFinishTime](d05a9902-a281-0c8c-4d36-bc30128a06cf.md) *,#|DateTime|Gets the default end time of a working day. |
|[DefaultOvertimeRateUnits](0e7a696b-a647-468c-0c23-7ac392eec052.md) #|[DefaultOvertimeRateUnits](5fde23ca-c7a1-31c1-b2d5-26873b24e6e5.md) #|[DefaultOvertimeRateUnits](5fde23ca-c7a1-31c1-b2d5-26873b24e6e5.md) #|Integer (OvertimeRateFormat)|Gets the time unit for the default overtime rate that is stored by the DefaultOvertimeRate property.|
|[DefaultStandardRateUnits](055841b5-62f7-c675-e2fb-302e171705c3.md) #|[DefaultStandardRateUnits](f6c95f08-e914-ef79-74b3-4061d909b829.md) #|[DefaultStandardRateUnits](f6c95f08-e914-ef79-74b3-4061d909b829.md) #|Integer (StandardRateFormat)|Gets the time unit for the default standard rate that is stored by the DefaultStandardRate property.|
|[DefaultStartTime](20249210-2e34-35f7-aed2-fb7b61a010a4.md) *,#|[DefaultStartTime](16b65e6d-1db5-214c-6d4b-3335fd828c1e.md) *,#|[DefaultStartTime](16b65e6d-1db5-214c-6d4b-3335fd828c1e.md) *,#|DateTime|Gets the default start time of a working day. |
|[Engagements]() *,#|[Engagements]() *,#|[Engagements]() *,#|PS.ProjectEngagementCollection||
|[EnterpriseProjectType](a239bbfd-8a78-de67-7995-46747d5a8850.md) #|[EnterpriseProjectType](f39fed21-bebc-3bbe-e1b9-d99c7165de1e.md) #|[EnterpriseProjectType](f39fed21-bebc-3bbe-e1b9-d99c7165de1e.md) #|[EnterpriseProjectType](db9e7200-331b-5f48-8a46-33cd53f916fd.md)|Gets the enterprise project type (EPT) for the project.|
|[HasMppPendingImport](d42f5d06-621c-0dec-d40f-72684654e954.md) #|[HasMppPendingImport](964d4421-2819-bd04-a0da-c53c77a078df.md) #|[HasMppPendingImport](964d4421-2819-bd04-a0da-c53c77a078df.md) #|Boolean|Gets a value that indicates whether there is an mpp file waiting to be imported.|
|[HonorConstraints](2bac50d3-8bfc-2282-9fdb-f6f5fa455703.md) *,#|[HonorConstraints](12199489-8e19-77ae-fc44-073169740005.md) *,#|[HonorConstraints](12199489-8e19-77ae-fc44-073169740005.md) *,#|Boolean|Gets a value that indicates whether scheduling constraints take precedence over dependencies. |
|[Id](3ad4c300-54ac-8bf7-fb1a-823328b6cf39.md) #|[Id](ebefb7b8-af96-3d9f-9500-e93df5ae9d2f.md) #|[Id](ebefb7b8-af96-3d9f-9500-e93df5ae9d2f.md) #|Guid|Gets the GUID of the project.|
|[IsCheckedOut](5ddccc17-21e8-8e29-dbdf-9ae029ba0df4.md) #|[IsCheckedOut](a75c0953-6f9a-9f9d-e37e-e47a1284d555.md) #|[IsCheckedOut](a75c0953-6f9a-9f9d-e37e-e47a1284d555.md) #|Boolean|Gets a value that indicates whether the project is checked out.|
|[LastPublishedDate](a8a950a7-3a7a-0fae-6f3d-34e159b7be57.md) #|[LastPublishedDate](d809457b-4057-7246-40b9-31accdfbbdb0.md) #|[LastPublishedDate](d809457b-4057-7246-40b9-31accdfbbdb0.md) #|DateTime|Gets the most recent date when the project was published.|
|[LastSavedDate](8ed0932d-71dc-8ece-e257-b51004e62a0a.md) #|[LastSavedDate](1c924cdd-e9b7-ad1d-14d1-5f342566542d.md) #|[LastSavedDate](1c924cdd-e9b7-ad1d-14d1-5f342566542d.md) #|DateTime|Gets the most recent date when the project was saved.|
|[MoveActualIfLater](95d049e7-b39a-a46c-6236-e1946903df8b.md) *,#|[MoveActualIfLater](24bfd072-4b42-c0c0-24fd-f6b5444fbe48.md) *,#|[MoveActualIfLater](24bfd072-4b42-c0c0-24fd-f6b5444fbe48.md) *,#|Boolean|Gets a value that indicates whether to move the end date of completed parts forward to the status date, if the actual end date falls before the status date. |
|[MoveActualToStatus](44b00d66-213a-612b-a33f-738f9d69d0e9.md) *,#|[MoveActualToStatus](bc70e7eb-06ad-f612-627f-0feac795e54c.md) *,#|[MoveActualToStatus](bc70e7eb-06ad-f612-627f-0feac795e54c.md) *,#|Boolean|Gets a value that indicates whether to move the end date of completed parts back to the status date, if the actual end data falls after the status date. |
|[MoveRemainingIfEarlier](91f7a4c1-ede8-82c4-df6f-82a86fed3575.md) *,#|[MoveRemainingIfEarlier](1fabf6c5-1591-3915-93f7-b5a36233fc38.md) *,#|[MoveRemainingIfEarlier](1fabf6c5-1591-3915-93f7-b5a36233fc38.md) *,#|Boolean|Gets a value that indicates whether to move the start date of remaining parts forward to the status date, if the actual start date falls before the status date. |
|[MoveRemainingToStatus](40e9cf9d-0920-b6b9-0c45-ef48967c4a66.md) *,#|[MoveRemainingToStatus](2505a926-f19d-1af8-a0d7-0017548c3abb.md) *,#|[MoveRemainingToStatus](2505a926-f19d-1af8-a0d7-0017548c3abb.md) *,#|Boolean|Gets a value that indicates whether to move the start date of the remaining parts back to the status date, if the actual start date falls after the status date. |
|[MultipleCriticalPaths](2162a868-e34c-a44d-72e4-35986c72807c.md) *,#|[MultipleCriticalPaths](80be1b5c-9bac-b139-a53c-eeeb6e50e1df.md) *,#|[MultipleCriticalPaths](80be1b5c-9bac-b139-a53c-eeeb6e50e1df.md) *,#|Boolean|Gets a value that indicates whether to calculate multiple critical paths. |
|[OptimizerDecision](0ad91a8e-239e-5ee9-ae4c-2d05d2844697.md) #|[OptimizerDecision](6dc2ff9e-6051-555c-4656-ad5a4284bda6.md) #|[OptimizerDecision](6dc2ff9e-6051-555c-4656-ad5a4284bda6.md) #|Integer (CommittedDecisionResult)|Gets the result of the Optimizer in a project portfolio analysis.|
|[PercentComplete](d8b22f65-9046-9353-827f-8bff0191a624.md) #|[PercentComplete](8229a534-f2cf-b7c7-3dbc-e3aa731e3144.md) #|[PercentComplete](8229a534-f2cf-b7c7-3dbc-e3aa731e3144.md) #|Integer|Gets the percentage complete of the project summary task.|
|[Phase](2da4af29-2b10-8b1c-3728-4d5f10cdb79c.md) #|[Phase](3c3af690-0f13-1bbc-22b0-fa1ba49c6ba2.md) #|[Phase](3c3af690-0f13-1bbc-22b0-fa1ba49c6ba2.md) #|[Phase](c5336e3c-52c9-ca7e-ee4e-b280ae5269e0.md)|Gets the current workflow phase of the project.|
|[PlannerDecision](819ab389-db95-99fc-1ea2-5717a389bd50.md) #|[PlannerDecision](ad42eda1-d7bc-9c6d-ad91-0a174ddfb491.md) #|[PlannerDecision](ad42eda1-d7bc-9c6d-ad91-0a174ddfb491.md) #|Integer (CommittedDecisionResult)|Gets the result of the Planner in a project portfolio analysis.|
|[ProjectSiteUrl](43430af9-e5c6-60c6-960f-c19b04ebb784.md) #|[ProjectSiteUrl](5647c26c-f0a0-246e-46a2-8bf64e216b7d.md) #| #|String|Gets the URL of the project site.|
|[ProjectSummaryTask]() *,#|[ProjectSummaryTask]() *,#|[ProjectSummaryTask]() *,#|ProjectSummaryTask||
|[ProjectType](884f6ce7-feca-d56b-0572-a444e4a9c5ae.md) #|[ProjectType](406ab18b-24b4-18a4-c061-9b3eae4c0da4.md) #|[ProjectType](406ab18b-24b4-18a4-c061-9b3eae4c0da4.md) #|Integer (ProjectType)|Gets the type of project (standard project, template, master project, or subproject).|
|[QueueJobs](93dd46aa-db6b-f403-1601-e96c57418717.md) #|[QueueJobs](66ace9d6-ff3a-24c4-133a-41ce06e9dcef.md) #|[QueueJobs](66ace9d6-ff3a-24c4-133a-41ce06e9dcef.md) #|[QueueJobCollection](9cc098d6-abcd-fbcf-90f4-bed029084b42.md)|Gets the collection of Project Server Queue Service jobs that are associated with the project.|
|[ScheduledFromStart](e8e93431-0a66-8c23-03b1-10476f63c998.md) *,#|[ScheduledFromStart](bfa76815-73ea-7144-b415-30f8dadfe67c.md) *,#|[ScheduledFromStart](bfa76815-73ea-7144-b415-30f8dadfe67c.md) *,#|Boolean|Gets whether the project is scheduled from the finish date instead of the start date. |
|[SplitInProgress](d3f4a872-1ed0-6df2-e627-665721694ac1.md) *,#|[SplitInProgress](fa35ef31-1d8e-bf9c-473e-6bd1e3f9a3ed.md) *,#|[SplitInProgress](fa35ef31-1d8e-bf9c-473e-6bd1e3f9a3ed.md) *,#|Boolean|Gets a value that indicates whether to split tasks that are in progress. |
|[SpreadActualCostsToStatus](0bc64804-979a-6281-fc44-e33d08d32483.md) *,#|[SpreadActualCostsToStatus](875db967-4329-1717-e9a6-9b03bc3a89d8.md) *,#|[SpreadActualCostsToStatus](875db967-4329-1717-e9a6-9b03bc3a89d8.md) *,#|Boolean|Gets a value that indicates whether actual costs are spread to the status date or to the stop date. |
|[SpreadPercentCompleteToStatus](58f7bff0-5f4c-108a-dd50-36f052e942e2.md) *,#|[SpreadPercentCompleteToStatus](abc4f193-9af2-e0c4-ff2c-dc2c24aa9180.md) *,#|[SpreadPercentCompleteToStatus](abc4f193-9af2-e0c4-ff2c-dc2c24aa9180.md) *,#|Boolean|Gets a value that indicates whether the percentage complete consideration period is spread to the status date or to the task finish date. |
|[Stage](ad324297-e262-79c5-9e82-5c2563db9cfa.md) #|[Stage](ae6ea07c-be9f-4c82-d73c-1025e5669c96.md) #|[Stage](ae6ea07c-be9f-4c82-d73c-1025e5669c96.md) #|[Stage](8ef9f206-088b-6ea9-0991-2b7a69de78af.md)|Gets the current workflow stage of the project.|
|[SummaryTaskId](4a2fc4bb-91d5-a82b-c4b4-80c7540e3d0e.md) #|[SummaryTaskId](4465d13f-5a03-c1d7-0254-96b5ac779c89.md) #|[SummaryTaskId](4465d13f-5a03-c1d7-0254-96b5ac779c89.md) #|Guid|Gets the GUID for the hidden project summary task.|
|[TaskListId](928727ee-b8e3-09a1-9a91-20171f7edbf9.md) #|[TaskListId](94af85c6-af62-a84b-c44f-f0f6ddb6e8e2.md) #|[TaskListId](94af85c6-af62-a84b-c44f-f0f6ddb6e8e2.md) #|Guid|Gets the GUID of the project's task list.|



  **Note on Symbol Usage:**  
  (*blank*) - indicates the property has Read and Write access, and was available in the previous release.<br />
  * - indicates a new method or property.<br />
  # - indicates Read-Only access to a property.<br />
  $ - indicated Write-Only access to a property.


## Syntax

### CSOM Library

The CSOM .NET library used for client-side applications. The class declaration for Project follows.

```C#
Public Class Project _
	Inherits ClientObject
```

#### Inheritance hierarchy


[System.Object](http://msdn2.microsoft.com/EN-US/library/e5kfa45b)[Microsoft.SharePoint.Client.ClientObject](http://msdn2.microsoft.com/EN-US/library/ee540788)<br />
==>Microsoft.ProjectServer.Client.Project <br />
==>[Microsoft.ProjectServer.Client.DraftProject](c915d48d-c1bc-e454-fc2c-81b7a1a48578.md)<br />
==>[Microsoft.ProjectServer.Client.PublishedProject](c8ca8c11-6cbe-7b0f-b9a5-b77060012327.md)

**Namespace:**[Microsoft.ProjectServer.Client](e79057b8-4161-453c-1035-02e38725305c.md) 

**Assembly:**Microsoft.ProjectServer.Client (in Microsoft.ProjectServer.Client.dll)


### JSOM Library

The JSOM library is used for AddIns and is written in JavaScript. The declaration for the Project object follows:
```
PS.Project
```

### REST Interface

The <a name="restresourceendpoint"> </a>

#### Endpoint URI structure
<a name="endpointuristructure"> </a>


```
http://<sitecollection> /<site> /_api/ProjectServer/Projects('projectid')
```


#### HTTP requests
<a name="httprequests"> </a>

This resource supports the following HTTP commands:


- [GET](a2431b86-5e45-b4f5-dfb7-77145e3ac930.md#getsyntax)
    
- [DELETE](a2431b86-5e45-b4f5-dfb7-77145e3ac930.md#deletesyntax)
    

#### GET syntax
<a name="getsyntax"> </a>


```
GET http://<sitecollection> /<site> /_api/ProjectServer/Projects('projectid')
```


#### DELETE syntax
<a name="deletesyntax"> </a>


```
DELETE http://<sitecollection> /<site> /_api/ProjectServer/Projects('projectid')
```


## Remarks

The **DraftProject** class and the **PublishedProject** class are derived from the **Project** class. All of the properties in the **Project** class are read-only. To set the value of properties in an existing project, use the **[PublishedProject.CheckOut](981b89c7-40de-83ad-edff-c6877f6fdfaf.md)** method, edit the **DraftProject** object, and then use the **[DraftProject.CheckIn](18cd1db1-6bb3-0943-521b-c49f09225fb2.md)** method.


## Thread safety

Any public  **static** ( **Shared** in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See also

#### Reference


[Project members](8f325eaf-41ed-740b-0f97-76fc5fffbe1e.md)
[Microsoft.ProjectServer.Client namespace](e79057b8-4161-453c-1035-02e38725305c.md)
[DraftProject](c915d48d-c1bc-e454-fc2c-81b7a1a48578.md)
[PublishedProject](c8ca8c11-6cbe-7b0f-b9a5-b77060012327.md)
[ProjectCollection](a1477401-1aea-35c2-a162-ca6aff45cd1a.md)
[Projects](cf3b8367-99a8-24f9-f15b-b5cca214ed9c.md)
[Projects](d9994f46-a1b8-c610-70f0-01f69183d327.md)

