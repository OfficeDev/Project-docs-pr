
# PublishedAssignment
Represents an assignment in a published project.

## Members

The members consist of the properties defined for the PublishedAssignment object and those inherited from the Assignment object. 

Three different interfaces are available:

* CSOM - client-side library providing support for .NET applications
* JSOM - JavaScript object model library that provides support for AddIn development
* REST - HTTP command-based interface that provides language-agnostic functionality

The table identifies the properties used in each library. Each entry includes the property names, the data type, and a description. 

### Methods

The  **PublishedAssignment** object has no methods.

### Properties

The  **PublishedAssignment** object has the following properties:

|**CSOM** |**JSOM (get_, set_)** |**REST** |**Data Type CSOM**|**Description**|
|:----- |:-----|:-----|:-----|:-----|
|[ActualCost](743c1229-3626-e142-0470-39d0bffbc7bf.md) #|[ActualCost](06450ca6-07de-38b2-18d9-3a4a911e26c0.md) #|[ActualCost](06450ca6-07de-38b2-18d9-3a4a911e26c0.md) #|Double (64-bit)|Gets the costs incurred for work already performed on the assignment, together with any other recorded costs that are associated with the assignment.|
|[ActualCostWorkPerformed](20bd7be5-bd04-835a-d034-2480a57be2d1.md) #|[ActualCostWorkPerformed](2ff40b76-7bba-a807-1e29-af3f2e78a2bf.md) #|[ActualCostWorkPerformed](2ff40b76-7bba-a807-1e29-af3f2e78a2bf.md) #|Double (64-bit)|Gets the actual cost of work performed (ACWP) for the assignment to date.|
|[ActualFinish](3fa8263f-5a5c-6e35-b673-887361c182a9.md) #|[ActualFinish](e83c6904-a5e2-972e-df80-2929f29d83b6.md) #|[ActualFinish](e83c6904-a5e2-972e-df80-2929f29d83b6.md) #|DateTime|Gets the date and time when the assignment is complete.|
|[ActualOvertimeCost](1742b77a-222c-8fdb-f67f-22b63b545c4f.md) #|[ActualOvertimeCost](0ffa3473-01e1-bc21-96ac-3dab80a89824.md) #|[ActualOvertimeCost](0ffa3473-01e1-bc21-96ac-3dab80a89824.md) #|Double (64-bit)|Gets the actual overtime cost for the assignment.|
|[ActualOvertimeWork](768e46c5-afb4-cfea-faee-c5e8f732e849.md) #|[ActualOvertimeWork](04825a6d-767f-635e-17d1-2320e575a497.md) #|[ActualOvertimeWork](04825a6d-767f-635e-17d1-2320e575a497.md) #|String|Gets the actual amount of overtime work that has already been performed on the assignment.|
| |[ActualOvertimeWorkMilliseconds](93a8a2be-f968-854b-281d-e515235d176f.md) #|[ActualOvertimeWorkMilliseconds](93a8a2be-f968-854b-281d-e515235d176f.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the actual amount of overtime work that has already been performed on the assignment.|
|[ActualOvertimeWorkTimeSpan](405a54b8-bbba-88f2-437e-f423ec92d4bf.md) #| | |TimeSpan|Gets the time interval for the actual amount of overtime work that has already been performed on the assignment.|
|[ActualStart](34c5aa8d-8087-258e-a4a3-df2a41838808.md) #|[ActualStart](5cf4260a-3a8d-54a2-de37-d05fac574aba.md) #|[ActualStart](5cf4260a-3a8d-54a2-de37-d05fac574aba.md) #|DateTime|Gets the date and time that the assignment actually began, based on progress information that was entered.|
|[ActualWork](ff6f8c46-5dcc-7a30-8fa1-3964bb3683c8.md) #|[ActualWork](23979f26-3ad8-aeb7-82ad-745fb393809e.md) #|[ActualWork](23979f26-3ad8-aeb7-82ad-745fb393809e.md) #|String|Gets the amount of work that has already been performed on the assignment.|
| |[ActualWorkMilliseconds](e3d16ae1-e5f1-4087-5a47-dfa01db14509.md) #|[ActualWorkMilliseconds](e3d16ae1-e5f1-4087-5a47-dfa01db14509.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of work that has already been performed on the assignment.|
|[ActualWorkTimeSpan](ff0675eb-3fd6-b8cf-1566-2f6c93d66265.md) #| | |TimeSpan|Gets the time interval for the amount of work that has already been performed on the assignment.|
|[BaselineCost](b11e9208-88ee-a69d-056e-45366c1c44bf.md) #|[BaselineCost](1b58f18b-9c60-a418-6af5-8bcdc2c68b40.md) #|[BaselineCost](1b58f18b-9c60-a418-6af5-8bcdc2c68b40.md) #|Double (64-bit)|Gets the total planned costs of the assignment.|
|[BaselineCostPerUse](4872fa8a-dec5-58d2-e5db-d6e2ca096f7b.md) #|[BaselineCostPerUse](c025c136-3d14-69e7-60b2-0f69f3a4cd31.md) #|[BaselineCostPerUse](c025c136-3d14-69e7-60b2-0f69f3a4cd31.md) #|Double (64-bit)|Gets the cost per use of a resource on an assignment, at the time of the project baseline.|
|[BaselineFinish](3aaad609-d199-1bad-9f26-855e3317d245.md) #|[BaselineFinish](62b59f16-dc44-64b9-0aee-d173212db545.md) #|[BaselineFinish](62b59f16-dc44-64b9-0aee-d173212db545.md) #|DateTime|Gets the planned completion date for an assignment, at the time of the project baseline.|
|[BaselineStart](19a65a0a-9a2f-261a-a5f4-a23b66b0431a.md) #|[BaselineStart](f9f0fb3a-cd1c-384e-eaeb-bf0548001c57.md) #|[BaselineStart](f9f0fb3a-cd1c-384e-eaeb-bf0548001c57.md) #|DateTime|Gets the planned start date for an assignment, at the time of the project baseline.|
|[BaselineWork](bb5de47f-f672-028e-3433-2e3f818af4b7.md) #|[BaselineWork](01060ea3-024f-ee36-c477-94001663319d.md) #|[BaselineWork](01060ea3-024f-ee36-c477-94001663319d.md) #|String|Gets total planned person-hours scheduled for an assignment, at the time of the project baseline.|
| |[BaselineWorkMilliseconds](0e310335-f96b-6d40-1964-f4ac1dc886e0.md) #|[BaselineWorkMilliseconds](0e310335-f96b-6d40-1964-f4ac1dc886e0.md) #|Double (64-bit)|Gets the total time interval, expressed in milliseconds, of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|[BaselineWorkTimeSpan](5c6f8698-c27d-f43c-f82a-fe288b2ecede.md) #| | |TimeSpan|Gets the total time interval of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|[BudgetedCost](b31f2f27-09ed-0323-eed2-c97c2ba5ed1d.md) #|[BudgetedCost](e050e0a6-4969-92d0-8864-ed78f8971428.md) #|[BudgetedCost](e050e0a6-4969-92d0-8864-ed78f8971428.md) #|Double (64-bit)|Gets the budgeted cost for the assignment.|
|[BudgetedCostWorkPerformed](b3f241b1-a21a-81c6-3e20-4ce1bf973e05.md) #|[BudgetedCostWorkPerformed](89ad9647-082b-ff9e-763f-1a3ac988de78.md) #|[BudgetedCostWorkPerformed](89ad9647-082b-ff9e-763f-1a3ac988de78.md) #|Double (64-bit)|Gets the budgeted cost of work performed (BCWP).|
|[BudgetedCostWorkScheduled](76fd4958-cd03-c0e1-d385-6c0ad285ad1d.md) #|[BudgetedCostWorkScheduled](71f0c1cd-9808-83ad-e8f9-d6d9e41ff372.md) #|[BudgetedCostWorkScheduled](71f0c1cd-9808-83ad-e8f9-d6d9e41ff372.md) #|Double (64-bit)|Gets the budgeted cost of work scheduled (BCWS) for the assignment.|
|[BudgetedWork](350c239a-edea-4512-6a26-be1898be74fb.md) #|[BudgetedWork](d3e6eed3-97a1-b3c1-9873-5977825b0c61.md) #|[BudgetedWork](d3e6eed3-97a1-b3c1-9873-5977825b0c61.md) #|String|Gets the budgeted work for the assignment.|
| |[BudgetedWorkMilliseconds](906c971f-5e3b-63bc-6570-152fccc5ff1a.md) #|[BudgetedWorkMilliseconds](906c971f-5e3b-63bc-6570-152fccc5ff1a.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the budgeted work for the assignment.|
|[BudgetedWorkTimeSpan](9b15a265-0ea8-ed0e-cd9b-f68b375692d0.md) #| | |TimeSpan|Gets the time interval for the budgeted work for the assignment.|
|[Cost](8612d798-3320-452d-eb9f-878302c1eedc.md) #|[Cost](73f52b34-af59-6ef5-cb64-0cbadd5ebed1.md) #|[Cost](73f52b34-af59-6ef5-cb64-0cbadd5ebed1.md) #|Double (64-bit)|Gets the total scheduled or projected cost for the assignment.|
|[CostVariance](7db7d477-6b6a-1f79-4eba-967ba00ef059.md) #|[CostVariance](3fbaf2be-2cf9-085d-ae05-806dcacf0674.md) #|[CostVariance](3fbaf2be-2cf9-085d-ae05-806dcacf0674.md) #|Double (64-bit)|Gets the cost variance (CV), which is the difference between the baseline cost and the total cost of the assignment.|
|[CostVarianceAtCompletion](b0172706-800d-8509-37b8-5a899d651f98.md) #|[CostVarianceAtCompletion](e51869dc-a328-0449-9b55-2b192d5b4d2e.md) #|[CostVarianceAtCompletion](e51869dc-a328-0449-9b55-2b192d5b4d2e.md) #|Double (64-bit)|Gets the cost variance at completion (VAC) for the assignment.|
|[Created](d9f3b673-3928-90fb-1f04-29af65bd305d.md) #|[Created](99c639c8-4293-fca8-e5a9-99e60c63bc06.md) #|[Created](99c639c8-4293-fca8-e5a9-99e60c63bc06.md) #|DateTime|Gets the date when the assignment was created.|
|[CurrentCostVariance](8cb4222f-355d-e175-efa6-5b9e6e32a255.md) #|[CurrentCostVariance](238dc3e5-9cfa-87bb-0679-a96127a6ac20.md) #|[CurrentCostVariance](238dc3e5-9cfa-87bb-0679-a96127a6ac20.md) #|Double (64-bit)|Gets the current cost variance (CV).|
|[CustomFields](3e31709d-0c1d-d94e-cb48-98910fbb6cc0.md) #|[CustomFields](71d2027b-c5b2-898a-4f25-dc8b3abcbbb8.md) #|[CustomFields](71d2027b-c5b2-898a-4f25-dc8b3abcbbb8.md) #|[CustomFieldCollection](39c70b02-09d2-d60e-94d9-ea538846124a.md)|Gets the collection of custom fields for the assignment.|
|[DefaultBookingType](d1dbf6c5-87b8-762c-0cf2-c8263a8f9b8f.md) #|[DefaultBookingType](1cb50a90-e4d0-3624-41a4-9da572651181.md) #|[DefaultBookingType](1cb50a90-e4d0-3624-41a4-9da572651181.md) #|BookingType  (enum)|Gets the default booking type for the assignment.|
|[Delay](adbaa743-ac1c-88cb-f55d-f8f75333fd6a.md) #|[Delay](ba14196f-78ec-425f-055b-760e7861abd3.md) #|[Delay](ba14196f-78ec-425f-055b-760e7861abd3.md) #|String|Gets the amount of time that passes after the start date, before work on the assignment starts.|
| |[DelayMilliseconds](d485b88c-c199-b30d-92dd-e8595732d2a3.md) #|[DelayMilliseconds](d485b88c-c199-b30d-92dd-e8595732d2a3.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of time that passes after the start date, before work on the assignment starts.|
|[DelayTimeSpan](34effc7f-a6d2-ce66-25e1-ac5c3940a661.md) #| | |TimeSpan|Gets the time interval for the amount of time that passes after the start date, before work on the assignment starts.|
|[FieldValues](20584225-4b74-2d1f-9af0-96e98b24140f.md) #|[FieldValues](30bb3625-bb08-043c-e673-bbacc3c88fa9.md) #|[FieldValues](30bb3625-bb08-043c-e673-bbacc3c88fa9.md) #|Dictionary<string,object>|Gets the collection of custom fields that have values set for the assignment.|
|[Finish](4e74ac93-23ac-b2ed-fc5e-86acd13ab57b.md) #|[Finish](30e87425-cc7b-a449-75c5-08956132492b.md) #|[Finish](30e87425-cc7b-a449-75c5-08956132492b.md) #|DateTime|Gets the date when the assignment is scheduled to be completed.|
|[FinishVariance](544c5b57-6dd7-5f5f-a30c-1b48d7806e58.md) #|[FinishVariance](83e6b7a2-7988-5fc2-3d91-89fb0514811f.md) #|[FinishVariance](83e6b7a2-7988-5fc2-3d91-89fb0514811f.md) #|String|Gets the variance of the finish date of the assignment.|
| |[FinishVarianceMilliseconds](b12222bb-2b4a-19f6-3824-88cd821c7a26.md) #|[FinishVarianceMilliseconds](b12222bb-2b4a-19f6-3824-88cd821c7a26.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the variance of the finish date of the assignment.|
|[FinishVarianceTimeSpan](5d3073be-b808-6f71-a983-b7237613faee.md) #| | |TimeSpan|Gets the time interval for the variance of the finish date of the assignment.|
|[Id](2dcafd99-b3d5-4987-ec50-92c55ff05e9f.md) #|[Id](5dffe615-e608-a684-60e4-210d34834b4d.md) #|[Id](5dffe615-e608-a684-60e4-210d34834b4d.md) #|Guid|Gets the GUID of the assignment.|
|[IsConfirmed](aa9d63f4-c1fd-b825-b6f6-7bd771a910ad.md) #|[IsConfirmed](0fead0ec-d196-4d8f-aecd-b7c23690c19d.md) #|[IsConfirmed](0fead0ec-d196-4d8f-aecd-b7c23690c19d.md) #|Boolean|Gets a value that shows whether the resource has accepted the assignment.|
|[IsLockedByManager](c7e9d77a-b124-88a2-dc0e-f79f8462ca68.md) #|[IsLockedByManager](83057e4d-4835-d28a-d526-7d77cb346e48.md) #|[IsLockedByManager](83057e4d-4835-d28a-d526-7d77cb346e48.md) #|Boolean|Gets a value that indicates whether the assignment has been locked for changes by a manager.|
|[IsOverAllocated](4dc7d559-d70d-a1fb-497f-77b5a902b969.md) #|[IsOverAllocated](b5262211-9a6e-fa85-bddf-5dd99f4daf41.md) #|[IsOverAllocated](b5262211-9a6e-fa85-bddf-5dd99f4daf41.md) #|Boolean|Gets a value that indicates whether the resource is overallocated during the time of the assignment.|
|[IsPublished](d22861ce-5931-1aab-0b7b-551a2040cdf4.md) #|[IsPublished](650ab8d0-d8a9-4905-9b94-0d6237482152.md) #|[IsPublished](650ab8d0-d8a9-4905-9b94-0d6237482152.md) #|Boolean|Gets a value that indicates whether the assignment is published.|
|[IsResponsePending](689979a1-fa7b-8a9e-49c9-5d13c45a53d7.md) #|[IsResponsePending](6bb23b39-1230-4317-ac4f-f507c7b93164.md) #|[IsResponsePending](6bb23b39-1230-4317-ac4f-f507c7b93164.md) #|Boolean|Gets a value that shows whether the assignment update has been sent to the resource.|
|[IsUpdateNeeded](3b8109a7-21a8-b2bd-c136-2444522173ba.md) #|[IsUpdateNeeded](5eec16d8-99fc-a33b-ab63-e0835fa053f1.md) #|[IsUpdateNeeded](5eec16d8-99fc-a33b-ab63-e0835fa053f1.md) #|Boolean|Gets a value that indicates whether an assignment update should be sent to the resource.|
|[IsWorkResource](4b31a6a6-b8b5-31de-bf2d-672592bee087.md) #|[IsWorkResource](e864a3fe-2fa5-ffb6-096a-fe93a9e2731f.md) #|[IsWorkResource](e864a3fe-2fa5-ffb6-096a-fe93a9e2731f.md) #|Boolean|Gets a value that indicates whether an assignment resource is a work resource or a material resource.|
|[Item](6624141a-0b8f-dbec-4f63-ece09cb9d476.md) #|[Item](265be3f0-6b11-f261-4edd-e208ff3c9a23.md) #|[Item](265be3f0-6b11-f261-4edd-e208ff3c9a23.md) #|Object|Gets an item in the project.|
|[LevelingDelay](88e315c8-3635-8a6c-f306-58b74d3a5279.md) #|[LevelingDelay](08996e06-dfa4-bf9e-c8b6-88feedcf4eed.md) #|[LevelingDelay](08996e06-dfa4-bf9e-c8b6-88feedcf4eed.md) #|String|Gets the amount of time that resource leveling can delay the assignment from its early start date.|
| |[LevelingDelayMilliseconds](674b7c33-2d7a-da70-2c8f-68c36a354983.md) #|[LevelingDelayMilliseconds](674b7c33-2d7a-da70-2c8f-68c36a354983.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of time that resource leveling can delay the assignment from its early start date.|
|[LevelingDelayTimeSpan](8d75c0b3-5cd7-2981-c9d1-f71ca730f414.md) #| | |TimeSpan|Gets the time interval for the amount of time that resource leveling can delay the assignment from its early start date.|
|[Modified](e7843816-4c49-8cc2-ff1c-8f57f47ff163.md) #|[Modified](c10dd65b-1db1-436c-efd1-145aa67d6036.md) #|[Modified](c10dd65b-1db1-436c-efd1-145aa67d6036.md) #|DateTime|Gets the date when the assignment was modified.|
|[Notes](848abe2e-bf2d-31e0-00fc-ed6b01dee211.md) #|[Notes](7aaaa949-7875-843e-524e-d6390416b073.md) #|[Notes](7aaaa949-7875-843e-524e-d6390416b073.md) #|String|Gets comments that were entered about the assignment.|
|[OvertimeCost](d59ac9ed-94f7-05ec-8ee8-795e9065202d.md) #|[OvertimeCost](d4964e48-6180-3ebf-e438-d580caf426cb.md) #|[OvertimeCost](d4964e48-6180-3ebf-e438-d580caf426cb.md) #|Double (64-bit)|Gets the total overtime cost of the assignment.|
|[OvertimeWork](6a3a87c0-b4ea-c8fa-341a-e30ac18a33ea.md) #|[OvertimeWork](37997325-5c8d-e168-9a40-7efa4e350e93.md) #|[OvertimeWork](37997325-5c8d-e168-9a40-7efa4e350e93.md) #|String|Gets the amount of overtime that is scheduled to be performed on the assignment.|
| |[OvertimeWorkMilliseconds](56bb9ef7-49c3-3cf3-e967-05c8bc4d7ff2.md) #|[OvertimeWorkMilliseconds](56bb9ef7-49c3-3cf3-e967-05c8bc4d7ff2.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of overtime that is scheduled to be performed on the assignment.|
|[OvertimeWorkTimeSpan](697a1a96-9ec6-be79-be5c-8d413375e811.md) #| | |TimeSpan|Gets the time interval for the amount of overtime that is scheduled to be performed on the assignment.|
|[Owner](eda79374-038c-b120-d878-6efe0b6189a0.md) #|[Owner](9c103f45-2a0e-ff34-9a81-ecc4e366a362.md) #|[Owner](9c103f45-2a0e-ff34-9a81-ecc4e366a362.md) #|User (SP)|Gets the name of the user who is responsible for entering status for the current assignment.|
|[Parent](aec1b00c-1b7a-1ffa-c9e4-52772487bc03.md) #|[Parent](1df25234-7c9e-2dd2-fe29-508eee6d20c5.md) #|[Parent](1df25234-7c9e-2dd2-fe29-508eee6d20c5.md) #|[PublishedAssignment](6721899e-a1de-eb24-6f68-85476f368612.md)|Gets the parent assignment link.|
|[PercentWorkComplete](ed257a54-787e-2465-4d6e-8e5d2266a472.md) #|[PercentWorkComplete](d87c654f-26fe-83ee-c8a7-080dce0efc22.md) #|[PercentWorkComplete](d87c654f-26fe-83ee-c8a7-080dce0efc22.md) #|int32|Gets the current status of the assignment, expressed as the percentage of the total work that has been completed.|
|[RegularWork](8a43376f-706b-47c1-70d5-401ae2b0c1fe.md) #|[RegularWork](b781d7d4-3a79-0148-9765-5d96ac74a2a0.md) #|[RegularWork](b781d7d4-3a79-0148-9765-5d96ac74a2a0.md) #|String|Gets the total amount of nonovertime work that is scheduled to be performed on the assignment.|
| |[RegularWorkMilliseconds](7efa473f-a36d-e110-87f3-32b39a7a3632.md) #|[RegularWorkMilliseconds](7efa473f-a36d-e110-87f3-32b39a7a3632.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|[RegularWorkTimeSpan](92258507-9c49-019b-1860-bccf176773bc.md) #| | |TimeSpan|Gets the time interval for the total amount of nonovertime work that is scheduled to be performed on the assignment.|
|[RemainingCost](ba732b6b-2c34-1b4f-cc09-e79c74c2da93.md) #|[RemainingCost](698ff7c4-87fa-e170-06c3-68eb117e0049.md) #|[RemainingCost](698ff7c4-87fa-e170-06c3-68eb117e0049.md) #|Double (64-bit)|Gets the total remaining cost of the assignment, as scheduled.|
|[RemainingOvertimeCost](c218a16a-6811-8750-b2d1-6090be178d19.md) #|[RemainingOvertimeCost](d3a504b5-46fe-bbed-365f-44d84e182ced.md) #|[RemainingOvertimeCost](d3a504b5-46fe-bbed-365f-44d84e182ced.md) #|Double (64-bit)|Gets the scheduled remaining overtime cost of the assignment.|
|[RemainingOvertimeWork](41e4c577-fe31-ca1b-c730-7d4633eee929.md) #|[RemainingOvertimeWork](eaf8e297-a56b-91a7-32a4-b2f3579e42b1.md) #|[RemainingOvertimeWork](eaf8e297-a56b-91a7-32a4-b2f3579e42b1.md) #|String|Gets the amount of remaining scheduled overtime work on the assignment.|
| |[RemainingOvertimeWorkMilliseconds](b0af0c04-3e70-2ffe-cfdf-76f5fd636f9f.md) #|[RemainingOvertimeWorkMilliseconds](b0af0c04-3e70-2ffe-cfdf-76f5fd636f9f.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of remaining scheduled overtime work on the assignment.|
|[RemainingOvertimeWorkTimeSpan](12ea6d5a-2bb1-d020-fac4-719d1af072c5.md) #| | |TimeSpan|Gets the time interval for the amount of remaining scheduled overtime work on the assignment.|
|[RemainingWork](51e23282-5ce5-a0a9-d6db-a4eb74c0e5de.md) #|[RemainingWork](e30ee965-d95d-2fec-5914-df2b834a537c.md) #|[RemainingWork](e30ee965-d95d-2fec-5914-df2b834a537c.md) #|String|Gets the time, such as person-hours or days, that is still required to complete the assignment.|
| |[RemainingWorkMilliseconds](2d3086fa-0564-3137-60c7-259adc5bd5e5.md) #|[RemainingWorkMilliseconds](2d3086fa-0564-3137-60c7-259adc5bd5e5.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds,  for the time that is still required to complete the assignment.|
|[RemainingWorkTimeSpan](4e06e0a7-18ce-466d-e34f-e4c957e671e8.md) #| | |TimeSpan|Gets the time interval for the time, such as person-hours or days, that is still required to complete the assignment.|
|[Resource](3bc99b67-745e-580a-9fb6-77745c81ee3e.md) #|[Resource](8fdffcf7-01ee-4959-03e4-122f99ec1588.md) #|[Resource](8fdffcf7-01ee-4959-03e4-122f99ec1588.md) #|[PublishedProjectResource](f94fdcd0-a37c-ca43-4fcb-92a515bf23e6.md)|Gets the resource that is associated with the assignment.|
|[ResourceCapacity](1d2dd52a-fb55-94b4-d1af-3a231530ea51.md) #|[ResourceCapacity](1dc02e80-aa1e-2164-b42e-68d0b7039e35.md) #|[ResourceCapacity](1dc02e80-aa1e-2164-b42e-68d0b7039e35.md) #|Double (64-bit)|Gets how much work the resource performs on the assignment, expressed as a percentage of the resource's theoretical full capacity.|
|[Resume](6fe198cb-0c01-ca6f-dddb-a8575deb2c38.md) #|[Resume](f0156892-d4f4-8903-8df0-4334736bff2b.md) #|[Resume](f0156892-d4f4-8903-8df0-4334736bff2b.md) #|DateTime|Gets the date and time when a resource resumes work on the assignment.|
|[ScheduleCostVariance](5a7ca83a-0b6b-4582-246b-001671bcc00a.md) #|[ScheduleCostVariance](6f711a63-8f14-1871-970e-1ec8a343290b.md) #|[ScheduleCostVariance](6f711a63-8f14-1871-970e-1ec8a343290b.md) #|Double (64-bit)|Gets the schedule cost variance (CV), which is the difference between the baseline cost and the scheduled cost of the assignment.|
|[Start](5a56cff8-77b2-9f0f-64f6-7d233b252a1b.md) #|[Start](e67ed0fa-dd3f-18eb-93c3-dd9f3f417255.md) #|[Start](e67ed0fa-dd3f-18eb-93c3-dd9f3f417255.md) #|DateTime|Gets the date and time that a resource is scheduled to start the assignment.|
|[StartVariance](8d958a46-2501-3f9c-e290-e43b4f30ed0b.md) #|[StartVariance](c3ce7350-3fe4-fb07-543c-7881e8ff5d9d.md) #|[StartVariance](c3ce7350-3fe4-fb07-543c-7881e8ff5d9d.md) #|String|Gets the variance of the assignment start date.|
| |[StartVarianceMilliseconds](07b9eb78-d599-a33e-59c1-475e8b8a38a3.md) #|[StartVarianceMilliseconds](07b9eb78-d599-a33e-59c1-475e8b8a38a3.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the variance of the assignment start date.|
|[StartVarianceTimeSpan](f7164618-d53c-888f-f6e5-46072971f24a.md) #| | |TimeSpan|Gets the time interval for the variance of the assignment start date.|
|[Stop](a36eea49-bab3-6d83-0743-04119976d5f2.md) #|[Stop](e5d5b420-8b13-9625-1c2e-ab1d64b7f5a9.md) #|[Stop](e5d5b420-8b13-9625-1c2e-ab1d64b7f5a9.md) #|DateTime|Gets the date and time when a resource stops work on the assignment.|
|[Task](264a1825-92a2-6a18-998e-dc533aacef77.md) #|[Task](dfcdd671-f340-136e-88ec-76efb2a3d977.md) #|[Task](dfcdd671-f340-136e-88ec-76efb2a3d977.md) #|PublishedTask|Gets the task to which the assignment belongs.|
|[Work](e94d6018-e5ac-c273-d0a1-ce4371422166.md) #|[Work](0ba4ac47-da2d-6c71-c1a3-4b81c02a8be4.md) #|[Work](0ba4ac47-da2d-6c71-c1a3-4b81c02a8be4.md) #|String|Gets the total amount of time that is scheduled for the assignment.|
|WorkContourType #|WorkContourType #|WorkContourType #|WorkContourType||
| |[WorkMilliseconds](9d2cc7da-2957-7883-fede-33abe5d801d9.md) #|[WorkMilliseconds](9d2cc7da-2957-7883-fede-33abe5d801d9.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the total amount of time that is scheduled for the assignment.|
|[WorkTimeSpan](0ebc0791-e293-d898-dac8-2fd58d7273f1.md) #| | |TimeSpan|Gets the time interval for the total amount of time that is scheduled for the assignment.|
|[WorkVariance](60711093-d850-a8ce-3169-fb4b00590130.md) #|[WorkVariance](413a9e0d-7b46-c263-f5e8-6d33be7ce83f.md) #|[WorkVariance](413a9e0d-7b46-c263-f5e8-6d33be7ce83f.md) #|String|Gets the difference between baseline work and currently scheduled work on the assignment.|
| |[WorkVarianceMilliseconds](59f6985d-2c37-5deb-1fbe-f734b76db496.md) #|[WorkVarianceMilliseconds](59f6985d-2c37-5deb-1fbe-f734b76db496.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the difference between baseline work and currently scheduled work on the assignment.|
|[WorkVarianceTimeSpan](32bc05f8-60c9-661e-c15c-4de34d2777fa.md) #| | |TimeSpan|Gets the time interval for the difference between baseline work and currently scheduled work on the assignment.|


  **Note on Symbol Usage:**  
  * - indicates a new method or property.<br />
  # - indicates Read access to a property.<br />
  $ - indicated Write access to a property.


