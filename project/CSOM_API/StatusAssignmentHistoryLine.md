
# StatusAssignmentHistoryLine

<!-- Need description here. 
   A statusing transaction entry for one or more assignments and/or tasks.  
   Gleaned from Statusing.ReadAssignmentHistory method topic.
-->

## Syntax

### CSOM

```C#
Class StatusAssignmentHistoryLine 
```
### JSOM

```
PS.StatusAssignmentHistoryLine
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection> /<site> /_api/ProjectServer/?????
```


## Members

### Properties

|**CSOM**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Author|&#x2713;|&#x2713;|&#x2713;|SPUser| |
|Comment|&#x2713;|&#x2713;|&#x2713;|String| |
|Decision|&#x2713;|&#x2713;|&#x2713;|StatusApprovalType| |
|Id|&#x2713;|&#x2713;|&#x2713;|Guid| |
|Submitted|&#x2713;|&#x2713;|&#x2713;|DateTime| |
|UpdateType|&#x2713;|&#x2713;|&#x2713;|StatusUpdateType| |

## See Also
