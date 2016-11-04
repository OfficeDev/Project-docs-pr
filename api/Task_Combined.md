
# Task class
Contains inheritable properties common to draft and published tasks.

## Members

The members consist of the properties defined for the Task object. 

Three different interfaces are available:

* CSOM - client-side library providing support for .NET applications
* JSOM - JavaScript object model library that provides support for AddIn development
* REST - HTTP command-based interface that provides language-agnostic functionality

The table for properties identifies the each property by the name used in each library, the data type of the exchanged value or entity), and a description of the property. 

### Methods

The  **Task** object has no methods.


### Properties

The  **Task** object has the following properties:

|**CSOM** N,R,W|**JSOM (get, set)** N,R,W|**REST** |**Data Type**|**Description**|
|:----- |:----- |:----- |:-----|:-----|
|[ActualCostWorkPerformed]() *,#|[ActualCostWorkPerformed]() *,#|[ActualCostWorkPerformed]() *,#|Double|Gets the costs incurred for work already performed by resources on the task to date.|
|[ActualDuration](19610522-34ff-3920-d36b-51c7b39d52c7.md) #|[ActualDuration](fdda8088-df33-2cd3-c303-b8f944027b78.md) #|[ActualDuration](fdda8088-df33-2cd3-c303-b8f944027b78.md) #|String|Gets the span of active working time that is required to complete a task. (Inherited from Task.|
| |[ActualDurationMilliseconds](74410690-3f4e-403c-1322-9017b181c8ae.md) #|[ActualDurationMilliseconds](74410690-3f4e-403c-1322-9017b181c8ae.md) #|Double|Gets the time interval, expressed in milliseconds, for the span of active working time that is required to complete a task.|
|[ActualDurationTimeSpan](6950c975-b1f2-fb5c-203d-3228c3227f45.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the total time interval for the span of active working time that is required to complete a task. (Inherited from Task.)|
|[ActualOvertimeCost]() *,#|[ActualOvertimeCost]() *,#|[ActualOvertimeCost]() *,#|Double|Gets the costs incurred for overtime work already performed on the task by assigned resources.|
|[ActualOvertimeWork]() *,#|[ActualOvertimeWork]() *,#|[ActualOvertimeWork]() *,#|String|Gets the actual amount of overtime work that has already been performed by resources assigned to the task.|
| |[ActualOvertimeWorkMilliseconds]() *,#|[ActualOvertimeWorkMilliseconds]() *,#|Double|Gets the time interval, expressed in milliseconds, for the actual amount of overtime work already performed by resources assigned to the task.|
|[ActualOvertimeWorkTimeSpan]() *,#| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the time interval for the actual amount of overtime work that has already been performed by resources assigned to the task.|
|[BaselineCost](f99e83dd-cffb-cd41-9c99-b219f99b1663.md) #|[BaselineCost](2956901b-046a-74c5-b8ff-4c7a4bd0f2db.md) #|[BaselineCost](2956901b-046a-74c5-b8ff-4c7a4bd0f2db.md) #|Double|Gets the total planned cost for the task. (Inherited from Task.|
|[BaselineDuration](99e8e3c6-9ce9-50cf-d5db-f4826941f335.md) #|[BaselineDuration](0b32c5ca-67ed-fe57-5516-c945fd478dc3.md) #|[BaselineDuration](0b32c5ca-67ed-fe57-5516-c945fd478dc3.md) #|String|Gets the original span of time that is planned to complete the task, established at the time of the project baseline. (Inherited from Task.|
| |[BaselineDurationMilliseconds](01de99cd-be49-c994-cf09-c015b8a57dec.md) #|[BaselineDurationMilliseconds](01de99cd-be49-c994-cf09-c015b8a57dec.md) #|Double|Gets the time interval, expressed in milliseconds, for the original span of time that is planned to complete the task, established at the time of the project baseline.|
|[BaselineDurationTimeSpan](57d13f25-97b7-0b36-88d6-340edcfffd0a.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the total time interval for the original span of time that is planned to complete the task, established at the time of the project baseline. (Inherited from Task.|
|[BaselineFinish](fea09c9f-c9ee-52dd-cc42-90c695ef017a.md) #|[BaselineFinish](ad873847-38fb-f3dd-fe8e-86c5b32b93d5.md) #|[BaselineFinish](ad873847-38fb-f3dd-fe8e-86c5b32b93d5.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the planned task completion date that was set at the time that the baseline was saved. (Inherited from Task.)|
|[BaselineStart](fb633803-ec74-3d63-e5e2-7f3dcfc0d6ec.md) #|[BaselineStart](48ab7a9c-9b06-84a3-41f3-e7854c95cfd4.md) #|[BaselineStart](48ab7a9c-9b06-84a3-41f3-e7854c95cfd4.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the planned task start date that was set at the time that the baseline was saved. (Inherited from Task.)|
|[BaselineWork](1b7aff5c-241a-5509-0033-6dbd9317e6f5.md) #|[BaselineWork](c8277d80-ae47-ae4b-8c68-de9e03169c2b.md) #|[BaselineWork](c8277d80-ae47-ae4b-8c68-de9e03169c2b.md) #|String|Gets the total planned person-hours that are scheduled for a task, as established at the time of the project baseline. (Inherited from Task.)|
| |[BaselineWorkMilliseconds](9d288bf4-7f2e-ed38-fee2-926f2e05b9f1.md) #|[BaselineWorkMilliseconds](9d288bf4-7f2e-ed38-fee2-926f2e05b9f1.md) #|Double|Gets the time interval, expressed in milliseconds, for the total planned person-hours that are scheduled for the task, as established at the time of the project baseline. (Inherited from Task.|
|[BaselineWorkTimeSpan](9f15d9c1-9226-9d8c-e0b3-ffca7bd94f2f.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the total time interval for the total planned person-hours that are scheduled for the task, as established at the time of the project baseline. (Inherited from Task.)|
|[BudgetCost](e4b538ff-44af-ce2e-be07-5c58421a2dc0.md) #|[BudgetCost](29958266-d2eb-b2ad-3a77-ce700193a0cb.md) #|[BudgetCost](29958266-d2eb-b2ad-3a77-ce700193a0cb.md) #|Double|Gets the budget costs for budget cost resources. (Inherited from Task.)|
|[BudgetedCostWorkPerformed](9982579f-e8e8-f22d-3b42-9380ff9107a7.md) *,#|[BudgetedCostWorkPerformed](89ad9647-082b-ff9e-763f-1a3ac988de78.md) *,#|[BudgetedCostWorkPerformed](89ad9647-082b-ff9e-763f-1a3ac988de78.md) *,#|Double|Gets the budgeted cost of work that has been performed (BCWP) on the task to date.|
|[BudgetedCostWorkScheduled](a53d6480-4d43-7e80-ebb0-340022e080f2.md) *,#|[BudgetedCostWorkScheduled](71f0c1cd-9808-83ad-e8f9-d6d9e41ff372.md) *,#|[BudgetedCostWorkScheduled](71f0c1cd-9808-83ad-e8f9-d6d9e41ff372.md) *,#|Double|Gets the budgeted cost of work that is scheduled (BCWS) for the task.|
|[Contact](c8a83167-b975-0b59-7d12-349b49bb5891.md) *,#|[Contact](0190c914-c96d-49bf-5a8e-2fd71be3f198.md) *,#|[Contact](0190c914-c96d-49bf-5a8e-2fd71be3f198.md) *,#|String|Gets the name of the individual who is responsible for a task.|
|[CostPerformanceIndex](1dcd4dbb-89e8-516c-ddff-27ef8c177d1f.md) #|[CostPerformanceIndex](4d19bf07-b50c-4666-3cd6-f5e1cd0c63ec.md) #|[CostPerformanceIndex](4d19bf07-b50c-4666-3cd6-f5e1cd0c63ec.md) #|Double|Gets the ratio of the baseline costs of work that has been performed on the task to the actual costs of work that has been performed, calculated up to the project status date or today's date. (Inherited from Task.)|
|[CostVariance](cf1347db-ef49-ee83-4450-2e47df2cad2a.md) #|[CostVariance](56aef638-c9f7-d516-73dc-d991e7f9cdd3.md) #|[CostVariance](56aef638-c9f7-d516-73dc-d991e7f9cdd3.md) #|Double|Gets the difference between the baseline cost and the total cost for the task. (Inherited from Task.)|
|[CostVarianceAtCompletion](d76c3476-be0b-c7b9-51ef-0fdaf16dbcb2.md) #|[CostVarianceAtCompletion](1ebfe122-031d-4eb5-f0cd-25348b429a4c.md) #|[CostVarianceAtCompletion](1ebfe122-031d-4eb5-f0cd-25348b429a4c.md) #|Double|Gets the difference between the baseline cost and the total cost at the completion of the task. (Inherited from Task.)|
|[CostVariancePercentage](7796fdfe-5177-2e4a-8196-46a92ef14b06.md) #|[CostVariancePercentage](c0892052-ddf8-06ff-aa56-3410eaa8def9.md) #|[CostVariancePercentage](c0892052-ddf8-06ff-aa56-3410eaa8def9.md) #|Integer|Gets the ratio of cost variance (CV) to the budgeted cost of work that has been performed on the task (BCWP), expressed as a percentage. (Inherited from Task.)|
|[Created](9b9b8907-3cd1-044f-9531-14f8a8c1a309.md) #|[Created](eb74eae2-ae3f-184e-7f17-1c3f3ea1499f.md) #|[Created](eb74eae2-ae3f-184e-7f17-1c3f3ea1499f.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the date and the time when the task was added to the project. (Inherited from Task.)|
|[CurrentCostVariance]() *,#|[CurrentCostVariance]() *,#|[CurrentCostVariance]() *,#|Double||
|[CustomFields](9b077062-6303-9227-41ce-4ed33a1e9119.md) #|[CustomFields](d1d92cfc-dc2d-28a7-3e23-eb72579d9876.md) #|[CustomFields](d1d92cfc-dc2d-28a7-3e23-eb72579d9876.md) #|[CustomFieldCollection](39c70b02-09d2-d60e-94d9-ea538846124a.md)|Gets the collection of custom fields for the task. (Inherited from Task.)|
|[DurationVariance](887b2576-b176-2971-e093-3bab555252cd.md) #|[DurationVariance](c4ffd628-850b-0b79-104a-356a63ee3bec.md) #|[DurationVariance](c4ffd628-850b-0b79-104a-356a63ee3bec.md) #|String|Gets the difference between the baseline duration of the task and the total duration, or current estimated duration, of the task. (Inherited from Task.)|
| |[DurationVarianceMilliseconds](0e62d2a6-e37d-2efb-0a5c-9d41c466e867.md) #|[DurationVarianceMilliseconds](0e62d2a6-e37d-2efb-0a5c-9d41c466e867.md) #|Double|Gets the time interval, expressed in milliseconds, of the difference between the baseline duration of the task and the total duration, or current estimated duration, of the task.|
|[DurationVarianceTimeSpan](1e868d77-79e0-f087-0c1a-d894dcf47995.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the total time interval for the difference between the baseline duration of the task and the total duration, or current estimated duration, of the task. (Inherited from Task.)|
|[EarliestFinish](1f530771-21dc-d83b-d67f-e478e0699515.md) #|[EarliestFinish](31d9524a-9e0f-751c-dbbc-fc2254007513.md) #|[EarliestFinish](31d9524a-9e0f-751c-dbbc-fc2254007513.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the earliest date that the task could possibly finish, based on the early finish dates of predecessor and successor tasks, other constraints, and any leveling delay. (Inherited from Task.)|
|[EarliestStart](fd2aecc7-bb40-0c0b-4fff-bbe334d869cf.md) #|[EarliestStart](8cda0215-1ef6-380f-f62e-c55b297aea78.md) #|[EarliestStart](8cda0215-1ef6-380f-f62e-c55b297aea78.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the earliest date that the task could possibly begin, based on the early start dates of predecessor and successor tasks and other constraints. (Inherited from Task.)|
|[EstimateAtCompletion](ee9c449b-afb9-983c-b3ae-08db2788fd57.md) #|[EstimateAtCompletion](3af38a9d-56c5-7813-9f00-f1ee1128281b.md) #|[EstimateAtCompletion](3af38a9d-56c5-7813-9f00-f1ee1128281b.md) #|Double|Gets the estimate at completion (EAC) for the task. (Inherited from Task.)|
|[FinishSlack](853c0cc4-44a3-13dd-c965-f783351b2393.md) #|[FinishSlack](2603ebb5-c6fe-0699-fd63-c1b3f2972143.md) #|[FinishSlack](2603ebb5-c6fe-0699-fd63-c1b3f2972143.md) #|String|Gets the duration between the EarlyFinish date and theLateFinish date. (Inherited from Task.)|
| |[FinishSlackMilliseconds](ff3ddb44-3722-9e7c-8859-d5198e9b3b23.md) #|[FinishSlackMilliseconds](ff3ddb44-3722-9e7c-8859-d5198e9b3b23.md) #|Double|Gets the time interval, expressed in milliseconds, of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|[FinishSlackTimeSpan](8ce53c1d-7c8f-7e74-fe28-beb0ed80305d.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the total time interval of planned person-hours scheduled for an assignment, at the time of the project baseline. (Inherited from Task.)|
|[FinishVariance](24daf6c6-8e93-1962-5308-e261c131bc7f.md) #|[FinishVariance](5cce38f9-794b-7838-00d7-bff1ed4c4b0b.md) #|[FinishVariance](5cce38f9-794b-7838-00d7-bff1ed4c4b0b.md) #|String|Gets the time that represents the difference between the baseline finish date of the task and the current finish date. (Inherited from Task.)|
| |[FinishVarianceMilliseconds](3a49bb41-045b-b0cb-7e4a-595fb8d95e04.md) #|[FinishVarianceMilliseconds](3a49bb41-045b-b0cb-7e4a-595fb8d95e04.md) #|Double|Gets the time interval, expressed in milliseconds, of the variance of the finish date of the task.|
|[FinishVarianceTimeSpan](07524705-07d0-3647-d9d6-716cb1d3b131.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the time interval for the variance of the finish date of the task. (Inherited from Task.)|
|[FixedCostAccrual](99539329-317f-f85c-9017-76e453ad516c.md) *,#|[FixedCostAccrual](04b348de-db98-7f61-45e5-bbd4d6297536.md) *,#|[FixedCostAccrual](04b348de-db98-7f61-45e5-bbd4d6297536.md) *,#|FixedCostAccrual|Gets the cost accrual method for how and when fixed costs are to be charged, or accrued, to the cost of the task.|
|[FreeSlack](c1b56de3-194d-98a5-08c0-84a93db0709e.md) #|[FreeSlack](1ef33a4b-bfeb-4739-df77-dbbff8f9e9e7.md) #|[FreeSlack](1ef33a4b-bfeb-4739-df77-dbbff8f9e9e7.md) #|String|Gets the amount of time that the task can be delayed without delaying successor tasks. (Inherited from Task.)|
| |[FreeSlackMilliseconds](8acca175-0e1b-27c6-a2dd-20278fa6284a.md) #|[FreeSlackMilliseconds](8acca175-0e1b-27c6-a2dd-20278fa6284a.md) #|Double|Gets the time interval, expressed in milliseconds, of the amount of time that the task can be delayed without delaying successor tasks.|
|[FreeSlackTimeSpan](3832f813-6e31-6c46-130c-409bbd51d160.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the total time interval for the amount of time that the task can be delayed without delaying successor tasks. (Inherited from Task.)|
|[Id](bb848e92-ecae-6280-ecf0-a27bc30cf29c.md) #|[Id](7b159eb3-530d-c699-2249-e9b8d264346d.md) #|[Id](7b159eb3-530d-c699-2249-e9b8d264346d.md) #|[Guid](http://msdn2.microsoft.com/EN-US/library/cey1zx63)|Gets the GUID of the task. (Inherited from Task.)|
|[IgnoreResourceCalendar]() *,#|[IgnoreResourceCalendar]() *,#|[IgnoreResourceCalendar]() *,#|Boolean||
|[IsCritical](ea890c1c-7449-5c73-629c-9736866e37da.md) #|[IsCritical](e3bda25e-9be2-e31b-4145-5a95e7976cc1.md) #|[IsCritical](e3bda25e-9be2-e31b-4145-5a95e7976cc1.md) #|Boolean|Gets a value that indicates whether the timing for the task is critical or whether there can be any slack in the timing. (Inherited from Task.)|
|[IsEffortDriven](29f6e272-8925-81fb-57bf-5b484877ea66.md) *,#|[IsEffortDriven](6a5aa486-6daf-2576-aa84-c33e3a695b05.md) *,#|[IsEffortDriven](6a5aa486-6daf-2576-aa84-c33e3a695b05.md) *,#|Boolean|Gets a value that indicates whether the scheduling of the task is effort-driven.|
|[IsExternalTask](750ae403-1b5b-409f-db51-81e9e8261ade.md) #|[IsExternalTask](4031d10e-26a4-fd1a-e78b-74f0be6b74df.md) #|[IsExternalTask](4031d10e-26a4-fd1a-e78b-74f0be6b74df.md) #|Boolean|Gets a value that indicates whether this is a ghost task from another project created by Project Professional. (Inherited from Task.)|
|[IsOverAllocated](baba44ad-2cb9-efb7-1f37-53fe4e981b6c.md) #|[IsOverAllocated](d1918852-9d38-19f2-aea0-ec33bb9e508f.md) #|[IsOverAllocated](d1918852-9d38-19f2-aea0-ec33bb9e508f.md) #|Boolean|Gets a value that indicates whether the task is overallocated. (Inherited from Task.)|
|[IsRecurring](b43819a4-adb5-e6f0-341b-1dcceaa5d751.md) #|[IsRecurring](e86b0d28-ec49-c321-737d-5cc9fa799a14.md) #|[IsRecurring](e86b0d28-ec49-c321-737d-5cc9fa799a14.md) #|Boolean|Gets a value that indicates whether the task is part of a recurring series. (Inherited from Task.)|
|[IsRecurringSummary](51029395-56e6-5302-e77e-363a7b60390b.md) #|[IsRecurringSummary](569d068e-e7a6-4377-7f6f-f516e619f1ff.md) #|[IsRecurringSummary](569d068e-e7a6-4377-7f6f-f516e619f1ff.md) #|Boolean|Gets a value that indicates whether the task is the parent of a recurring series. (Inherited from Task.)|
|[IsRolledUp](7be45167-e301-03de-b230-2658f4bc2b41.md) #|[IsRolledUp](4bd0a124-3052-b42c-23fa-97bd1add4432.md) #|[IsRolledUp](4bd0a124-3052-b42c-23fa-97bd1add4432.md) #|Boolean|Gets a value that indicates whether information on the subtask Gantt bars is rolled up to the summary task bar. (Inherited from Task.)|
|[IsSubProject](cdf9f69e-047a-60c8-c186-11b3fb49e3d4.md) #|[IsSubProject](98dcf9cf-e52a-583e-20cf-7b95023bc7b0.md) #|[IsSubProject](98dcf9cf-e52a-583e-20cf-7b95023bc7b0.md) #|Boolean|Gets a value that indicates whether the task represents a subproject. (Inherited from Task.)|
|[IsSubProjectReadOnly](0dde16ef-d692-1a33-9c7d-b0c080a78bfd.md) #|[IsSubProjectReadOnly](34249c7f-69a9-9ac3-6a92-8e2943240168.md) #|[IsSubProjectReadOnly](34249c7f-69a9-9ac3-6a92-8e2943240168.md) #|Boolean|Gets a value that indicates whether a subproject for this task is read-only. (Inherited from Task.)|
|[IsSubProjectScheduledFromFinish](013ee10c-18ea-7acb-2083-9aaa126e9930.md) #|[IsSubProjectScheduledFromFinish](208edd0a-5e86-6439-b74c-22d7864e7cf6.md) #|[IsSubProjectScheduledFromFinish](208edd0a-5e86-6439-b74c-22d7864e7cf6.md) #|Boolean|Gets a value that indicates whether a subproject for this task is set to schedule from finish. (Inherited from Task.)|
|[IsSummary](fb3f4b31-ca3b-a92d-75db-bd9705af851f.md) #|[IsSummary](3cd2e7d0-3621-7dfa-c471-aadeb5c2e293.md) #|[IsSummary](3cd2e7d0-3621-7dfa-c471-aadeb5c2e293.md) #|Boolean|Gets a value that indicates whether the task is a summary task. (Inherited from Task.)|
|[LatestFinish](dae23b82-3572-bd9b-bb56-912353e2c0d3.md) #|[LatestFinish](590f3892-e264-5d6a-80bd-77e9afb21cbc.md) #|[LatestFinish](590f3892-e264-5d6a-80bd-77e9afb21cbc.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the latest date that the task can finish without delaying the finish of the project. (Inherited from Task.)|
|[LatestStart](af420814-345f-bf31-3937-9c7807b5e186.md) #|[LatestStart](d76d9a94-1c4e-2cfc-c4f0-44fb39992abe.md) #|[LatestStart](d76d9a94-1c4e-2cfc-c4f0-44fb39992abe.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the latest date that the task can start without delaying the finish of the project. (Inherited from Task.)|
|[LevelingDelay](43063858-23cd-5ffc-7555-e481aa28c9c9.md) *,#|[LevelingDelay](40b7336f-21b3-3da6-9804-9f0281e38c57.md) *,#|[LevelingDelay](40b7336f-21b3-3da6-9804-9f0281e38c57.md) *,#|String|Gets the amount of time that leveling can delay the task from its early start.|
| |[LevelingDelayMilliseconds](74a20914-9beb-199d-94e0-d461df5c9ca6.md) *,#|[LevelingDelayMilliseconds](74a20914-9beb-199d-94e0-d461df5c9ca6.md) *,#|Double|Gets the time interval, expressed in milliseconds, for the amount of time that leveling can delay the task from its early start.|
|[LevelingDelayTimeSpan](515d1336-181d-159d-1894-4f6468fdbd29.md) *,#| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the time interval for the amount of time that leveling can delay the task from its early start.|
|[Modified](aca65524-1360-340d-3d28-5f6fefe19007.md) #|[Modified](b0392154-a8fc-3898-093c-467a61b8f2f2.md) #|[Modified](b0392154-a8fc-3898-093c-467a61b8f2f2.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the modified date. (Inherited from Task.)|
|[Notes](c1058799-5e04-0524-ec8e-3966086de3a4.md) #|[Notes](1aba7ca2-222c-72db-dac1-c2f2b20a9555.md) #|[Notes](1aba7ca2-222c-72db-dac1-c2f2b20a9555.md) #|String|Gets the notes about the task. (Inherited from Task.)|
|[OutlinePosition](872fe727-ee2e-e6de-4e69-ee49c60c8952.md) #|[OutlinePosition](4b400c4a-ed64-90eb-584f-cbe5f213d592.md) #|[OutlinePosition](4b400c4a-ed64-90eb-584f-cbe5f213d592.md) #|String|Gets the position of the task in the project outline hierarchy. (Inherited from Task.)|
|[OvertimeCost](2e702c3b-168d-5647-a716-9df0eccd300c.md) #|[OvertimeCost](034273c4-f31e-99ac-ac98-489f86a2811e.md) #|[OvertimeCost](034273c4-f31e-99ac-ac98-489f86a2811e.md) #|Double|Gets the total overtime cost for the task. (Inherited from Task.)|
|[OvertimeWork](9c6c6515-95d3-c36d-f430-1aaae1b836d9.md) #|[OvertimeWork](5367645f-19c0-9a3d-3588-3d8738a39dce.md) #|[OvertimeWork](5367645f-19c0-9a3d-3588-3d8738a39dce.md) #|String|Gets the amount of overtime scheduled to be performed on the task. (Inherited from Task.)|
| |[OvertimeWorkMilliseconds](709235e5-a0e6-1975-b5a5-da0b8a4a3cb2.md) #|[OvertimeWorkMilliseconds](709235e5-a0e6-1975-b5a5-da0b8a4a3cb2.md) #|Double|Gets the time interval, expressed in milliseconds, for the amount of overtime scheduled to be performed on the task.|
|[OvertimeWorkTimeSpan](2474a184-e6a7-d165-2c54-2e01f62b780a.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the total time interval for the amount of overtime scheduled to be performed on the task. (Inherited from Task.)|
|[PercentWorkComplete](d74cafa1-1f4a-3199-6e73-1a405da83dca.md) #|[PercentWorkComplete](3ac91a3c-22c7-00f8-1446-148132f3fb1b.md) #|[PercentWorkComplete](3ac91a3c-22c7-00f8-1446-148132f3fb1b.md) #|Integer|Gets the current status of the task, expressed as the percentage of work that has been completed. (Inherited from Task.)|
|[PreLevelingFinish](9d296690-b691-e381-5d70-603620462544.md) #|[PreLevelingFinish](00d103a6-0052-57ee-4c69-2701ef68a156.md) #|[PreLevelingFinish](00d103a6-0052-57ee-4c69-2701ef68a156.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the finish date of the task as it was before resource leveling was performed. (Inherited from Task.)|
|[PreLevelingStart](817d4ee7-f14b-45e5-434d-5d88692edcee.md) #|[PreLevelingStart](bc5966d6-6a93-38d9-74ad-3d802686dae0.md) #|[PreLevelingStart](bc5966d6-6a93-38d9-74ad-3d802686dae0.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the start date of the task as it was before resource leveling was performed. (Inherited from Task.)|
|[RegularWork](28b7fb93-ec04-c004-e087-1d74a2e6aeb6.md) #|[RegularWork](4c682928-4632-270b-13de-1f75fcc6aa78.md) #|[RegularWork](4c682928-4632-270b-13de-1f75fcc6aa78.md) #|String|Gets the total amount of non-overtime work that is scheduled to be performed on the task. (Inherited from Task.)|
| |[RegularWorkMilliseconds](54d689fe-11fd-9a99-e05f-7969c8713075.md) #|[RegularWorkMilliseconds](54d689fe-11fd-9a99-e05f-7969c8713075.md) #|Double|Gets the time interval, expressed in milliseconds, for the total amount of non-overtime work that is scheduled to be performed on the task.|
|[RegularWorkTimeSpan](115276d7-2322-2e19-e785-8176f3cc638b.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the total time interval for the total amount of non-overtime work that is scheduled to be performed on the task. (Inherited from Task.)|
|[RemainingCost](9dc8cc4c-49ec-234e-e46a-2817668d038b.md) #|[RemainingCost](e9dac047-496f-5c14-a0b4-402509ecf358.md) #|[RemainingCost](e9dac047-496f-5c14-a0b4-402509ecf358.md) #|Double|Gets the remaining scheduled expense that will be incurred during completion of the remaining scheduled work on the task. (Inherited from Task.)|
|[RemainingOvertimeCost](df8f6ea4-8233-9de8-af7d-323bb9cf27f3.md) #|[RemainingOvertimeCost](02bb0219-1e62-dae8-d50a-095a5576234c.md) #|[RemainingOvertimeCost](02bb0219-1e62-dae8-d50a-095a5576234c.md) #|Double|Gets the remaining scheduled overtime expense for the task. (Inherited from Task.)|
|[RemainingOvertimeWork](eea361a9-20db-59ed-57bb-13c930a430f2.md) #|[RemainingOvertimeWork](4f7372dc-aa92-9e8a-8c43-a278bd46dcab.md) #|[RemainingOvertimeWork](4f7372dc-aa92-9e8a-8c43-a278bd46dcab.md) #|String|Gets the amount of time, such as person-hours or days, that is required to complete the remaining overtime work for a task. (Inherited from Task.)|
| |[RemainingOvertimeWorkMilliseconds](8a955398-7576-b3ed-d932-89b58fd9c879.md) #|[RemainingOvertimeWorkMilliseconds](8a955398-7576-b3ed-d932-89b58fd9c879.md) #|Double|Gets the time interval, expressed in milliseconds, for the amount of time, such as person-hours or days, that is required to complete the remaining overtime work for a task.|
|[RemainingOvertimeWorkTimeSpan](55347307-e7aa-f7d8-5224-c1b185e3b219.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the total time interval for the amount of time, such as person-hours or days, that is required to complete the remaining overtime work for a task. (Inherited from Task.)|
|[RemainingWork](b8809d17-5d61-e7e7-a213-010bf993bb22.md) #|[RemainingWork](d9ae809c-cdd1-3b1b-8e69-ea0139557524.md) #|[RemainingWork](d9ae809c-cdd1-3b1b-8e69-ea0139557524.md) #|String|Gets the time, such as person-hours or days, that is required to complete the task or set of tasks. (Inherited from Task.)|
| |[RemainingWorkMilliseconds](97f1e316-501c-47c5-765f-9e9e1711077d.md) #|[RemainingWorkMilliseconds](97f1e316-501c-47c5-765f-9e9e1711077d.md) #|Double|Gets the time interval, expressed in milliseconds, for the time, such as person-hours or days, that is required to complete the task or set of tasks.|
|[RemainingWorkTimeSpan](8c56bf02-8d35-13c0-c743-567ef913322c.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the total time interval for the time, such as person-hours or days, that is required to complete the task or set of tasks. (Inherited from Task.)|
|[Resume](e1d09773-1b32-29f3-c411-1d074a739424.md) #|[Resume](8f47f6a7-0858-0d9c-ffeb-d596d56acb4a.md) #|[Resume](8f47f6a7-0858-0d9c-ffeb-d596d56acb4a.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the date that the remaining part of the task is scheduled to resume after progress is entered. (Inherited from Task.)|
|[ScheduleCostVariance](e4dd2dad-fdfe-3608-baa4-664ce5a3bf09.md) #|[ScheduleCostVariance](2dcdbaf8-f434-0ea3-76b7-5e8240decabf.md) #|[ScheduleCostVariance](2dcdbaf8-f434-0ea3-76b7-5e8240decabf.md) #|Double|Gets the difference in cost terms between the current progress and the baseline planned progress for a resource on the task. (Inherited from Task.)|
|[SchedulePerformanceIndex](8253a323-ae2e-e7e2-2fb8-20dc2cffefda.md) #|[SchedulePerformanceIndex](4f34e54c-8620-dd6d-e94f-5c71a58090af.md) #|[SchedulePerformanceIndex](4f34e54c-8620-dd6d-e94f-5c71a58090af.md) #|Double|Gets the ratio of the budgeted cost of work performed to the budgeted cost of work scheduled. (Inherited from Task.)|
|[ScheduleVariancePercentage](b6bce06d-7ec1-2434-e787-530ac336eb68.md) #|[ScheduleVariancePercentage](fcaef959-7468-1d0c-cde9-b8734220a65b.md) #|[ScheduleVariancePercentage](fcaef959-7468-1d0c-cde9-b8734220a65b.md) #|Integer|Gets the ratio of schedule variance (SV) to budgeted cost of work scheduled (BCWS), expressed as a percentage. (Inherited from Task.)|
|[ScheduledDuration](5f5d9188-93a8-bcda-ed84-5912b7961645.md) #|[ScheduledDuration](b5fbad14-a908-d732-aed0-09ad76cdb9e9.md) #|[ScheduledDuration](b5fbad14-a908-d732-aed0-09ad76cdb9e9.md) #|String|Gets the total span of active working time for the task as entered or as calculated based on the start date, the finish date, calendars, and other scheduling factors. (Inherited from Task.)|
| |[ScheduledDurationMilliseconds](63811418-0204-2961-f1e1-7f9d08bb5721.md) #|[ScheduledDurationMilliseconds](63811418-0204-2961-f1e1-7f9d08bb5721.md) #|Double|Gets the time interval, expressed in milliseconds, for the total span of active working time for the task as entered or as calculated based on the start date, the finish date, calendars, and other scheduling factors.|
|[ScheduledDurationTimeSpan](6c6bb830-f988-1c1a-dc9b-98ef1a227a98.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the time interval for the total span of active working time for the task as entered or as calculated based on the start date, the finish date, calendars, and other scheduling factors. (Inherited from Task.)|
|[ScheduledFinish](051bb1a3-91f2-0638-c674-357bbc3dfe3c.md) #|[ScheduledFinish](df0d195f-1d69-81f9-1b6b-2ddd0e118a92.md) #|[ScheduledFinish](df0d195f-1d69-81f9-1b6b-2ddd0e118a92.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the date when work on the task is scheduled to be complete as it was calculated based on the start date, the duration, dependencies, calendars, and other scheduling factors. (Inherited from Task.)|
|[ScheduledStart](9096b28f-3d14-e625-1d21-6400e4fa0cf4.md) #|[ScheduledStart](896a3e2c-3b99-4af4-0935-8f3d45b7d10b.md) #|[ScheduledStart](896a3e2c-3b99-4af4-0935-8f3d45b7d10b.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the date when work on the task is scheduled to begin as it was calculated based on dependencies, constraints, calendars, and other scheduling factors. (Inherited from Task.)|
|[StartSlack](299beca5-fdf2-90b7-b8d2-b4454e2db9a7.md) #|[StartSlack](92a99a71-6469-8839-7ca9-b4c5ee535e05.md) #|[StartSlack](92a99a71-6469-8839-7ca9-b4c5ee535e05.md) #|String|Gets the duration between the EarlyStart date and theLateStart date. (Inherited from Task.)|
| |[StartSlackMilliseconds](d0c96a43-4b75-5950-8727-c1512efec8e4.md) #|[StartSlackMilliseconds](d0c96a43-4b75-5950-8727-c1512efec8e4.md) #|Double|Gets the time interval, expressed in milliseconds, for the duration between the EarlyStart date and theLateStart date.|
|[StartSlackTimeSpan](ff22d6da-03b6-34f1-dd88-d3b864e21825.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the time interval for the duration between the EarlyStart date and theLateStart date. (Inherited from Task.)|
|[StartVariance](9c868856-2b12-655b-d261-0e224dc2324c.md) #|[StartVariance](7ddc744d-c6b9-bef9-cf91-a19685bf4e26.md) #|[StartVariance](7ddc744d-c6b9-bef9-cf91-a19685bf4e26.md) #|String|Gets the time that represents the difference between a baseline start date of the task and its currently scheduled start date. (Inherited from Task.)|
| |[StartVarianceMilliseconds](61bb0d89-b5e0-b469-8352-6441ba825766.md) #|[StartVarianceMilliseconds](61bb0d89-b5e0-b469-8352-6441ba825766.md) #|Double|Gets the time interval, expressed in milliseconds, for the variance of the task start date.|
|[StartVarianceTimeSpan](246a3061-a712-0c66-bfab-f01fe2989e8c.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577)|Gets the time interval for the variance of the task start date. (Inherited from Task.)|
|[Stop](1754c025-1a62-a7c9-3f96-fae39e16fa28.md) #|[Stop](2a84ce10-e29d-c35e-6586-7478c60cf483.md) #|[Stop](2a84ce10-e29d-c35e-6586-7478c60cf483.md) #|[DateTime](http://msdn2.microsoft.com/EN-US/library/03ybds8y)|Gets the date that represents the end of the actual portion of the task. (Inherited from Task.)|
|[SubProject](18686c8b-ec80-993e-e8b7-7f90c8c8c229.md) #|[SubProject](89bf1300-ee01-a36b-9042-ca4d51a6e08d.md) #|[SubProject](89bf1300-ee01-a36b-9042-ca4d51a6e08d.md) #|[PublishedProject](c8ca8c11-6cbe-7b0f-b9a5-b77060012327.md)|Gets a project that has been inserted into the master project. (Inherited from Task.)|
|[TaskType](a31cd8e8-aa3a-349b-54b4-61133b1a64f3.md) *,#|[TaskType](f2d66bf1-e516-4123-e6d4-05b5e09b5d14.md) *,#|[TaskType](f2d66bf1-e516-4123-e6d4-05b5e09b5d14.md) *,#|[TaskType](19207026-36b7-84a4-786c-05c87d2dc4c8.md)|Gets the task type.|
|[ToCompletePerformanceIndex](ef60e4fc-e050-252d-6639-f82a38d96822.md) #|[ToCompletePerformanceIndex](3e507ebe-2e6c-ef0a-ee88-0c8b391152fb.md) #|[ToCompletePerformanceIndex](3e507ebe-2e6c-ef0a-ee88-0c8b391152fb.md) #|Double|Gets the To Complete Performance Index for the task. (Inherited from Task.)|
|[TotalSlack](9b0ce70d-828b-ade9-51c8-bfbedb31294a.md) #|[TotalSlack](e61294b5-f89b-fcfa-1798-e0ecc306fb06.md) #|[TotalSlack](e61294b5-f89b-fcfa-1798-e0ecc306fb06.md) #|String|Gets the time that the task's finish date can be delayed without delaying the project's finish date. (Inherited from Task.)|
| |[TotalSlackMilliseconds](fde3efd0-54de-6a11-fb46-a36ce3001642.md) #|[TotalSlackMilliseconds](fde3efd0-54de-6a11-fb46-a36ce3001642.md) #|Double|Gets the time interval, expressed in milliseconds, for the amount of time that the task finish date can be delayed without delaying the project's finish date.|
|[TotalSlackTimeSpan](ef142436-b5b9-5346-b7ea-d37bf1140867.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577) |Gets the total time interval for the amount of time that the task finish date can be delayed without delaying the project's finish date. (Inherited from Task.)|
|[WorkBreakdownStructure](a24019fe-6302-1a14-f830-89afcf7755c7.md) #|[WorkBreakdownStructure](1689804c-67cc-d94f-f295-abdac9c67c99.md) #|[WorkBreakdownStructure](1689804c-67cc-d94f-f295-abdac9c67c99.md) #|String|Gets a code that identifies a location in a hierarchical structure that is used to organize tasks for reporting schedules and tracking costs. (Inherited from Task.)|
|[WorkVariance](9f0b56d2-43db-a262-7144-d6a0a72bb860.md) #|[WorkVariance](6de1996b-24aa-6fe4-18d6-066ad58bf89b.md) #|[WorkVariance](6de1996b-24aa-6fe4-18d6-066ad58bf89b.md) #|String|Gets the difference between baseline work and currently scheduled work on a task, expressed as, for example, the number of person-hours or days. (Inherited from Task.)|
| |[WorkVarianceMilliseconds](da38de49-ac82-74b9-60ee-9f1ba26b32a2.md) #|[WorkVarianceMilliseconds](da38de49-ac82-74b9-60ee-9f1ba26b32a2.md) #|Double|Gets the time interval, expressed in milliseconds, for the difference between baseline work and currently scheduled work on the task.|
|[WorkVarianceTimeSpan](70ed3e81-69e3-fe12-30d3-daa32791b543.md) #| | |[TimeSpan](http://msdn2.microsoft.com/EN-US/library/269ew577) |Gets the total time interval for the difference between baseline work and currently scheduled work on the task. (Inherited from Task.)|




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
==>Microsoft.ProjectServer.Client.Task <br />
==>[Microsoft.ProjectServer.Client.DraftTask](ce4789dd-75b3-c3b6-ce28-33c9b663c817.md)<br />
==>[Microsoft.ProjectServer.Client.PublishedTask](2b7a0448-19f3-ba5d-5585-2c9cb53407d9.md)

**Namespace:**[Microsoft.ProjectServer.Client](e79057b8-4161-453c-1035-02e38725305c.md) 

**Assembly:**Microsoft.ProjectServer.Client (in Microsoft.ProjectServer.Client.dll)


### JSOM Library

The JSOM library is used for AddIns and is written in JavaScript. The declaration for the Task object follows:
```
PS.Task
```

### REST Interface

The <a name="restresourceendpoint"> </a>

#### Endpoint URI structure
<a name="endpointuristructure"> </a>


```
http://<sitecollection> /<site> /_api/ProjectServer/Tasks('taskid')
```


#### HTTP requests
<a name="httprequests"> </a>

This resource supports the following HTTP commands:


- [GET](a2431b86-5e45-b4f5-dfb7-77145e3ac930.md#getsyntax)
    
- [DELETE](a2431b86-5e45-b4f5-dfb7-77145e3ac930.md#deletesyntax)
    

#### GET syntax
<a name="getsyntax"> </a>


```
GET http://<sitecollection> /<site> /_api/ProjectServer/Tasks('taskid')
```


#### DELETE syntax
<a name="deletesyntax"> </a>


```
DELETE http://<sitecollection> /<site> /_api/ProjectServer/Tasks('taskid')
```



## Remarks

A task is an activity that has a beginning and an end. Project plans are made up of tasks.


## Thread safety

Any public  **static** ( **Shared** in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.
## See also


#### Reference


[Task members](67472f2a-fe15-2678-efed-45c0af54dace.md)
[Microsoft.ProjectServer.Client namespace](e79057b8-4161-453c-1035-02e38725305c.md)
