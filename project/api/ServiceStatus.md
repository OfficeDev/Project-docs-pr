[comment]: # (Name:ServiceStatus)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# ServiceStatus

Provides information about the status of the Project Server service.



## Syntax

### CSOM

```C#
Class ServiceStatus 
```
### JSOM

```
PS.ServiceStatus
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/_api/ProjectServer/?????
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|IsDelegate|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the current user has started a delegation session in PWA.|
|IsReadOnly|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the Project Server database is in read-only mode.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[StopDelegation()](#StopDelegation__)|&#x2713;|&#x2713;|&#x2713;|void|Stops the current delegation session.|



## Method Details


### <a id="StopDelegation__"></a>StopDelegation()
 
Stops the current delegation session.

#### Syntax

```
void StopDelegation()
```

#### Parameters

None

#### Return Value

void


## See Also