## Syntax

### CSOM Library

The CSOM .NET library used for client-side applications. The class declaration for PublishedAssignment follows.

```C#
Public Class PublishedAssignment _
	Inherits Assignment
```

#### Inheritance hierarchy

[System.Object](http://msdn2.microsoft.com/EN-US/library/e5kfa45b)<br />
[Microsoft.SharePoint.Client.ClientObject](http://msdn2.microsoft.com/EN-US/library/ee540788)<br />
==>[Microsoft.ProjectServer.Client.Assignment](762a3d4f-5167-b95d-1d4f-c61a3a893c54.md)<br />
==>Microsoft.ProjectServer.Client.PublishedAssignment

**Namespace:**[Microsoft.ProjectServer.Client](e79057b8-4161-453c-1035-02e38725305c.md) 

**Assembly:**Microsoft.ProjectServer.Client (in Microsoft.ProjectServer.Client.dll)



### JSOM Library

The JSOM library is used for AddIns and is written in JavaScript. The declaration for the PublishedAssignment object follows:
```
PS.PublishedAssignment
```

### REST Interface

The 

<a name="restresourceendpoint"> </a>

#### Endpoint URI structure
<a name="endpointuristructure"> </a>


```
http://<sitecollection> /<site> /_api/ProjectServer/PublishedAssignment('assignmentid')
```


#### HTTP requests
<a name="httprequests"> </a>

This resource supports the following HTTP commands:


- [GET](a2431b86-5e45-b4f5-dfb7-77145e3ac930.md#getsyntax)
    
- [DELETE](a2431b86-5e45-b4f5-dfb7-77145e3ac930.md#deletesyntax)
    

#### GET syntax
<a name="getsyntax"> </a>


```
GET http://<sitecollection> /<site> /_api/ProjectServer/PublishedAssignment('assignmentid')
```


#### DELETE syntax
<a name="deletesyntax"> </a>


```
DELETE http://<sitecollection> /<site> /_api/ProjectServer/PublishedAssignment('assignmentid')
```

## Thread safety

Any public  **static** ( **Shared** in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.
## See also


## Remarks




## Thread safety

Any public  **static** ( **Shared** in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.


#### Reference


[PublishedAssignment members](dc3359bf-d77c-ba89-5880-10f07191777c.md)<br />
[Microsoft.ProjectServer.Client namespace](e79057b8-4161-453c-1035-02e38725305c.md)<br />
[Assignment](762a3d4f-5167-b95d-1d4f-c61a3a893c54.md)<br />
[PublishedAssignmentCollection](e08e5c0b-4eb9-b668-2866-74c7429b47f3.md)<br />
[DraftAssignment](3a362ea3-8aa7-6ada-f6ff-4b93bed2b8b8.md)<br />
[DraftAssignmentCollection](eaee2ac5-8c39-1bbd-ee28-1270d6c3e82e.md)<br />
[AssignmentCreationInformation](06c6694b-dbde-7e6c-5376-853bac972b1c.md)

