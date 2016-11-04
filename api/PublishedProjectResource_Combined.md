# PublishedProjectResource

Represents an enterprise resource that is published on Project Server.


## Members

The members listed consist of the properties defined for the PublishedProjectResource object and those inherited from the ProjectResource object. 

Three different interfaces are available:

* CSOM - client-side library providing support for .NET applications
* JSOM - JavaScript object model library that provides support for AddIn development
* REST - HTTP command-based interface that provides language-agnostic functionality

The properties table identifies the following items for entry: the name used in each library, read and write access, the data type, and a description of the property. 

### Methods

The  **PublishedProjectResource** has no methods.


### Properties

The  **PublishedProjectResource** object has the following properties.

|**CSOM** |**JSOM (get_, set_)** |**REST** |**Data Type**|**Description**|
|:----- |:-----|:-----|:-----|:-----|
|[ActualCost](6505cc67-b2d3-24c7-bfd0-e89ecc8ec98d.md) #|[ActualCost](facc22dc-5ce7-8c25-3ef4-59602828d975.md) #|[ActualCost](facc22dc-5ce7-8c25-3ef4-59602828d975.md) #|Double (64-bit)|Gets the costs incurred for work that has been performed by the project resource, along with any other recorded costs. |
|[ActualCostWorkPerformed](baf9e3ed-0d5e-1a63-6e3b-4368c0a755cb.md) #|[ActualCostWorkPerformed](243112d7-f51d-b216-1bd8-357230a0f184.md) #|[ActualCostWorkPerformed](243112d7-f51d-b216-1bd8-357230a0f184.md) #|String|Gets the actual cost for work that has been performed by the project resource to date. |
| |[ActualCostWorkPerformedMilliseconds](acc33939-6701-f7f7-d5fa-05363beac5c8.md) #|[ActualCostWorkPerformedMilliseconds](acc33939-6701-f7f7-d5fa-05363beac5c8.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the actual cost for work that has been performed by the project resource to date. |
|[ActualCostWorkPerformedTimeSpan](8e9f729b-c7b6-07a7-146f-16f198689604.md) #| | |TimeSpan|Gets the time interval for the actual cost for work that has been performed by the project resource to date. |
|[ActualOvertimeCost](a9a1b162-8627-ef51-33a9-521b365e11de.md) #|[ActualOvertimeCost](46725575-e9c8-7d01-d6fc-cd87f50fbeec.md) #|[ActualOvertimeCost](46725575-e9c8-7d01-d6fc-cd87f50fbeec.md) #|Double (64-bit)|Gets the actual cost incurred for overtime work that has been performed by the project resource. |
|[ActualOvertimeWork](aaa94449-39d5-ca84-03f6-a241cb496f0f.md) #|[ActualOvertimeWork](75b258d5-6967-93e7-2cad-2c44a13a95f5.md) #|[ActualOvertimeWork](75b258d5-6967-93e7-2cad-2c44a13a95f5.md) #|String|Gets the actual amount of overtime work that has been performed by the project resource. |
| |[ActualOvertimeWorkMilliseconds](a329ea4e-407d-f8d0-667e-36be60c3add1.md) #|[ActualOvertimeWorkMilliseconds](a329ea4e-407d-f8d0-667e-36be60c3add1.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the actual amount of overtime work that has been performed by the project resource. |
|[ActualOvertimeWorkTimeSpan](851c6884-e221-ab1a-40f2-196318974725.md) #| | |TimeSpan|Gets the time interval for the actual amount of overtime work that has been performed by the project resource. |
|[ActualWork](e4a9ddfc-7e20-aeb9-5979-0e98fec0b742.md) #|[ActualWork](fc72c30a-3f96-7575-13b0-d190a3ee07e3.md) #|[ActualWork](fc72c30a-3f96-7575-13b0-d190a3ee07e3.md) #|String|Gets the actual amount of work that has already been performed by the project resource. |
| |[ActualWorkMilliseconds](94ae6b44-edd7-015c-1624-80d5fd00b178.md) #|[ActualWorkMilliseconds](94ae6b44-edd7-015c-1624-80d5fd00b178.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the actual amount of work that has already been performed by the project resource. |
|[ActualWorkTimeSpan](5cb23e1a-dd50-5d93-81ab-6522bc5520af.md) #| | |TimeSpan|Gets the time interval for the actual amount of work that has already been performed by the project resource. |
|[Assignments property ](d6c80c25-13fa-6b63-9e42-88512d228936.md) #|[Assignments](15847708-2350-2c88-f942-23c6c4d4f797.md) #|[Assignments](15847708-2350-2c88-f942-23c6c4d4f797.md) #|[PublishedAssignmentCollection](e08e5c0b-4eb9-b668-2866-74c7429b47f3.md)|Gets the assignments that are associated with the resource.|
|[AvailableFrom](63ee307c-f333-d9b7-1030-e77656bad564.md) #|[AvailableFrom](4cb8af62-427b-2b6a-70fb-ebcaa24687cc.md) #|[AvailableFrom](4cb8af62-427b-2b6a-70fb-ebcaa24687cc.md) #|DateTime|Gets the starting date that the project resource is available for work, at the units specified for the current time period. |
|[AvailableTo](ce599644-8a73-1aea-74cf-9ce775828f56.md) #|[AvailableTo](b13d3159-cf97-a749-524b-f32bf09dc733.md) #|[AvailableTo](b13d3159-cf97-a749-524b-f32bf09dc733.md) #|DateTime|Gets the end date that the project resource is available for work, at the units specified for the current time period. |
|[BaselineCost](ef1af668-e377-9e50-c872-af4a2d7d3f61.md) #|[BaselineCost](73b4b27f-22ae-be94-605f-45b967507355.md) #|[BaselineCost](73b4b27f-22ae-be94-605f-45b967507355.md) #|Double (64-bit)|Gets the planned total cost for work to be performed by the project resource. |
|[BaselineWork](0d4c7d37-c216-8fb0-817a-6d9ab8f211c7.md) #|[BaselineWork](93507a93-bde1-4544-2e6a-5b35b90a0657.md) #|[BaselineWork](93507a93-bde1-4544-2e6a-5b35b90a0657.md) #|String|Gets the planned amount of work to be performed by the project resource. |
| |[BaselineWorkMilliseconds](1adb78e5-a6f8-7005-53ac-dd57b5ebeb79.md) #|[BaselineWorkMilliseconds](1adb78e5-a6f8-7005-53ac-dd57b5ebeb79.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the planned amount of work to be performed by the project resource. |
|[BaselineWorkTimeSpan](be5721c0-e7c5-81d9-f361-7c0eb66939b6.md) #| | |TimeSpan|Gets the time interval for the planned amount of work to be performed by the project resource. |
|[BudetCostWorkPerformed](6b65ecae-44cf-d648-e9e5-9977e7deb4f6.md) #|[BudetCostWorkPerformed](6ae1c786-236f-dbed-5ae9-bf6622335347.md) #|[BudetCostWorkPerformed](6ae1c786-236f-dbed-5ae9-bf6622335347.md) #|Double (64-bit)|Gets the budgeted cost for work performed by the project resource to date. |
|[BudgetedCost](1e8cebed-1772-9c08-73ce-c77e2b63f326.md) #|[BudgetedCost](83cfd8a4-f248-2557-6075-b117f75f3887.md) #|[BudgetedCost](83cfd8a4-f248-2557-6075-b117f75f3887.md) #|Double (64-bit)|Gets the total budgeted cost for work performed by the project resource. |
|[BudgetedCostWorkScheduled](09dbf4ce-a6af-a4cb-3d58-1bb1c3ff90fd.md) #|[BudgetedCostWorkScheduled](20440d94-e834-bd72-3f64-9105fdf9960a.md) #|[BudgetedCostWorkScheduled](20440d94-e834-bd72-3f64-9105fdf9960a.md) #|Double (64-bit)|Gets the budgeted cost of scheduled work for the project resource. |
|[BudgetedWork](338a35e5-33e7-9572-dc5c-5760c1dccfda.md) #|[BudgetedWork](1a4a07c5-4096-864e-da58-6abf46e454d9.md) #|[BudgetedWork](1a4a07c5-4096-864e-da58-6abf46e454d9.md) #|String|Gets the total budgeted amount of work to be performed by the project resource. |
| |[BudgetedWorkMilliseconds](35ba0d1b-b6cc-49cf-412b-7138f7f80443.md) #|[BudgetedWorkMilliseconds](35ba0d1b-b6cc-49cf-412b-7138f7f80443.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the total budgeted amount of work to be performed by the project resource. |
|[BudgetedWorkTimeSpan](ad89efef-1f0b-b5af-4cd8-c7d617e0ff03.md) #| | |TimeSpan|Gets the time interval for the total budgeted amount of work to be performed by the project resource. |
|[CanLevel property ](f2de4d06-b6c5-45e8-28e1-5e258f37336f.md) #|[CanLevel](168545c2-ee8a-b2f8-9c98-08638944cb12.md) #|[CanLevel](168545c2-ee8a-b2f8-9c98-08638944cb12.md) #|Boolean|Gets a value that indicates whether resource leveling can be performed on the resource.|
|[Code property ](bd3ef0a5-aa47-5e4c-bef8-ab83f0e3e07f.md) #|[Code](7e375d23-93c7-c641-1954-22dd403af003.md) #|[Code](7e375d23-93c7-c641-1954-22dd403af003.md) #|String|Gets any code, abbreviation, or number that is entered as part of the information about the resource.|
|[Cost](86fc0e59-8fb0-4aab-d5ea-a2540394b742.md) #|[Cost](ffc627af-8af7-87ce-74d4-4678bbec6898.md) #|[Cost](ffc627af-8af7-87ce-74d4-4678bbec6898.md) #|Double (64-bit)|Gets the total scheduled or estimated cost for work that has been performed, and work that remains to be performed, by the project resource. |
|[CostAccrual property ](c7fd5b9f-c706-b157-c948-d047521904fb.md) #|[CostAccrual](dbce4b64-5f81-30a7-ec93-a742dcc5f11c.md) #|[CostAccrual](dbce4b64-5f81-30a7-ec93-a742dcc5f11c.md) #|AccrueAt()|Gets a value that represents how and when to charge resource costs to the cost of a task.|
|[CostCenter property ](eca7d769-91f0-04e2-dcb9-5d37ce93e805.md) #|[CostCenter](bcc0783a-8862-ac48-c4e8-30ee64ca0cfc.md) #|[CostCenter](bcc0783a-8862-ac48-c4e8-30ee64ca0cfc.md) #|String|Gets any code, abbreviation, or number that has been entered as part of the information about the resource.|
|[CostPerUse property ](042a60a8-54c2-5386-7133-6ef13a4f73ff.md) #|[CostPerUse](e7e50d42-c44d-41f4-2158-4901087ac53f.md) #|[CostPerUse](e7e50d42-c44d-41f4-2158-4901087ac53f.md) #|Double (64-bit)|Gets the cost per use of the resource.|
|[CostVariance](f881e684-7fb2-e4d9-ac07-0321534aaea5.md) #|[CostVariance](5630c7b1-79f1-19d2-c035-695b69faf849.md) #|[CostVariance](5630c7b1-79f1-19d2-c035-695b69faf849.md) #|Double (64-bit)|Gets the difference between the baseline cost and actual cost for the project resource. |
|[CostVarianceAtCompletion](35259000-50d6-85a9-5f92-5f5ebdd9c7ff.md) #|[CostVarianceAtCompletion](6902f6fd-1ba0-73c2-97ff-cea7c1e4485f.md) #|[CostVarianceAtCompletion](6902f6fd-1ba0-73c2-97ff-cea7c1e4485f.md) #|Double (64-bit)|Gets the difference between the baseline cost and actual cost of the project resource at the completion of a project. |
|[Created](145760a8-fed7-91c5-954c-6aee92598a83.md) #|[Created](fae7b65e-e1c1-d7f0-722b-4d25f0f6c46c.md) #|[Created](fae7b65e-e1c1-d7f0-722b-4d25f0f6c46c.md) #|DateTime|Gets the date and time when the task was added to the project. |
|[CurrentCostVariance](406c2c0e-70fb-688c-5d64-241a09e70522.md) #|[CurrentCostVariance](3991cfa0-1210-eb54-d2c4-534b2019c44c.md) #|[CurrentCostVariance](3991cfa0-1210-eb54-d2c4-534b2019c44c.md) #|Double (64-bit)|Gets the difference between the baseline cost and the actual cost of the project resource to date. |
|[CustomFields](275ad75d-8bea-88fb-874d-c3fa64cab7d3.md) #|[CustomFields](c93f8197-8579-3d5a-b72c-1dd04e79c841.md) #|[CustomFields](c93f8197-8579-3d5a-b72c-1dd04e79c841.md) #|[CustomFieldCollection](39c70b02-09d2-d60e-94d9-ea538846124a.md)|Gets a collection of custom fields that have values set for this project resource. |
|[DefaultAssignmentOwner property ](22a36110-bc9d-cb45-68a8-54a776c888a0.md) #|[DefaultAssignmentOwner](f8f06bc1-a96a-b897-d648-a2f6de6e88b9.md) #|[DefaultAssignmentOwner](f8f06bc1-a96a-b897-d648-a2f6de6e88b9.md) #|User (SP)|Gets the default assignment owner.|
|[DefaultBookingType property ](62553a4f-f87b-1d44-e7c5-919d522b9900.md) #|[DefaultBookingType](7a7502ea-3c9d-8cdd-e0b0-a69e2c40a5cc.md) #|[DefaultBookingType](7a7502ea-3c9d-8cdd-e0b0-a69e2c40a5cc.md) #|BookingType()|Gets the default booking type for the resource.|
|[Email property ](9543d6dc-1665-9b79-ae7d-a1460055a664.md) #|[Email](66b08262-986d-8b18-417e-d02ca7f45143.md) #|[Email](66b08262-986d-8b18-417e-d02ca7f45143.md) #|String|Gets the email address of the resource.|
|[EnterpriseResource](d4db79de-eb1a-147f-12a5-ac12474d208d.md) #|[EnterpriseResource](ce004a4b-c9f9-313a-093b-2d534ff5f01c.md) #|[EnterpriseResource](ce004a4b-c9f9-313a-093b-2d534ff5f01c.md) #|[EnterpriseResource](2e73d43c-e447-413b-296e-c7b640e364dd.md)|Gets identification information for the project resource. |
|[FieldValues property ](3274ea0f-4036-2bc6-e34a-5ff673fe698f.md) #|[FieldValues](10d2275e-19ba-dbe3-4056-3ca758ee79ff.md) #|[FieldValues](10d2275e-19ba-dbe3-4056-3ca758ee79ff.md) #|Dictionary<String,Object>|Gets the collection of custom fields that have values set for the project resource.|
|[Finish](bb01f56a-d6ae-2291-2061-ff7587325275.md) #|[Finish](84426f78-2417-d48e-aee6-a29d36a39352.md) #|[Finish](84426f78-2417-d48e-aee6-a29d36a39352.md) #|DateTime|Gets the date when the project resource is scheduled to complete work on all assigned tasks. |
|[Group property ](67c856cc-16d8-170c-4961-da9664187cfd.md) #|[Group](710a2543-ef0e-3122-1f37-241dcd1a4297.md) #|[Group](710a2543-ef0e-3122-1f37-241dcd1a4297.md) #|String|Gets the name of a group to which a resource belongs.|
|[Id](fe612ba3-5e55-4a1b-06b2-ce8868cbf42d.md) #|[Id](ed9cd45c-efe8-d3a1-4706-7ba8b07956ec.md) #|[Id](ed9cd45c-efe8-d3a1-4706-7ba8b07956ec.md) #|Guid|Gets the GUID of the project resource. |
|[Initials property ](0cd0f819-808a-2c1f-45b1-09efe695c5bc.md) #|[Initials](9f322b08-550f-a9a7-e546-fffd49498150.md) #|[Initials](9f322b08-550f-a9a7-e546-fffd49498150.md) #|String|Gets the short name for the resource.|
|[IsBudgeted](da61f148-4391-6430-b493-7fd1e833be68.md) #|[IsBudgeted](d940a6a1-a4eb-1631-b07c-0dac091c951a.md) #|[IsBudgeted](d940a6a1-a4eb-1631-b07c-0dac091c951a.md) #|Boolean|Gets a value that indicates whether the project resource is used for budgeting purposes or is a regular resource. |
|[IsGenericResource](f76d117e-d532-253b-29a7-501150d125e9.md) #|[IsGenericResource](2d6c499b-7ccd-b823-c262-f67028573495.md) #|[IsGenericResource](2d6c499b-7ccd-b823-c262-f67028573495.md) #|Boolean|Gets a value that indicates whether the project resource is a generic placeholder. |
|[IsOverAllocated](7bd36fdf-fb74-90dc-076e-15939efa8f61.md) #|[IsOverAllocated](13b85feb-8725-417b-63b6-ebac546cc5f1.md) #|[IsOverAllocated](13b85feb-8725-417b-63b6-ebac546cc5f1.md) #|Boolean|Gets a value that indicates whether the project resource is assigned to do more work on all assigned tasks than can be done within the normal working capacity. |
|[Item property ](9ef02d34-ce33-76b7-e750-17ada61b2b39.md) #|[Item](3a9f71d8-2514-f832-c010-1b2c40122305.md) #|[Item](3a9f71d8-2514-f832-c010-1b2c40122305.md) #|Object|Gets a resource item in the published project.|
|[MaterialLabel property ](e3d6bb4b-54d4-d2f6-8ed6-b2fac279b42b.md) #|[MaterialLabel](65314899-cc8f-b160-6a8e-f89484315cea.md) #|[MaterialLabel](65314899-cc8f-b160-6a8e-f89484315cea.md) #|String|Gets the unit of measure for a material resource, which can be supplies or other consumable items that are used in a project.|
|[MaximumCapacity property ](f52268de-6e28-4d1b-ceeb-f1b364ce6a87.md) #|[MaximumCapacity](036421b2-4e84-c1ac-4069-ef3725a4e31c.md) #|[MaximumCapacity](036421b2-4e84-c1ac-4069-ef3725a4e31c.md) #|Double (64-bit)|Gets the percentage, or the number of units, that represent the maximum capacity for which the resource is available during the current time period.|
|[Modified](2cd2b8a2-57ae-ca2e-684d-e14196fd719e.md) #|[Modified](865ba067-ed41-8d23-9fae-497ee4fcdfce.md) #|[Modified](865ba067-ed41-8d23-9fae-497ee4fcdfce.md) #|DateTime|Gets the date of modification. |
|[Name property ](35e54086-7209-3dad-6da1-52c2966a5804.md) #|[Name](10dea198-2d69-9de8-1943-dc2577e4f897.md) #|[Name](10dea198-2d69-9de8-1943-dc2577e4f897.md) #|String|Gets the name of the project resource.|
|[Notes](0188ec9f-fa7d-2beb-6c51-f5281814d179.md) #|[Notes](fe59df03-8673-6c17-0234-25782c259be9.md) #|[Notes](fe59df03-8673-6c17-0234-25782c259be9.md) #|String|Gets comments entered about the project resource. |
|[OvertimeCost](10706114-1fff-3f82-3b82-01386544ef33.md) #|[OvertimeCost](8397ef88-5bd5-6d4e-f74b-659131b60e65.md) #|[OvertimeCost](8397ef88-5bd5-6d4e-f74b-659131b60e65.md) #|Double (64-bit)|Gets the total overtime cost for a project resource on all assigned tasks. |
|[OvertimeRate property ](1723938d-64f6-1a9f-5b1f-c6726673a6bc.md) #|[OvertimeRate](32096b59-d721-dedc-fa5b-640ff425ab7f.md) #|[OvertimeRate](32096b59-d721-dedc-fa5b-640ff425ab7f.md) #|Double (64-bit)|Gets the hourly rate of pay for overtime for the resource.|
|[OvertimeRateUnits property ](124beb66-43a8-7f65-8bfe-313b7ccb6cd6.md) #|[OvertimeRateUnits](b86fd189-3838-be7a-3ae4-a969640b68f8.md) #|[OvertimeRateUnits](b86fd189-3838-be7a-3ae4-a969640b68f8.md) #|OvertimeRateFormat()|Gets the rate description format in which the overtime rate is displayed.|
|[OvertimeWork](c0bc08c3-83ba-f655-e205-97d357dcfb26.md) #|[OvertimeWork](0154958a-3583-6b12-2395-3d2b934a85ce.md) #|[OvertimeWork](0154958a-3583-6b12-2395-3d2b934a85ce.md) #|String|Gets the amount of overtime work that is scheduled to be performed on all tasks assigned to the project resource and that is charged at the overtime rates of the project resource involved. |
| |[OvertimeWorkMilliseconds](54457ff3-3822-6c88-081d-98ed2ac2a554.md) #|[OvertimeWorkMilliseconds](54457ff3-3822-6c88-081d-98ed2ac2a554.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of overtime work that is scheduled to be performed on all tasks assigned to the project resource and that is charged at the overtime rates of the project resource involved. |
|[OvertimeWorkTimeSpan](c95d3b4f-e7f7-1f66-5f8b-27bfa2d73d06.md) #| | |TimeSpan|Gets the time interval for the amount of overtime work that is scheduled to be performed on all tasks assigned to the project resource and that is charged at the overtime rates of the project resource involved. |
|[PeakWork](e3d525d2-f8ed-b8eb-2006-9d152a238628.md) #|[PeakWork](f3c961e8-01e5-15e6-acd7-16693f975208.md) #|[PeakWork](f3c961e8-01e5-15e6-acd7-16693f975208.md) #|String|Gets the maximum effort that the project resource is scheduled to work on all assigned tasks. |
| |[PeakWorkMilliseconds](3f5c03e4-4367-70ca-6742-177e096de510.md) #|[PeakWorkMilliseconds](3f5c03e4-4367-70ca-6742-177e096de510.md) #|Double (64-bit)|Gets the duration of the maximum effort, expressed in milliseconds, that the project resource is scheduled to work on all assigned tasks. |
|[PeakWorkTimeSpan](5c666108-7869-0d96-cebf-89ba012283b9.md) #| | |TimeSpan|Gets the duration of the maximum effort that the project resource is scheduled to work on all assigned tasks. |
|[PercentWorkComplete](482c7056-c0e9-ff30-364b-94d3f1cb82e9.md) #|[PercentWorkComplete](1f0463aa-9328-b743-4431-341247165e5d.md) #|[PercentWorkComplete](1f0463aa-9328-b743-4431-341247165e5d.md) #|Integer (32-bit)|Gets the current status of the project resource, expressed as the percentage of work that has been completed by the project resouce. |
|[Phonetics property ](bc803273-2a1b-fd0b-7bfa-106ab1f63747.md) #|[Phonetics](5d613e9d-e56c-0416-e2c8-c359ea882622.md) #|[Phonetics](5d613e9d-e56c-0416-e2c8-c359ea882622.md) #|String|Gets phonetic information in either the Japanese Hiragana writing system or the Katakana writing system for resource names.|
|[RegularWork](2261ed2c-272f-c7f7-67b8-78d00e55bd8b.md) #|[RegularWork](9ed5bd0d-dc58-ff7d-817b-002a6b23a555.md) #|[RegularWork](9ed5bd0d-dc58-ff7d-817b-002a6b23a555.md) #|String|Gets the total amount of non-overtime work that is scheduled to be performed by the project resource. |
| |[RegularWorkMilliseconds](d2283e1b-06a5-2c6b-33f8-d391c6feef6a.md) #|[RegularWorkMilliseconds](d2283e1b-06a5-2c6b-33f8-d391c6feef6a.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the total amount of non-overtime work that is scheduled to be performed by the project resource. |
|[RegularWorkTimeSpan](14cc44b3-b6d3-d9f6-058a-74f9735432bf.md) #| | |TimeSpan|Gets the time interval for the total amount of non-overtime work that is scheduled to be performed by the project resource. |
|[RemainingCost](2c471ef7-04d1-53b8-8abb-2e550ccc1e64.md) #|[RemainingCost](452b09cf-4ec4-ec97-25ac-02ff91286221.md) #|[RemainingCost](452b09cf-4ec4-ec97-25ac-02ff91286221.md) #|Double (64-bit)|Gets the remaining scheduled expense that will be incurred by the project resource in completing the remaining scheduled work. |
|[RemainingOvertimeCost](5848a2e1-cde8-b432-3490-43bc9e63356d.md) #|[RemainingOvertimeCost](c123eac5-5883-12d3-006b-7e5d8312e1eb.md) #|[RemainingOvertimeCost](c123eac5-5883-12d3-006b-7e5d8312e1eb.md) #|Double (64-bit)|Gets the remaining scheduled overtime expense for the project resource. |
|[RemainingOvertimeWork](da3cd9ac-2e89-4ae9-31ae-b3c64e29ae38.md) #|[RemainingOvertimeWork](d839da0b-8ec9-a7f4-e596-57fcc7b37eb1.md) #|[RemainingOvertimeWork](d839da0b-8ec9-a7f4-e596-57fcc7b37eb1.md) #|String|Gets the amount of remaining scheduled overtime work for the project resource. |
| |[RemainingOvertimeWorkMilliseconds](d1c8e266-7ecb-9d9f-dae4-8ab27566b90b.md) #|[RemainingOvertimeWorkMilliseconds](d1c8e266-7ecb-9d9f-dae4-8ab27566b90b.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of remaining scheduled overtime work for the project resource. |
|[RemainingOvertimeWorkTimeSpan](67b0e462-ede3-2498-5173-b09fc441d91b.md) #| | |TimeSpan|Gets the time interval for the amount of remaining scheduled overtime work for the project resource. |
|[RemainingWork](3f96ebe6-95c1-4044-ad56-cd57c71af20a.md) #|[RemainingWork](0bc83658-02b6-3765-4659-dd0ee1d50311.md) #|[RemainingWork](0bc83658-02b6-3765-4659-dd0ee1d50311.md) #|String|Gets the amount of time, such as person-hours or days, that is still required for the project resource to complete a task or set of tasks. |
| |[RemainingWorkMilliseconds](afe2a99c-aea9-0e72-cb07-6a934b341d4c.md) #|[RemainingWorkMilliseconds](afe2a99c-aea9-0e72-cb07-6a934b341d4c.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the amount of time that is still required for the project resource to complete a task or set of tasks.|
|[RemainingWorkTimeSpan](85bd4592-01bc-5ada-d132-8c63610db36e.md) #| | |TimeSpan|Gets the time interval for the amount of time, such as person-hours or days, that is still required for the project resource to complete a task or set of tasks. |
|[ScheduleCostVariance](f4d5fdf5-8b8a-b52f-eda9-68d4bfacb1f4.md) #|[ScheduleCostVariance](2ed0c0bd-c1ea-f308-3231-65dfd1124748.md) #|[ScheduleCostVariance](2ed0c0bd-c1ea-f308-3231-65dfd1124748.md) #|Double (64-bit)|Gets the scheduled cost variance for the project resource. |
|[StandardRate property ](db33c098-683f-c2b7-f325-c2359feff115.md) #|[StandardRate](53a422f3-20c0-1379-15b4-e0e98a4eecd9.md) #|[StandardRate](53a422f3-20c0-1379-15b4-e0e98a4eecd9.md) #|Double (64-bit)|Gets the rate of pay per hour for regular, non-overtime work performed by the resource.|
|[StandardRateUnits property ](dfd648b6-1dcb-6aa1-e0bb-aaf10da0e1e8.md) #|[StandardRateUnits](b214883f-cca8-ffca-6164-e783698e108c.md) #|[StandardRateUnits](b214883f-cca8-ffca-6164-e783698e108c.md) #|StandardRateFormat()|Gets the rate description format in which the standard rate is displayed.|
|[Start](479e7959-ce42-84a6-5d0a-03072ed2092e.md) #|[Start](a8cb008f-6c78-8069-d115-d2506518b1bd.md) #|[Start](a8cb008f-6c78-8069-d115-d2506518b1bd.md) #|DateTime|Gets the date when an assigned resource is scheduled to begin working on a task. |
|[Work](e6cebd38-7f24-51fb-0007-2fb704ae4426.md) #|[Work](c1190290-62cf-21ea-dead-a4e217cfb6fd.md) #|[Work](c1190290-62cf-21ea-dead-a4e217cfb6fd.md) #|String|Gets the total amount of time to which the project resource is scheduled for a task. |
| |[WorkMilliseconds](f975d176-b232-7d0a-d926-955f80c37790.md) #|[WorkMilliseconds](f975d176-b232-7d0a-d926-955f80c37790.md) #|Double (64-bit)|Gets the time interval, expressed in milliseconds, for the total amount of time to which the project resource is scheduled for a task. |
|[WorkTimeSpan](97c3765a-2644-b842-7026-74292a7d4032.md) #| | |TimeSpan|Gets the time interval for the total amount of time to which the project resource is scheduled for a task. |



  **Note on Symbol Usage:**  
  (*blank*) - indicates the property has Read and Write access, and was available in the previous release.<br />
  * - indicates a new method or property.<br />
  # - indicates Read-Only access to a property.<br />
  $ - indicated Write-Only access to a property.


