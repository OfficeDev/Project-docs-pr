
# Assignment class
Contains inheritable properties common to draft and published assignments.

## Members

The members consist of the properties defined for the Assignment object. 

Three different interfaces are available:

* CSOM - client-side library providing support for .NET applications
* JSOM - JavaScript object model library that provides support for AddIn development
* REST - HTTP command-based interface that provides language-agnostic functionality

The table for properties identifies the each property by the name used in each library, the data type of the exchanged value or entity, and a description of the property. 

### Methods

The **Assignment** object has no methods.


### Properties

The **Assignment** object has the following properties:

|**CSOM** |**JSOM (get, set)** |**REST** |**Data Type**|**Description**|
|:----- |:----- |:----- |:-----|:-----|
|[ActualCostWorkPerformed](20bd7be5-bd04-835a-d034-2480a57be2d1.md) #|[ActualCostWorkPerformed](2ff40b76-7bba-a807-1e29-af3f2e78a2bf.md) #|[ActualCostWorkPerformed](2ff40b76-7bba-a807-1e29-af3f2e78a2bf.md) #|Double (64-bit)|Gets the actual cost of work performed (ACWP) for the assignment to date.|
|[ActualOvertimeCost](1742b77a-222c-8fdb-f67f-22b63b545c4f.md) #|[ActualOvertimeCost](0ffa3473-01e1-bc21-96ac-3dab80a89824.md) #|[ActualOvertimeCost](0ffa3473-01e1-bc21-96ac-3dab80a89824.md) #|Double (64-bit)|Gets the actual overtime cost for the assignment.|
|[BaselineCost](b11e9208-88ee-a69d-056e-45366c1c44bf.md) #|[BaselineCost](1b58f18b-9c60-a418-6af5-8bcdc2c68b40.md) #|[BaselineCost](1b58f18b-9c60-a418-6af5-8bcdc2c68b40.md) #|Double (64-bit)|Gets the total planned costs of the assignment.|
|[BaselineCostPerUse](4872fa8a-dec5-58d2-e5db-d6e2ca096f7b.md) #|[BaselineCostPerUse](c025c136-3d14-69e7-60b2-0f69f3a4cd31.md) #|[BaselineCostPerUse](c025c136-3d14-69e7-60b2-0f69f3a4cd31.md) #|Double (64-bit)|Gets the cost per use of a resource on an assignment, at the time of the project baseline.|
|[BaselineFinish](3aaad609-d199-1bad-9f26-855e3317d245.md) #|[BaselineFinish](62b59f16-dc44-64b9-0aee-d173212db545.md) #|[BaselineFinish](62b59f16-dc44-64b9-0aee-d173212db545.md) #|DateTime|Gets the planned completion date for an assignment, at the time of the project baseline.|
|[BaselineStart](19a65a0a-9a2f-261a-a5f4-a23b66b0431a.md) #|[BaselineStart](f9f0fb3a-cd1c-384e-eaeb-bf0548001c57.md) #|[BaselineStart](f9f0fb3a-cd1c-384e-eaeb-bf0548001c57.md) #|DateTime|Gets the planned start date for an assignment, at the time of the project baseline.|
|[BaselineWork](bb5de47f-f672-028e-3433-2e3f818af4b7.md) #|[BaselineWork](01060ea3-024f-ee36-c477-94001663319d.md) #|[BaselineWork](01060ea3-024f-ee36-c477-94001663319d.md) #|String|Gets total planned person-hours scheduled for an assignment, at the time of the project baseline.|
| |[BaselineWorkMilliseconds](0e310335-f96b-6d40-1964-f4ac1dc886e0.md) #|[BaselineWorkMilliseconds](0e310335-f96b-6d40-1964-f4ac1dc886e0.md) #|Double (64-bit)|Gets the total time interval, expressed in milliseconds, of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|[BaselineWorkTimeSpan](5c6f8698-c27d-f43c-f82a-fe288b2ecede.md) #| | |TimeSpan|Gets the total time interval of planned person-hours scheduled for an assignment, at the time of the project baseline.|
|[BudgetedCostWorkPerformed](b3f241b1-a21a-81c6-3e20-4ce1bf973e05.md) #|[BudgetedCostWorkPerformed](89ad9647-082b-ff9e-763f-1a3ac988de78.md) #|[BudgetedCostWorkPerformed](89ad9647-082b-ff9e-763f-1a3ac988de78.md) #|Double (64-bit)|Gets the budgeted cost of work performed (BCWP).|
|[BudgetedCostWorkScheduled](76fd4958-cd03-c0e1-d385-6c0ad285ad1d.md) #|[BudgetedCostWorkScheduled](71f0c1cd-9808-83ad-e8f9-d6d9e41ff372.md) #|[BudgetedCostWorkScheduled](71f0c1cd-9808-83ad-e8f9-d6d9e41ff372.md) #|Double (64-bit)|Gets the budgeted cost of work scheduled (BCWS) for the assignment.|
|[CostVariance](7db7d477-6b6a-1f79-4eba-967ba00ef059.md) #|[CostVariance](3fbaf2be-2cf9-085d-ae05-806dcacf0674.md) #|[CostVariance](3fbaf2be-2cf9-085d-ae05-806dcacf0674.md) #|Double (64-bit)|Gets the cost variance (CV), which is the difference between the baseline cost and the total cost of the assignment.|
|[CostVarianceAtCompletion](b0172706-800d-8509-37b8-5a899d651f98.md) #|[CostVarianceAtCompletion](e51869dc-a328-0449-9b55-2b192d5b4d2e.md) #|[CostVarianceAtCompletion](e51869dc-a328-0449-9b55-2b192d5b4d2e.md) #|Double (64-bit)|Gets the cost variance at completion (VAC) for the assignment.|
|[Created](d9f3b673-3928-90fb-1f04-29af65bd305d.md) #|[Created](99c639c8-4293-fca8-e5a9-99e60c63bc06.md) #|[Created](99c639c8-4293-fca8-e5a9-99e60c63bc06.md) #|DateTime|Gets the date when the assignment was created.|
|[CurrentCostVariance](8cb4222f-355d-e175-efa6-5b9e6e32a255.md) #|[CurrentCostVariance](238dc3e5-9cfa-87bb-0679-a96127a6ac20.md) #|[CurrentCostVariance](238dc3e5-9cfa-87bb-0679-a96127a6ac20.md) #|Double (64-bit)|Gets the current cost variance (CV).|
|[CustomFields](3e31709d-0c1d-d94e-cb48-98910fbb6cc0.md) #|[CustomFields](71d2027b-c5b2-898a-4f25-dc8b3abcbbb8.md) #|[CustomFields](71d2027b-c5b2-898a-4f25-dc8b3abcbbb8.md) #|[CustomFieldCollection](39c70b02-09d2-d60e-94d9-ea538846124a.md)|Gets the collection of custom fields for the assignment.|
|[Delay](dcf77784-a005-619a-2654-b86f0dc868e0.md) *,#|[Delay](77695c1e-6ae9-d3eb-16e1-e94492954521.md) *,#|[Delay](77695c1e-6ae9-d3eb-16e1-e94492954521.md) *,#|String|Gets the amount of time that passes after the start date, before work on the assignment starts.|
| |[DelayMilliseconds](40559863-93da-fb05-d86f-9dbdf13d17e4.md) *,#|[DelayMilliseconds](40559863-93da-fb05-d86f-9dbdf13d17e4.md) *,#|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of time that passes after the start date, before work on the assignment starts.|
|[DelayTimeSpan](09f4eb5a-898b-f636-309f-5ea8c5ea3644.md) *,#| | |TimeSpan|Gets the time interval for the amount of time that passes after the start date, before work on the assignment starts.|
|[Finish](0e51b77c-b865-0d37-b3de-a4f488e7216e.md) *,#|[Finish](4a045c38-f202-4891-eac8-9fc2ee80c89a.md) *,#|[Finish](4a045c38-f202-4891-eac8-9fc2ee80c89a.md) *,#|DateTime|Gets the date when the assignment is scheduled to be completed.|
|[FinishVariance](544c5b57-6dd7-5f5f-a30c-1b48d7806e58.md) #|[FinishVariance](83e6b7a2-7988-5fc2-3d91-89fb0514811f.md) #|[FinishVariance](83e6b7a2-7988-5fc2-3d91-89fb0514811f.md) #|String|Gets the variance of the finish date of the assignment.|
| |[FinishVarianceMilliseconds](b12222bb-2b4a-19f6-3824-88cd821c7a26.md) #|[FinishVarianceMilliseconds](b12222bb-2b4a-19f6-3824-88cd821c7a26.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the variance of the finish date of the assignment.|
|[FinishVarianceTimeSpan](5d3073be-b808-6f71-a983-b7237613faee.md) #| | |TimeSpan|Gets the time interval for the variance of the finish date of the assignment.|
|[Id](2dcafd99-b3d5-4987-ec50-92c55ff05e9f.md) #|[Id](5dffe615-e608-a684-60e4-210d34834b4d.md) #|[Id](5dffe615-e608-a684-60e4-210d34834b4d.md) #|Guid|Gets the GUID of the assignment.|
|[IsConfirmed](aa9d63f4-c1fd-b825-b6f6-7bd771a910ad.md) #|[IsConfirmed](0fead0ec-d196-4d8f-aecd-b7c23690c19d.md) #|[IsConfirmed](0fead0ec-d196-4d8f-aecd-b7c23690c19d.md) #|Boolean|Gets a value that shows whether the resource has accepted the assignment.|
|[IsOverAllocated](4dc7d559-d70d-a1fb-497f-77b5a902b969.md) #|[IsOverAllocated](b5262211-9a6e-fa85-bddf-5dd99f4daf41.md) #|[IsOverAllocated](b5262211-9a6e-fa85-bddf-5dd99f4daf41.md) #|Boolean|Gets a value that indicates whether the resource is overallocated during the time of the assignment.|
|[IsPublished](d22861ce-5931-1aab-0b7b-551a2040cdf4.md) #|[IsPublished](650ab8d0-d8a9-4905-9b94-0d6237482152.md) #|[IsPublished](650ab8d0-d8a9-4905-9b94-0d6237482152.md) #|Boolean|Gets a value that indicates whether the assignment is published.|
|[IsResponsePending](689979a1-fa7b-8a9e-49c9-5d13c45a53d7.md) #|[IsResponsePending](6bb23b39-1230-4317-ac4f-f507c7b93164.md) #|[IsResponsePending](6bb23b39-1230-4317-ac4f-f507c7b93164.md) #|Boolean|Gets a value that shows whether the assignment update has been sent to the resource.|
|[IsUpdateNeeded](3b8109a7-21a8-b2bd-c136-2444522173ba.md) #|[IsUpdateNeeded](5eec16d8-99fc-a33b-ab63-e0835fa053f1.md) #|[IsUpdateNeeded](5eec16d8-99fc-a33b-ab63-e0835fa053f1.md) #|Boolean|Gets a value that indicates whether an assignment update should be sent to the resource.|
|[LevelingDelay](88e315c8-3635-8a6c-f306-58b74d3a5279.md) #|[LevelingDelay](08996e06-dfa4-bf9e-c8b6-88feedcf4eed.md) #|[LevelingDelay](08996e06-dfa4-bf9e-c8b6-88feedcf4eed.md) #|String|Gets the amount of time that resource leveling can delay the assignment from its early start date.|
| |[LevelingDelayMilliseconds](674b7c33-2d7a-da70-2c8f-68c36a354983.md) #|[LevelingDelayMilliseconds](674b7c33-2d7a-da70-2c8f-68c36a354983.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of time that resource leveling can delay the assignment from its early start date.|
|[LevelingDelayTimeSpan](8d75c0b3-5cd7-2981-c9d1-f71ca730f414.md) #| | |TimeSpan|Gets the time interval for the amount of time that resource leveling can delay the assignment from its early start date.|
|[Modified](e7843816-4c49-8cc2-ff1c-8f57f47ff163.md) #|[Modified](c10dd65b-1db1-436c-efd1-145aa67d6036.md) #|[Modified](c10dd65b-1db1-436c-efd1-145aa67d6036.md) #|DateTime|Gets the date when the assignment was modified.|
|[Notes](e2dd1564-d1ea-40cc-70b0-b87480c79171.md) *,#|[Notes](9b843675-14e5-b245-d704-f8174186f38d.md) *,#|[Notes](9b843675-14e5-b245-d704-f8174186f38d.md) *,#|String|Gets comments about the assignment.|
|[OvertimeCost](d59ac9ed-94f7-05ec-8ee8-795e9065202d.md) #|[OvertimeCost](d4964e48-6180-3ebf-e438-d580caf426cb.md) #|[OvertimeCost](d4964e48-6180-3ebf-e438-d580caf426cb.md) #|Double (64-bit)|Gets the total overtime cost of the assignment.|
|[RemainingCost](ba732b6b-2c34-1b4f-cc09-e79c74c2da93.md) #|[RemainingCost](698ff7c4-87fa-e170-06c3-68eb117e0049.md) #|[RemainingCost](698ff7c4-87fa-e170-06c3-68eb117e0049.md) #|Double (64-bit)|Gets the total remaining cost of the assignment, as scheduled.|
|[RemainingOvertimeCost](c218a16a-6811-8750-b2d1-6090be178d19.md) #|[RemainingOvertimeCost](d3a504b5-46fe-bbed-365f-44d84e182ced.md) #|[RemainingOvertimeCost](d3a504b5-46fe-bbed-365f-44d84e182ced.md) #|Double (64-bit)|Gets the scheduled remaining overtime cost of the assignment.|
|[Resume](6fe198cb-0c01-ca6f-dddb-a8575deb2c38.md) #|[Resume](f0156892-d4f4-8903-8df0-4334736bff2b.md) #|[Resume](f0156892-d4f4-8903-8df0-4334736bff2b.md) #|DateTime|Gets the date and time when a resource resumes work on the assignment.|
|[ScheduleCostVariance](5a7ca83a-0b6b-4582-246b-001671bcc00a.md) #|[ScheduleCostVariance](6f711a63-8f14-1871-970e-1ec8a343290b.md) #|[ScheduleCostVariance](6f711a63-8f14-1871-970e-1ec8a343290b.md) #|Double (64-bit)|Gets the schedule cost variance (CV), which is the difference between the baseline cost and the scheduled cost of the assignment.|
|[Start](5a56cff8-77b2-9f0f-64f6-7d233b252a1b.md) #|[Start](e67ed0fa-dd3f-18eb-93c3-dd9f3f417255.md) #|[Start](e67ed0fa-dd3f-18eb-93c3-dd9f3f417255.md) #|DateTime|Gets the date and time that a resource is scheduled to start the assignment.|
|[StartVariance](8d958a46-2501-3f9c-e290-e43b4f30ed0b.md) #|[StartVariance](c3ce7350-3fe4-fb07-543c-7881e8ff5d9d.md) #|[StartVariance](c3ce7350-3fe4-fb07-543c-7881e8ff5d9d.md) #|String|Gets the variance of the assignment start date.|
| |[StartVarianceMilliseconds](07b9eb78-d599-a33e-59c1-475e8b8a38a3.md) #|[StartVarianceMilliseconds](07b9eb78-d599-a33e-59c1-475e8b8a38a3.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the variance of the assignment start date.|
|[StartVarianceTimeSpan](f7164618-d53c-888f-f6e5-46072971f24a.md) #| | |TimeSpan|Gets the time interval for the variance of the assignment start date.|
|[Stop](a36eea49-bab3-6d83-0743-04119976d5f2.md) #|[Stop](e5d5b420-8b13-9625-1c2e-ab1d64b7f5a9.md) #|[Stop](e5d5b420-8b13-9625-1c2e-ab1d64b7f5a9.md) #|DateTime|Gets the date and time when a resource stops work on the assignment.|
|WorkContourType *,#|WorkContourType *,#|WorkContourType *,#|WorkContourType||
|[WorkVariance](60711093-d850-a8ce-3169-fb4b00590130.md) #|[WorkVariance](413a9e0d-7b46-c263-f5e8-6d33be7ce83f.md) #|[WorkVariance](413a9e0d-7b46-c263-f5e8-6d33be7ce83f.md) #|String|Gets the difference between baseline work and currently scheduled work on the assignment.|
| |[WorkVarianceMilliseconds](59f6985d-2c37-5deb-1fbe-f734b76db496.md) #|[WorkVarianceMilliseconds](59f6985d-2c37-5deb-1fbe-f734b76db496.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the difference between baseline work and currently scheduled work on the assignment.|
|[WorkVarianceTimeSpan](32bc05f8-60c9-661e-c15c-4de34d2777fa.md) #| | |TimeSpan|Gets the time interval for the difference between baseline work and currently scheduled work on the assignment.|


  **Note on Symbol Usage:**  
  * - indicates a new method or property.<br />
  \# - indicates Read access to a property.<br />
  $ - indicated Write access to a property.


