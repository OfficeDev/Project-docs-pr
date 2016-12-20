[comment]: # (Name:ResourcePlan)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# ResourcePlan

Represents a high-level look at what resources might be needed for a project. 



## Syntax

### CSOM

```C#
Class ResourcePlan 
```
### JSOM

```
PS.ResourcePlan
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/GetResourcePlanByUrl(start='{yyyy-MM-dd}',end='{yyyy-MM-dd}',scale='{timescale}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Assignments|&#x2713;|&#x2713;|&#x2713;|[PlanAssignmentCollection](PlanAssignmentCollection.md)|Gets a collection of PlanAssignment objects that are associated with the resource plan.|
|Finish|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the end date of the resource plan.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the resource plan.|
|Start|&#x2713;|&#x2713;|&#x2713;|DateTime|Gets the start date of the resource plan.|
|UtilizationDate|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|DateTime|Gets or sets the date and time of resource utilization for the current resource plan.|
|UtilizationType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[UtilizationType](UtilizationType.md)|Gets or sets the type of resource utilization for the current resource plan.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Deletes the ResourcePlan object.|
|[ForceCheckIn()](#ForceCheckIn__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Checks in the project resource plan in case it was left checked out in Project Server.|
|[Publish()](#Publish__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Publishes the project resource plan and makes it visible to other users in Project Server.|
|[Update()](#Update__)|&#x2713;|&#x2713;|&#x2713;|[QueueJob](QueueJob.md)|Saves changes from the project resource plan back to Project Server.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the ResourcePlan object.

#### Syntax

```
QueueJob DeleteObject()
```

#### Parameters

None

#### Return Value

[QueueJob](QueueJob.md)

### <a id="ForceCheckIn__"></a>ForceCheckIn()
 
Checks in the project resource plan in case it was left checked out in Project Server.

#### Syntax

```
QueueJob ForceCheckIn()
```

#### Parameters

None

#### Return Value

[QueueJob](QueueJob.md)

### <a id="Publish__"></a>Publish()
 
Publishes the project resource plan and makes it visible to other users in Project Server.

#### Syntax

```
QueueJob Publish()
```

#### Parameters

None

#### Return Value

[QueueJob](QueueJob.md)

### <a id="Update__"></a>Update()
 
Saves changes from the project resource plan back to Project Server.

#### Syntax

```
QueueJob Update()
```

#### Parameters

None

#### Return Value

[QueueJob](QueueJob.md)


## See Also
