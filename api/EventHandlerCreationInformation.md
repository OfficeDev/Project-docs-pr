[comment]: # (Name:EventHandlerCreationInformation)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# EventHandlerCreationInformation

Provides information for the creation of an event handler.



## Syntax

### CSOM

```C#
Class EventHandlerCreationInformation 
```
### JSOM

```
PS.EventHandlerCreationInformation
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
|AssemblyName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the assembly that is associated with the event handler.|
|ClassName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the class that is associated with the event handler.|
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the event handler.|
|EndpointUrl|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Uri|Gets or sets the network location of the event handler.|
|EventId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the GUID of the event that triggers the event handler.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the event handler.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the event handler.|
|Order|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the order of placement of an event handler in a list of event handlers that are triggered by an event.|






## See Also
