# PublishedProject 
Represents a project that is published on Project Server.


## Members

The members listed consist of the methods and properties defined for the PublishedProject object and those inherited from the Project object. 

Three different interfaces are available:

* CSOM - client-side library providing support for .NET applications
* JSOM - JavaScript object model library that provides support for AddIn development
* REST - HTTP command-based interface that provides language-agnostic functionality

The tables for methods and properties identify the name used in each library, the return or data type (if a value is exchanged), and a description of the individual method or property. 

### Methods

The  **PublishedProject** object has the following methods.

|**CSOM**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----|:-----|:-----|:-----|
|[CheckOut](981b89c7-40de-83ad-edff-c6877f6fdfaf.md)|[checkOut ](c5d6bf37-ee4e-c9da-b25f-b0f9d9b7bacf.md)|[checkOut ](c5d6bf37-ee4e-c9da-b25f-b0f9d9b7bacf.md)|[DraftProject]()|Checks out the draft version of the project.|
|[DeleteObject](e7886ddb-6da9-0eae-3352-c5ae478f13b0.md)|[deleteObject ](ac7995f9-82b2-9b4f-e9b8-083ad61c1849.md)|[deleteObject ](ac7995f9-82b2-9b4f-e9b8-083ad61c1849.md)|[QueueJob](4b3cc79b-0451-f03b-2ebd-57c6367b1fed.md)|Deletes the PublishedProject object.|
|[EnterProjectStage](c7143697-4fc2-74fb-29fc-cd42732b51a1.md)|[enterProjectStage ](d638c4ce-306f-0c3d-d916-b4017991759a.md)|[enterProjectStage ](d638c4ce-306f-0c3d-d916-b4017991759a.md)|n/a|Switches the project to the specified stage in a Project Server workflow. (Inherited from Project.)|
|[GetResourcePlan](0f5d5c37-4ac1-cae9-0f3e-50cab1143f76.md)|[getResourcePlan ](22aff753-0076-59e7-33b0-8e0c3bacecac.md)|[getResourcePlanByUrl](22aff753-0076-59e7-33b0-8e0c3bacecac.md)|[ResourcePlan](e2a04dbe-dbf7-78ca-6ea3-aebad7a37170.md)|Gets resource plan data for a project by filtering project data with date range and timescale parameters. (Inherited from Project.)|
|[LeaveProjectStage](717120ce-cd62-9cca-ae8d-5efbfdab8e0d.md)|[leaveProjectStage ](899c243e-4174-8ed6-ebda-a063b993ddbe.md)|[leaveProjectStage ](899c243e-4174-8ed6-ebda-a063b993ddbe.md)|n/a|Sets the project complete and leaves the current workflow stage. (Inherited from Project.)|
|[ReadyToLeaveProjectStage](6a6ccf05-107e-fbdb-a80e-f033e39da285.md)|[readyToLeaveProjectStage ](ee41655d-3fe9-4be6-8305-3a2c170bf340.md)|[readyToLeaveProjectStage ](ee41655d-3fe9-4be6-8305-3a2c170bf340.md)|Collection of constants|Checks whether the current workflow stage requirements are met and the project is ready to move to the next stage. (Inherited from Project.)|
|[SetCustomFieldValue](50c84c98-109a-fafb-8818-ade8b85d7bbc.md)|[setCustomFieldValue ](1cdac745-0653-cf6e-b21c-d26fafee79c6.md)|[setCustomFieldValue ](1cdac745-0653-cf6e-b21c-d26fafee79c6.md) *|n/a|Sets a custom field on the project. (Inherited from Project.)|
|[SubmitToWorkflow](513311aa-64c0-64a0-71fd-1a56832492b9.md)|[submitToWorkflow ](a6db173c-9694-cbf8-a7e8-38b6231d84e8.md)|[submitToWorkflow ](a6db173c-9694-cbf8-a7e8-38b6231d84e8.md)|n/a|Causes the workflow to run.|
|[UpdateIdeaListItemStatus](bf8a2304-d8d7-7c02-ff97-c61cfe077edd.md)|[updateIdeaListItemStatus ](a5a787fd-d797-1708-deee-eaf17d81be92.md)|[updateIdeaListItemStatus ](a5a787fd-d797-1708-deee-eaf17d81be92.md)|n/a|Updates the Project Server Status column in the idea list with a status message. (Inherited from Project.)|
|[UpdateProjectStageStatus](0d00f09e-dcd4-21d2-a2c2-041bb91b4cde.md)|[updateProjectStageStatus ](85d9a8eb-09d0-a340-179d-0b6ee1e709d7.md)|[updateProjectStageStatus ](85d9a8eb-09d0-a340-179d-0b6ee1e709d7.md)|n/a|Updates the status of a workflow stage for the project. (Inherited from Project.)|
|[UpdateVisibilityCustomFields](93ac5458-a524-3ec1-6455-7b6eb74b6ded.md)|[updateVisibilityCustomFields ](babd0047-bc6d-1708-5ef2-be725295f75d.md)|[updateVisibilityCustomFields ](babd0047-bc6d-1708-5ef2-be725295f75d.md)|[QueueJob](4b3cc79b-0451-f03b-2ebd-57c6367b1fed.md)|Updates the custom fields for a project in visibility mode.|