## Syntax

### CSOM Library

The CSOM .NET library used for client-side applications. The class declaration for PublishedProjectResource follows.

```C#
Public Class PublishedProjectResource _
	Inherits ProjectResource
```

#### Inheritance hierarchy

[System.Object](http://msdn2.microsoft.com/EN-US/library/e5kfa45b)[Microsoft.SharePoint.Client.ClientObject](http://msdn2.microsoft.com/EN-US/library/ee540788)<br />
==>[Microsoft.ProjectServer.Client.ProjectResource](2f8fba96-7294-a266-a9de-ec4a63e82bd9.md)<br />
==>Microsoft.ProjectServer.Client.PublishedProjectResource

**Namespace:**[Microsoft.ProjectServer.Client](e79057b8-4161-453c-1035-02e38725305c.md) 

**Assembly:** Microsoft.ProjectServer.Client (in Microsoft.ProjectServer.Client.dll)


### JSOM Library

The JSOM library is used for AddIns and is written in JavaScript. The declaration for the PublishedProjectResource object follows:
```
PS.PublishedProjectResource
```

### REST Interface

The 

<a name="restresourceendpoint"> </a>

#### Endpoint URI structure
<a name="endpointuristructure"> </a>


```
http://<sitecollection> /<site> /_api/ProjectServer/PublicProjectResources('projectresourceid')
```


#### HTTP requests
<a name="httprequests"> </a>

This resource supports the following HTTP commands:


- [GET](a2431b86-5e45-b4f5-dfb7-77145e3ac930.md#getsyntax)
    
- [DELETE](a2431b86-5e45-b4f5-dfb7-77145e3ac930.md#deletesyntax)
    

#### GET syntax
<a name="getsyntax"> </a>


```
GET http://<sitecollection> /<site> /_api/ProjectServer/PublicProjectResources('projectresourceid')
```


#### DELETE syntax
<a name="deletesyntax"> </a>


```
DELETE http://<sitecollection> /<site> /_api/ProjectServer/PublicProjectResources('projectresourceid')
```

## Remarks



## Thread safety

Any public  **static** ( **Shared** in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.
## See also



#### Reference

[Microsoft.ProjectServer.Client namespace](e79057b8-4161-453c-1035-02e38725305c.md)
