[comment]: # (Name:QueueJob)
[comment]: # (Name:Microsoft.ProjectServer.QueueJob)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>QueueJob class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Queues a project for publishing.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class QueueJob 
```
### JSOM

```javascript
PS.QueueJob
```
### REST Interface

Supported.

```
PS.QueueJob

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Projects('{projectid}')/QueueJobs('{jobid}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the queue job.|
|<a name="JobState"></a>JobState|&#x2713;|&#x2713;|&#x2713;|[JobState](JobState.md)|Gets the current progress of a job that is queued.|
|<a name="MessageType"></a>MessageType|&#x2713;|&#x2713;|&#x2713;|[QueueMsgType](QueueMsgType.md)|Gets the queue message type, for sending a job to the Project Server Queue System..|
|<a name="PercentComplete"></a>PercentComplete|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the percentage complete value for the queue job.|
|<a name="Project"></a>Project|&#x2713;|&#x2713;|&#x2713;|[Project](Project.md)|Gets the project that is queued.|
|<a name="Submitter"></a>Submitter|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)|Gets the resource that submitted the queue job.|
|<a name="WaitMilliseconds"></a>WaitMilliseconds||&#x2713;|&#x2713;|Integer|Gets the time interval, expressed in milliseconds, for expected wait time before the queue job will complete.|
|<a name="WaitTime"></a>WaitTime|&#x2713;||&#x2713;|TimeSpan|Gets the expected wait time before the queue job will complete.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Cancel()](#Cancel__)|&#x2713;|&#x2713;|&#x2713;|void|Cancels the queue job.|

<br/>
#### Method Details

#### <a name="Cancel__"></a>Cancel()
 
Cancels the queue job.

##### Syntax

```
void Cancel()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[DraftProject](DraftProject.md)<br/>
[DraftProjectResourceCollection](DraftProjectResourceCollection.md)<br/>
[ProjectCollection](ProjectCollection.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
[QueueJobCollection](QueueJobCollection.md)<br/>
[ResourcePlan](ResourcePlan.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