### Properties

The  **PublishedProject** object has the following properties.

|**CSOM**|**JSOM (get_, set_)**|**REST**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|:-----|
|[ApprovedEnd](7487f3d8-c8bf-b4a1-66b4-dac2340bf051.md) #|[ApprovedEnd](811e4d0b-2369-f68a-5729-b6152db3a554.md) #|[ApprovedEnd](811e4d0b-2369-f68a-5729-b6152db3a554.md) #|DateTime|Gets the approved end date in the project portfolio planner. (Inherited from Project.)|
|[ApprovedStart](9ade7e8b-404f-b0ea-b0b2-b04622580b77.md) #|[ApprovedStart](4969a2da-3107-cab5-b8df-fddfb9d65578.md) #|[ApprovedStart](4969a2da-3107-cab5-b8df-fddfb9d65578.md) #|DateTime|Gets the approved start date in the project portfolio planner. (Inherited from Project.)|
|[Assignments](9ca9a814-47e2-8fcf-0368-71b8f5b8617f.md) #|[Assignments](929608b9-aab5-75c9-9fa1-321ec64f17e4.md) #|[Assignments](929608b9-aab5-75c9-9fa1-321ec64f17e4.md) #|[PublishedAssignmentCollection](e08e5c0b-4eb9-b668-2866-74c7429b47f3.md)|Gets the collection of assignments in the project.|
|[CalculateActualCosts](8e4785dd-c3a9-8a07-84df-bd258d3e4ed5.md) #|[CalculateActualCosts](c8623e88-435b-ed3f-6ab7-ce6fb1a317af.md) #|[CalculateActualCosts](c8623e88-435b-ed3f-6ab7-ce6fb1a317af.md) #|Boolean|Gets a value that indicates whether the project automatically calculates actual and remaining work and costs. |
|[CalculatesActualCosts](e9d37dd7-7e55-f397-b418-fb0e3c5109e3.md) #|[CalculatesActualCosts](94da91ea-9b82-e628-1b6b-d83478e894c4.md) #|[CalculatesActualCosts](94da91ea-9b82-e628-1b6b-d83478e894c4.md) #|Boolean|Gets a value that indicates whether the project always calculates actual costs. |
|[Calendar](653d0805-0a0d-ec40-1b27-91093fecca8b.md) #|[Calendar](897deb82-b9e2-4d7b-f136-2c43728f471e.md) #|[Calendar](897deb82-b9e2-4d7b-f136-2c43728f471e.md) #|[Calendar](a0f53249-347e-63d6-8230-6cb37bbc8477.md)|Gets the project calendar. |
|[CheckedOutBy](41a1d8aa-fe7b-119c-f8fe-2d9b2de43cb6.md) #|[CheckedOutBy](d0f89c29-51ae-122e-9606-a56050efa259.md) #|[CheckedOutBy](d0f89c29-51ae-122e-9606-a56050efa259.md) #|User|Gets the enterprise resource who has the project checked out. (Inherited from Project.) |
|[CheckedOutDate](f38c6a7e-9e51-74d2-5f7d-5222288a4470.md) #|[CheckedOutDate](7933c082-b11b-ff5b-d5de-b4c4c513d335.md) #|[CheckedOutDate](7933c082-b11b-ff5b-d5de-b4c4c513d335.md) #|DateTime|Gets the date when project was checked out. (Inherited from Project.) |
|[CheckOutDescription](0e188b22-664b-561b-21ee-0253adc25a03.md) #|[CheckOutDescription](83ddd70d-8f64-b5ef-933d-afd9e9931949.md) #|[CheckOutDescription](83ddd70d-8f64-b5ef-933d-afd9e9931949.md) #|String|Gets the description of the current checkout action for the project. (Inherited from Project.) |
|[CheckOutId](b9bb69b3-ce95-3a40-78bf-72e750084b29.md) #|[CheckOutId](a9abf00c-ecbd-6576-abc6-5565a49849e2.md) #|[CheckOutId](a9abf00c-ecbd-6576-abc6-5565a49849e2.md) #|Guid|Gets the session GUID that is associated with the current check out. (Inherited from Project.) |
|[CreatedDate](562c7bf3-d9e0-ce8c-92a2-bed3982079dd.md) #|[CreatedDate](c1f90a09-d83a-5a11-21ad-855c7d76cae2.md) #|[CreatedDate](c1f90a09-d83a-5a11-21ad-855c7d76cae2.md) #|DateTime|Gets the date when the project was created. (Inherited from Project.) |
|[CriticalSlackLimit](752e1504-6653-b6c2-604a-5f720b2378b8.md) #|[CriticalSlackLimit](306108bf-1cb7-6d28-4b7f-1e36a23ee6b5.md) #|[CriticalSlackLimit](306108bf-1cb7-6d28-4b7f-1e36a23ee6b5.md) #|Integer|Gets the number of days that a task can go past its end date before the project marks that task as critical. |
|[CurrencyCode](d4663d3b-8df8-e9b0-adec-e2a3f4277f3e.md) #|[CurrencyCode](62a1c3e6-a474-7b1d-0396-6a69d2f2283f.md) #|[CurrencyCode](62a1c3e6-a474-7b1d-0396-6a69d2f2283f.md) #|String|Gets the currency code of the project, as defined in ISO 4217. |
|[CurrencyDigits](1109c592-5fa4-fcb2-1a91-7dcd243a9d7e.md) #|[CurrencyDigits](c9432d59-8dc8-7406-eff8-9017ed47788c.md) #|[CurrencyDigits](c9432d59-8dc8-7406-eff8-9017ed47788c.md) #|Integer|Gets the number of decimal digits in currency values. |
|[CurrencyPosition](97e5e9bf-282a-515f-b212-a0eb13f9c744.md) #|[CurrencyPosition](d51e226e-0647-4c2a-6809-f96d8eca50e1.md) #|[CurrencyPosition](d51e226e-0647-4c2a-6809-f96d8eca50e1.md) #|Enumerated value|Gets the placement of the currency symbol in relation to the currency value. |
|[CurrencySymbol](db219a32-2d78-9e27-802b-6dbd762cc7cd.md) #|[CurrencySymbol](4d855fe4-a064-beae-9b6e-7669c6309fb0.md) #|[CurrencySymbol](4d855fe4-a064-beae-9b6e-7669c6309fb0.md) #|String|Gets the currency symbol that represents the type of currency that is used in the project. |
|[CurrentDate](bb45dd3f-076c-820a-6500-ec30bfbc8387.md) #|[CurrentDate](2c7f2690-38d3-7653-a1af-c162de8991e2.md) #|[CurrentDate](2c7f2690-38d3-7653-a1af-c162de8991e2.md) #|DateTime|Gets the current date for the project. |
|[CustomFields](058d8e47-6825-4ceb-4eaa-b717f62dea0b.md) #|[CustomFields](6c6afddb-ac7a-2c97-cda3-e902fecb72b1.md) #|[CustomFields](6c6afddb-ac7a-2c97-cda3-e902fecb72b1.md) #|CustomFieldCollection|Gets the collection of project custom fields that have values set for the project. (Inherited from Project.) |
|[DaysPerMonth](c0fc5089-dbb1-acdc-4c17-fffe60b01bb7.md) #|[DaysPerMonth](f4e06915-f7ea-c7a3-9969-3e03b12a625c.md) #|[DaysPerMonth](f4e06915-f7ea-c7a3-9969-3e03b12a625c.md) #|short integer|Gets the default number of working days per month. |
|[DefaultEffortDriven](0b25d14c-b28c-d026-0094-70ae5afd1762.md) #|[DefaultEffortDriven](df40bd59-a40b-1ca7-f9a0-9ad9f5244714.md) #|[DefaultEffortDriven](df40bd59-a40b-1ca7-f9a0-9ad9f5244714.md) #|Boolean|Gets a value that indicates whether the scheduling of new tasks is effort-driven. |
|[DefaultEstimatedDuration](82215f0c-7903-7623-77bb-c2ef19df5558.md) #|[DefaultEstimatedDuration](bab8221e-5d10-18a9-0018-a00b6f6e6bbd.md) #|[DefaultEstimatedDuration](bab8221e-5d10-18a9-0018-a00b6f6e6bbd.md) #|Boolean|Gets a value that indicates whether new tasks have estimated durations. |
|[DefaultFinishTime](f744fe10-c47b-8c5f-1e32-787af95f94c5.md) #|[DefaultFinishTime](d05a9902-a281-0c8c-4d36-bc30128a06cf.md) #|[DefaultFinishTime](d05a9902-a281-0c8c-4d36-bc30128a06cf.md) #|DateTime|Gets the default end time of a working day. |
|[DefaultFixedCostAccrual](0d4c7b6a-c631-3ced-a020-1ae0720a1ec3.md) #|[DefaultFixedCostAccrual](be5e1d10-6fe5-ca01-7e7f-fa4c81eca61e.md) #|[DefaultFixedCostAccrual](be5e1d10-6fe5-ca01-7e7f-fa4c81eca61e.md) #|Enumerated value|Gets a value that indicates which default fixed-cost accrual method to use on new tasks. |
|[DefaultOvertimeRate](bbf2e35a-34aa-1355-263e-7957f0974bb6.md) #|[DefaultOvertimeRate](2a8eaa0d-8e98-522c-5694-3ee38a0620dc.md) #|[DefaultOvertimeRate](2a8eaa0d-8e98-522c-5694-3ee38a0620dc.md) #|Double|Gets the default overtime rate for local resources. |
|[DefaultOvertimeRateUnits](0e7a696b-a647-468c-0c23-7ac392eec052.md) #|[DefaultOvertimeRateUnits](5fde23ca-c7a1-31c1-b2d5-26873b24e6e5.md) #|[DefaultOvertimeRateUnits](5fde23ca-c7a1-31c1-b2d5-26873b24e6e5.md) #|Enumerated value |Gets the time unit for the default overtime rate that is stored by the DefaultOvertimeRate property. (Inherited from Project.) |
|[DefaultStandardRate](37169b42-966b-1553-d06a-377840860712.md) #|[DefaultStandardRate](20ce440c-b88c-ab0d-dcc3-7b11ea86a3c5.md) #|[DefaultStandardRate](20ce440c-b88c-ab0d-dcc3-7b11ea86a3c5.md) #|Double|Gets the default standard rate for local resources. |
|[DefaultStandardRateUnits](055841b5-62f7-c675-e2fb-302e171705c3.md) #|[DefaultStandardRateUnits](f6c95f08-e914-ef79-74b3-4061d909b829.md) #|[DefaultStandardRateUnits](f6c95f08-e914-ef79-74b3-4061d909b829.md) #|Enumerated value |Gets the time unit for the default standard rate that is stored by the DefaultStandardRate property. (Inherited from Project.) |
|[DefaultStartTime](20249210-2e34-35f7-aed2-fb7b61a010a4.md) #|[DefaultStartTime](16b65e6d-1db5-214c-6d4b-3335fd828c1e.md) #|[DefaultStartTime](16b65e6d-1db5-214c-6d4b-3335fd828c1e.md) #|DateTime|Gets the default start time of a working day. |
|[DefaultTaskType](a6897ded-3bf6-7bcd-d144-29e774462183.md) #|[DefaultTaskType](46890ca5-3d57-d129-9add-999db57be8fd.md) #|[DefaultTaskType](46890ca5-3d57-d129-9add-999db57be8fd.md) #|Enumerated value|Gets the default type for tasks in the project. |
|[DefaultWorkFormat](6a99930a-9efe-ae54-16de-1b109d690025.md) #|[DefaultWorkFormat](a378c077-906a-4ac9-4e61-ab7beabc2fad.md) #|[DefaultWorkFormat](a378c077-906a-4ac9-4e61-ab7beabc2fad.md) #|Enumerated value|Gets the default format for work duration. |
|[Description](d7699510-657c-7654-c071-ba91c2463117.md) #|[Description](058b9a25-3845-5f96-2daa-6a28dbe30063.md) #|[Description](058b9a25-3845-5f96-2daa-6a28dbe30063.md) #|String|Gets the project description. |
|[Draft](a6f5a2e2-4e9e-7cb9-07e9-769fd88163ef.md) #|[Draft](b53eeb0d-9be1-9479-c86b-9f196a46a9ad.md) #|[Draft](b53eeb0d-9be1-9479-c86b-9f196a46a9ad.md) #|[DraftProject](c915d48d-c1bc-e454-fc2c-81b7a1a48578.md)|Gets a DraftProject object if it is not already checked out. |
|[Engagements]() *,#|[Engagements]() *,#|[Engagements]() *,#|PS.ProjectEngagementCollection||
|[EnterpriseProjectType](a239bbfd-8a78-de67-7995-46747d5a8850.md) #|[EnterpriseProjectType](f39fed21-bebc-3bbe-e1b9-d99c7165de1e.md) #|[EnterpriseProjectType](f39fed21-bebc-3bbe-e1b9-d99c7165de1e.md) #|[EnterpriseProjectType](db9e7200-331b-5f48-8a46-33cd53f916fd.md)|Gets the enterprise project type (EPT) for the project. (Inherited from Project.) |
|||[EnterpriseProjectTypeId]() *,#|? - This is OK||
|||[EntityLinks]() *,#|? - This is OK||
|[FieldValues](b71f0802-7375-1ed7-adde-bb9d327adf1d.md) #|[FieldValues](a1e7d623-0568-2eec-006b-ea2cfd6b901e.md) #|[FieldValues](a1e7d623-0568-2eec-006b-ea2cfd6b901e.md) #|Dictionary/JSON list of key-value pairs|Gets the custom field values for the published project. |
|[FinishDate](b77ee890-b8f7-a21a-92a4-cb858ead7cb2.md) #|[FinishDate](92380e75-db67-e7af-5cd0-5914c9d7bcae.md) #|[FinishDate](92380e75-db67-e7af-5cd0-5914c9d7bcae.md) #|DateTime|Gets the project finish date. |
|[FiscalYearStartMonth](dad18e5b-5266-af90-a55d-b464eac18a82.md) #|[FiscalYearStartMonth](7490919e-7263-6e21-5828-483ce0a22654.md) #|[FiscalYearStartMonth](7490919e-7263-6e21-5828-483ce0a22654.md) #|short integer|Gets the number of the first month in the fiscal year. |
|[HasMppPendingImport](d42f5d06-621c-0dec-d40f-72684654e954.md) #|[HasMppPendingImport](964d4421-2819-bd04-a0da-c53c77a078df.md) #|[HasMppPendingImport](964d4421-2819-bd04-a0da-c53c77a078df.md) #|Boolean|Gets a value that indicates whether there is an mpp file waiting to be imported. (Inherited from Project.) |
|[HonorConstraints](2bac50d3-8bfc-2282-9fdb-f6f5fa455703.md) #|[HonorConstraints](12199489-8e19-77ae-fc44-073169740005.md) #|[HonorConstraints](12199489-8e19-77ae-fc44-073169740005.md) #|Boolean|Gets a value that indicates whether scheduling constraints take precedence over dependencies. |
|[Id](3ad4c300-54ac-8bf7-fb1a-823328b6cf39.md) #|[Id](ebefb7b8-af96-3d9f-9500-e93df5ae9d2f.md) #|[Id](ebefb7b8-af96-3d9f-9500-e93df5ae9d2f.md) #|Guid|Gets the GUID of the project. (Inherited from Project.) |
|[IncludeCustomFields](00236952-61cc-68d7-3e50-65a0e0f9a7f1.md) #|[IncludeCustomFields](b223725a-1d73-54f1-b28e-caa060b2642c.md) #|[IncludeCustomFields](b223725a-1d73-54f1-b28e-caa060b2642c.md) #|[PublishedProject](c8ca8c11-6cbe-7b0f-b9a5-b77060012327.md)|Gets a PublishedProject object that includes custom fields. |
|[IsCheckedOut](5ddccc17-21e8-8e29-dbdf-9ae029ba0df4.md) #|[IsCheckedOut](a75c0953-6f9a-9f9d-e37e-e47a1284d555.md) #|[IsCheckedOut](a75c0953-6f9a-9f9d-e37e-e47a1284d555.md) #|Boolean|Gets a value that indicates whether the project is checked out. (Inherited from Project.) |
|[IsEnterpriseProject](62749e70-9aad-e370-6e09-f5fad026a920.md) #,$|[IsEnterpriseProject](56b66bfb-80c3-fac0-84e7-2ff35c77a8ef.md) #,$|[IsEnterpriseProject](56b66bfb-80c3-fac0-84e7-2ff35c77a8ef.md) #,$|Boolean|Gets or sets a value that indicates whether the published project is an enterprise project (managed by Project Server). |
|[Item](593eaa95-2283-83e0-3899-34baac7d5f26.md) #,$|[Item](6fcc325e-ac93-5967-cd0b-1d106d9a3eba.md) #,$|[Item](6fcc325e-ac93-5967-cd0b-1d106d9a3eba.md) #,$|Object|Gets or sets an item in the project. |
|[LastPublishedDate](a8a950a7-3a7a-0fae-6f3d-34e159b7be57.md) #|[LastPublishedDate](d809457b-4057-7246-40b9-31accdfbbdb0.md) #|[LastPublishedDate](d809457b-4057-7246-40b9-31accdfbbdb0.md) #|DateTime|Gets the most recent date when the project was published. (Inherited from Project.) |
|[LastSavedDate](8ed0932d-71dc-8ece-e257-b51004e62a0a.md) #|[LastSavedDate](1c924cdd-e9b7-ad1d-14d1-5f342566542d.md) #|[LastSavedDate](1c924cdd-e9b7-ad1d-14d1-5f342566542d.md) #|DateTime|Gets the most recent date when the project was saved. (Inherited from Project.) |
|||[ListId]() *,#|? - This is OK||
|[MinutesPerDay](ab7fcf16-e6ea-6b4a-12b1-f45b051009f5.md) #|[MinutesPerDay](208c3258-4b06-44fe-a512-9f0e4e613f64.md) #|[MinutesPerDay](208c3258-4b06-44fe-a512-9f0e4e613f64.md) #|Integer|Gets the default number of minutes per day. |
|[MinutesPerWeek](42aa738d-228d-7986-7a35-ab51d541d1d2.md) #|[MinutesPerWeek](6a6c2a20-c32d-cc78-599e-e45ee583dfaf.md) #|[MinutesPerWeek](6a6c2a20-c32d-cc78-599e-e45ee583dfaf.md) #|Integer|Gets the default number of minutes per week. |
|[MoveActualIfLater](95d049e7-b39a-a46c-6236-e1946903df8b.md) #|[MoveActualIfLater](24bfd072-4b42-c0c0-24fd-f6b5444fbe48.md) #|[MoveActualIfLater](24bfd072-4b42-c0c0-24fd-f6b5444fbe48.md) #|Boolean|Gets a value that indicates whether to move the end date of completed parts forward to the status date, if the actual end date falls before the status date. |
|[MoveActualToStatus](44b00d66-213a-612b-a33f-738f9d69d0e9.md) #|[MoveActualToStatus](bc70e7eb-06ad-f612-627f-0feac795e54c.md) #|[MoveActualToStatus](bc70e7eb-06ad-f612-627f-0feac795e54c.md) #|Boolean|Gets a value that indicates whether to move the end date of completed parts back to the status date, if the actual end data falls after the status date. |
|[MoveRemainingIfEarlier](91f7a4c1-ede8-82c4-df6f-82a86fed3575.md) #|[MoveRemainingIfEarlier](1fabf6c5-1591-3915-93f7-b5a36233fc38.md) #|[MoveRemainingIfEarlier](1fabf6c5-1591-3915-93f7-b5a36233fc38.md) #|Boolean|Gets a value that indicates whether to move the start date of remaining parts forward to the status date, if the actual start date falls before the status date. |
|[MoveRemainingToStatus](40e9cf9d-0920-b6b9-0c45-ef48967c4a66.md) #|[MoveRemainingToStatus](2505a926-f19d-1af8-a0d7-0017548c3abb.md) #|[MoveRemainingToStatus](2505a926-f19d-1af8-a0d7-0017548c3abb.md) #|Boolean|Gets a value that indicates whether to move the start date of the remaining parts back to the status date, if the actual start date falls after the status date. |
|[MultipleCriticalPaths](2162a868-e34c-a44d-72e4-35986c72807c.md) #|[MultipleCriticalPaths](80be1b5c-9bac-b139-a53c-eeeb6e50e1df.md) #|[MultipleCriticalPaths](80be1b5c-9bac-b139-a53c-eeeb6e50e1df.md) #|Boolean|Gets a value that indicates whether to calculate multiple critical paths. |
|[Name](21463879-d5dc-3d41-7904-8ab870c816a7.md) #|[Name](989d213c-57fe-fb04-f98c-a91d5ee018e5.md) #|[Name](989d213c-57fe-fb04-f98c-a91d5ee018e5.md) #|String|Gets the name of the project. |
|[NewTasksAreManual](1b9dfbdd-1d83-d7de-1d52-767cc2ded49e.md) #|[NewTasksAreManual](4096e783-84e3-4f00-496a-216d816aa251.md) #|[NewTasksAreManual](4096e783-84e3-4f00-496a-216d816aa251.md) #|Boolean|Gets a value that indicates whether new tasks are manually scheduled. |
|[NumberFiscalYearFromStart](278931e3-2874-94c7-65e4-2eb4bd4d3594.md) #|[NumberFiscalYearFromStart](46a3527e-6c18-a78b-9648-016e658e8d2f.md) #|[NumberFiscalYearFromStart](46a3527e-6c18-a78b-9648-016e658e8d2f.md) #|Boolean|Gets a value that indicates whether to use the project start year for fiscal year numbering. |
|[OptimizerDecision](0ad91a8e-239e-5ee9-ae4c-2d05d2844697.md) #|[OptimizerDecision](6dc2ff9e-6051-555c-4656-ad5a4284bda6.md) #|[OptimizerDecision](6dc2ff9e-6051-555c-4656-ad5a4284bda6.md) #|Enumerated value |Gets the result of the Optimizer in a project portfolio analysis. (Inherited from Project.) |
|[Owner](bb5b143b-821d-ff85-ee92-557e895b2b14.md) #,$|[Owner](a2d3c54b-710d-984a-b4d9-cfb48dab00f2.md) #,$|[Owner](a2d3c54b-710d-984a-b4d9-cfb48dab00f2.md) #,$|User|Gets the owner of the project. |
|[PercentComplete](d8b22f65-9046-9353-827f-8bff0191a624.md) #|[PercentComplete](8229a534-f2cf-b7c7-3dbc-e3aa731e3144.md) #|[PercentComplete](8229a534-f2cf-b7c7-3dbc-e3aa731e3144.md) #|Integer|Gets the percentage complete of the project summary task. (Inherited from Project.) |
|[Phase](2da4af29-2b10-8b1c-3728-4d5f10cdb79c.md) #|[Phase](3c3af690-0f13-1bbc-22b0-fa1ba49c6ba2.md) #|[Phase](3c3af690-0f13-1bbc-22b0-fa1ba49c6ba2.md) #|[Phase](c5336e3c-52c9-ca7e-ee4e-b280ae5269e0.md)|Gets the current workflow phase of the project. (Inherited from Project.) |
|[PlannerDecision](819ab389-db95-99fc-1ea2-5717a389bd50.md) #|[PlannerDecision](ad42eda1-d7bc-9c6d-ad91-0a174ddfb491.md) #|[PlannerDecision](ad42eda1-d7bc-9c6d-ad91-0a174ddfb491.md) #|Enumerated value |Gets the result of the Planner in a project portfolio analysis. (Inherited from Project.) |
|[ProjectIdentifier]() *,#|[ProjectIdentifier]() *,#|[ProjectIdentifier]() *,#|Integer||
|[ProjectResources](65b0d601-e3d7-9b15-8cad-5a2fbafd18b5.md) #|[ProjectResources](2b650433-155f-913b-83c5-20717e02bbfc.md) #|[ProjectResources](2b650433-155f-913b-83c5-20717e02bbfc.md) #|[PublishedProjectResourceCollection](3341d3f8-fbd3-1312-d092-710e4df39fce.md)|Gets the collection of resources for a project. |
|[ProjectSiteUrl](43430af9-e5c6-60c6-960f-c19b04ebb784.md) #|[ProjectSiteUrl](5647c26c-f0a0-246e-46a2-8bf64e216b7d.md) *,#|[ProjectSiteUrl](5647c26c-f0a0-246e-46a2-8bf64e216b7d.md) #|String|Gets the URL of the project site. (Inherited from Project.) |
|[ProjectSummaryTask]() *,#|[ProjectSummaryTask]() *,#|[ProjectSummaryTask]() *,#|ProjectSummaryTask||
|[ProjectType](884f6ce7-feca-d56b-0572-a444e4a9c5ae.md) #|[ProjectType](406ab18b-24b4-18a4-c061-9b3eae4c0da4.md) #|[ProjectType](406ab18b-24b4-18a4-c061-9b3eae4c0da4.md) #|Enumerated value |Gets the type of project (standard project, template, master project, or subproject). (Inherited from Project.) |
|[ProtectedActualsSynch](07239432-9d5f-be39-2062-45fe9a65228c.md) #|[ProtectedActualsSynch](fddd0219-8e8a-a4ac-894e-324a608312c9.md) #|[ProtectedActualsSynch](fddd0219-8e8a-a4ac-894e-324a608312c9.md) #|Boolean|Gets whether the project actuals are synchronized with the protected actuals. |
|[QueueJobs](93dd46aa-db6b-f403-1601-e96c57418717.md) #|[QueueJobs](66ace9d6-ff3a-24c4-133a-41ce06e9dcef.md) #|[QueueJobs](66ace9d6-ff3a-24c4-133a-41ce06e9dcef.md) #|[QueueJobCollection](9cc098d6-abcd-fbcf-90f4-bed029084b42.md)|Gets the collection of Project Server Queue Service jobs that are associated with the project. (Inherited from Project.) |
|[ScheduledFromStart](e8e93431-0a66-8c23-03b1-10476f63c998.md) #|[ScheduledFromStart](bfa76815-73ea-7144-b415-30f8dadfe67c.md) #|[ScheduledFromStart](bfa76815-73ea-7144-b415-30f8dadfe67c.md) #|Boolean|Gets whether the project is scheduled from the finish date instead of the start date. |
|[ShowEstimatedDurations](c2e9b8f1-d3a5-3b98-ea33-ec6ef92d002e.md) #|[ShowEstimatedDurations](e9d00323-dabe-a9bf-1ad9-0505df5b08a7.md) #|[ShowEstimatedDurations](e9d00323-dabe-a9bf-1ad9-0505df5b08a7.md) #|Boolean|Gets a value that indicates whether a question mark is displayed after an estimated duration for a task. |
|[SplitInProgress](d3f4a872-1ed0-6df2-e627-665721694ac1.md) #|[SplitInProgress](fa35ef31-1d8e-bf9c-473e-6bd1e3f9a3ed.md) #|[SplitInProgress](fa35ef31-1d8e-bf9c-473e-6bd1e3f9a3ed.md) #|Boolean|Gets a value that indicates whether to split tasks that are in progress. |
|[SpreadActualCostsToStatus](0bc64804-979a-6281-fc44-e33d08d32483.md) #|[SpreadActualCostsToStatus](875db967-4329-1717-e9a6-9b03bc3a89d8.md) #|[SpreadActualCostsToStatus](875db967-4329-1717-e9a6-9b03bc3a89d8.md) #|Boolean|Gets a value that indicates whether actual costs are spread to the status date or to the stop date. |
|[SpreadPercentCompleteToStatus](58f7bff0-5f4c-108a-dd50-36f052e942e2.md) #|[SpreadPercentCompleteToStatus](abc4f193-9af2-e0c4-ff2c-dc2c24aa9180.md) #|[SpreadPercentCompleteToStatus](abc4f193-9af2-e0c4-ff2c-dc2c24aa9180.md) #|Boolean|Gets a value that indicates whether the percentage complete consideration period is spread to the status date or to the task finish date. |
|[Stage](ad324297-e262-79c5-9e82-5c2563db9cfa.md) #|[Stage](ae6ea07c-be9f-4c82-d73c-1025e5669c96.md) #|[Stage](ae6ea07c-be9f-4c82-d73c-1025e5669c96.md) #|[Stage](8ef9f206-088b-6ea9-0991-2b7a69de78af.md)|Gets the current workflow stage of the project. (Inherited from Project.) |
|[StartDate](f910e042-cf7e-23f6-b077-621ae996ceac.md) #|[StartDate](49d9fa49-2384-220a-1cdc-4e52ab399e6d.md) #|[StartDate](49d9fa49-2384-220a-1cdc-4e52ab399e6d.md) #|DateTime|Gets the project start date. |
|[StatusDate](45e7aa42-d83a-8451-6840-edd9db53e719.md) #|[StatusDate](5970827e-a591-94a3-4268-a27afb0c65fa.md) #|[StatusDate](5970827e-a591-94a3-4268-a27afb0c65fa.md) #|DateTime|Gets the status date for the project. |
|[SummaryTaskId](4a2fc4bb-91d5-a82b-c4b4-80c7540e3d0e.md) #|[SummaryTaskId](4465d13f-5a03-c1d7-0254-96b5ac779c89.md) #|[SummaryTaskId](4465d13f-5a03-c1d7-0254-96b5ac779c89.md) #|Guid|Gets the GUID for the hidden project summary task. (Inherited from Project.) |
|[TaskLinks](21569314-f31f-d050-2898-450dc2946ce9.md) #|[TaskLinks](cd217cc2-8772-46b4-db86-e7f38502aa13.md) #|[TaskLinks](cd217cc2-8772-46b4-db86-e7f38502aa13.md) #|[PublishedTaskLinkCollection](1be3a6d9-4738-2a92-2ea6-27e3e4a3c425.md)|Gets the collection of task links for the project. |
|[TaskListId](928727ee-b8e3-09a1-9a91-20171f7edbf9.md) #|[TaskListId](94af85c6-af62-a84b-c44f-f0f6ddb6e8e2.md) #|[TaskListId](94af85c6-af62-a84b-c44f-f0f6ddb6e8e2.md) #|Guid|Gets the GUID of the project's task list. (Inherited from Project.) |
|[Tasks](b2fd7ea4-9d46-3485-32f5-112ae3391ae9.md) #|[Tasks](2eb6cd9e-f440-d6b4-cbc3-b9d5e6c53217.md) #|[Tasks](2eb6cd9e-f440-d6b4-cbc3-b9d5e6c53217.md) #|[PublishedTaskCollection](c1da0419-08f3-a859-6c24-ae8ce5750af2.md)|Gets the collection of tasks for the project. |
|[TrackingMode](ba002473-6d5c-7eb8-31ed-f808daf2bc74.md) #|[TrackingMode](c0621ac8-743a-7b29-12c8-887a6b105d72.md) #|[TrackingMode](c0621ac8-743a-7b29-12c8-887a6b105d72.md) #|Enumerated value |Gets the default tracking method for all assignments in the project. |
||[UserPermissions]() *,#|[UserPermissions]() *,#|||
|[UtilizationDate]() *,#|[UtilizationDate]() *,#|[UtilizationDate]() *,#|DateTime||
|[UtilizationType]() *,#|[UtilizationType]() *,#|[UtilizationType]() *,#|Integer|Gets the derivation source(s) of the summary resource assignments of a project. Uses the UtilizationType enumeration.|
|||[WebId]() *,#|? - This is OK||
|[WeekStartDay](3f1bacbd-d80e-25dc-7e3d-ea72bfd2dc7b.md) #|[WeekStartDay](09ddee4f-e588-22e0-77d8-493daeed12eb.md) #|[WeekStartDay](09ddee4f-e588-22e0-77d8-493daeed12eb.md) #|Short integer|Gets the day of the week on which a work week starts. |
|[WinprojVersion](6d0647d4-ad13-fb1a-8c5e-4b58678fb1da.md) #|[WinprojVersion](508ab2fd-12ca-289c-39e5-d427265ec722.md) #|[WinprojVersion](508ab2fd-12ca-289c-39e5-d427265ec722.md) #|Decimal|Gets the version of Project Professional that created the published project. |



  **Note on Symbol Usage:**  
  (*blank*) - indicates the property has Read and Write access, and was available in the previous release.<br />
  * - indicates a new method or property.<br />
  # - indicates Read-Only access to a property.<br />
  $ - indicated Write-Only access to a property.


