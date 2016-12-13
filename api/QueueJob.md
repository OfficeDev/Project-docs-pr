[comment]: # (Name:QueueJob)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# QueueJob

Queues a project for publishing.



## Syntax

### CSOM

```C#
Class QueueJob 
```
### JSOM

```
PS.QueueJob
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Projects('{projectid}')/QueueJobs('{jobid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the queue job.|
|JobState|&#x2713;|&#x2713;|&#x2713;|[JobState](JobState.md)|Gets the current progress of a job that is queued.|
|MessageType|&#x2713;|&#x2713;|&#x2713;|[QueueMsgType](QueueMsgType.md)|Gets the queue message type, for sending a job to the Project Server Queue System..|
|PercentComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the percentage complete value for the queue job.|
|Project|&#x2713;|&#x2713;|&#x2713;|[Project](Project.md)|Gets the project that is queued.|
|Submitter|&#x2713;|&#x2713;|&#x2713;|SPUser|Gets the resource that submitted the queue job.|
|WaitMilliseconds||&#x2713;|&#x2713;|Integer||
|WaitTime|&#x2713;||&#x2713;|TimeSpan|Gets the expected wait time before the queue job will complete.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Cancel()](#Cancel__)|&#x2713;|&#x2713;|&#x2713;|void|Cancels the queue job.|



## Method Details


### <a id="Cancel__"></a>Cancel()
 
Cancels the queue job.

#### Syntax

```
void Cancel()
```

#### Parameters

None

#### Return Value

void


## See Also
