
# StatusAssignmentHistoryLineCollection

Represents a collection of [StatusAssignmentHistoryLineCollection](StatusAssignmentHistoryLineCollection.md) objects.

## Syntax

### CSOM

```C#
Class StatusAssignmentHistoryLineCollection 
```
### JSOM

```
PS.StatusAssignmentHistoryLineCollection 
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection> /<site> /_api/ProjectServer/?????
```

## Members

### Methods

|**CSOM**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetById(String oid)](#getbyguid)|&#x2713;|&#x2713;|&#x2713;|StatusAssignmentHistoryLine||


## Method Details

### <a name="getbyguid"></a>GetByGuid(Guid oid)
 


#### Syntax

```
StatusAssignmentHistoryLine GetByGuid(Guid uid)
```

#### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|oid| String | String representation of the StatusAssignmentHistoryLine Id.  


#### Return Value

StatusAssignmentHistoryLine<br />
A StatusAssignmentHistoryLine object.



StatusAssignmentHistoryLine GetById(String objectId)	Y/Y/Y
