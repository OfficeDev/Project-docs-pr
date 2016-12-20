[comment]: # (Name:EventHandler)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# EventHandler

Represents the identification and location of a Project Server event handler.



## Syntax

### CSOM

```C#
Class EventHandler 
```
### JSOM

```
PS.EventHandler
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/EventHandlers('{handlerid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|AssemblyName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the assembly that is associated with the event handler.|
|ClassName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the class that is associated with the event handler.|
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the event handler.|
|EndpointUrl|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Uri|Gets or sets the URL of the endpoint that is associated with the event handler.|
|Event|&#x2713;|&#x2713;|&#x2713;|[Event](Event.md)|Gets the event that triggers the event handler.|
|Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the event handler.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the event handler.|
|Order|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the order of placement of the event handler in a list of event handlers that are associated with an event.|





### Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the EventHandler object.|



## Method Details


### <a id="DeleteObject__"></a>DeleteObject()
 
Deletes the EventHandler object.

#### Syntax

```
void DeleteObject()
```

#### Parameters

None

#### Return Value

void


## See Also
