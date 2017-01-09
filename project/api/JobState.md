[comment]: # (Name:JobState)
[comment]: # (Type:Enum)
[comment]: # (Status:Incomplete)

# <a name="name"></a>JobState enumeration

<a name="description"></a>The Project Service queue job state specifies the status of a queue job.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum JobState 
```
### JSOM

```JavaScript
PS.JobState
```
### REST Interface

JobState enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="Unknown"></a>Unknown|0|The queue job is unknown.|
|<a name="ReadyForProcessing"></a>ReadyForProcessing|1|The queue job is ready for processing.|
|<a name="SendIncomplete"></a>SendIncomplete|2|The message sent to the queue is incomplete.|
|<a name="Processing"></a>Processing|3|The queue job is processing.|
|<a name="Success"></a>Success|4|The queue job completed successfully.|
|<a name="Failed"></a>Failed|5|The queue job failed. Unfinished jobs with the same correlation are blocked.|
|<a name="FailedNotBlocking"></a>FailedNotBlocking|6|The queue job failed. Unfinished jobs with the same correlation are not blocked.|
|<a name="ProcessingDeferred"></a>ProcessingDeferred|7|The queue job processing is deferred.|
|<a name="CorrelationBlocked"></a>CorrelationBlocked|8|The queue job correlation is blocked; the job is not processed.|
|<a name="Canceled"></a>Canceled|9|The queue job is canceled.|
|<a name="OnHold"></a>OnHold|10|The queue job is on hold.|
|<a name="Sleeping"></a>Sleeping|11|The queue job is sleeping.|
|<a name="ReadyForLaunch"></a>ReadyForLaunch|12|The queue job is ready for launch.|
|<a name="LastState"></a>LastState|13|This is the last state of the queue job (internal use only).|

## <a name="seeAlso"></a>See Also

[QueueJob](QueueJob.md)<br/>