## Syntax

### CSOM Library

The CSOM .NET library used for client-side applications. The class declaration for Assignment follows.

```C#
Public Class Assignment _
	Inherits ClientObject
```

#### Inheritance hierarchy

[System.Object](http://msdn2.microsoft.com/EN-US/library/e5kfa45b)[Microsoft.SharePoint.Client.ClientObject](http://msdn2.microsoft.com/EN-US/library/ee540788)<br />
==>Microsoft.ProjectServer.Client.Assignment<br />
==>[Microsoft.ProjectServer.Client.DraftAssignment](3a362ea3-8aa7-6ada-f6ff-4b93bed2b8b8.md)<br />
==>[Microsoft.ProjectServer.Client.PublishedAssignment](6721899e-a1de-eb24-6f68-85476f368612.md)

**Namespace:**[Microsoft.ProjectServer.Client](e79057b8-4161-453c-1035-02e38725305c.md) 

**Assembly:**Microsoft.ProjectServer.Client (in Microsoft.ProjectServer.Client.dll)


### JSOM Library

The JSOM library is used for AddIns and is written in JavaScript. The declaration for the Assignment object follows:
```
PS.Assignment
```

### REST Interface

The <a name="restresourceendpoint"> </a>

#### Endpoint URI structure
<a name="endpointuristructure"> </a>


```
http://<sitecollection> /<site> /_api/ProjectServer/Assignments('assignmentid')
```


#### HTTP requests
<a name="httprequests"> </a>

This resource supports the following HTTP commands:


- [GET](a2431b86-5e45-b4f5-dfb7-77145e3ac930.md#getsyntax)
    
- [DELETE](a2431b86-5e45-b4f5-dfb7-77145e3ac930.md#deletesyntax)
    

#### GET syntax
<a name="getsyntax"> </a>


```
GET http://<sitecollection> /<site> /_api/ProjectServer/Assignments('assignmentid')
```


#### DELETE syntax
<a name="deletesyntax"> </a>


```
DELETE http://<sitecollection> /<site> /_api/ProjectServer/Assignments('assignmentid')
```



## Remarks

The DraftAssignment class and the PublishedAssignment class are derived from the Assignment class. All of the properties in the Assignment class are read-only. To set the value of assignment properties, use a DraftAssignment object.

For more information about fields in Microsoft Project 2013, see [Available fields reference](http://office.microsoft.com/en-us/project-help/available-fields-reference-HA010370279.aspx).




## Thread safety

Any public  **static** ( **Shared** in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.
## See also


#### Reference

[Assignment members](e6c61a22-1596-4304-7ca9-7757d9467975.md) <br />
[Microsoft.ProjectServer.Client namespace](e79057b8-4161-453c-1035-02e38725305c.md)