## Syntax

### CSOM Library

The CSOM .NET library used for client-side applications. The class declaration for PublishedProject follows.

```C#
Public Class PublishedProject _
	Inherits Project
```

#### Inheritance hierarchy

[System.Object](http://msdn2.microsoft.com/EN-US/library/e5kfa45b)[Microsoft.SharePoint.Client.ClientObject](http://msdn2.microsoft.com/EN-US/library/ee540788)<br />
==>[Microsoft.ProjectServer.Client.Project](7efa9ac0-47b3-be64-35ec-85907b1fcd59.md)<br />
==>Microsoft.ProjectServer.Client.PublishedProject

**Namespace:**[Microsoft.ProjectServer.Client](e79057b8-4161-453c-1035-02e38725305c.md) 

**Assembly:**Microsoft.ProjectServer.Client (in Microsoft.ProjectServer.Client.dll)


### JSOM Library

The JSOM library is used for AddIns and is written in JavaScript. The declaration for the PublishedProject object follows:
```
PS.PublishedProject
```

### REST Interface

The 

<a name="restresourceendpoint"> </a>

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

To check out a project for editing, use the  **PublishedProjectCheckOut()** method.

Project Server creates a virtual PublishedProject object for each draft project that has not yet been published. A virtual published project ensures that a draft project can be retrieved through theProjectCollection object, whether it has been published or not. A retrieved project gets properties from the draft tables in the Project database.

For example, if you create a draft project with the PSI, and then read all projects with the CSOM, the ProjectCollection object contains the unpublished draft project. You can determine whether a project has been published by the value of thePublishedProject.LastPublishedDate property, which is inherited from[Project.LastPublishedDate](a8a950a7-3a7a-0fae-6f3d-34e159b7be57.md). For an unpublished project, the LastPublishedDate property value isDateTime.Min (1/1/0001). The following CSOM code fragment creates a draft project but does not persist or publish it.


```C#

	ProjectContext projContext = new ProjectContext("http://ServerName/pwa");
	ProjectCreationInformation newProj = new ProjectCreationInformation();

	newProj.Id = Guid.NewGuid();
	newProj.Name = "Test project not published";
	newProj.Start = DateTime.Today.Date;

	PublishedProject newPublishedProj = projContext.Projects.Add(newProj);

	projContext.Load(newPublishedProj);
	projContext.ExecuteQuery();

	DateTime pubDate = newPublishedProj.LastPublishedDate;
	Console.Write("\n\tLastPublishedDate before publishing: {0}", pubDate.ToString());
```

## Thread safety

Any public  **static** ( **Shared** in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.
## See also



#### Reference

[Microsoft.ProjectServer.Client namespace](e79057b8-4161-453c-1035-02e38725305c.md)
