[comment]: # (Name:Event)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# Event

Represents and identifies activity that occurs in Project Server when there are changes in business object data.



## Syntax

### CSOM

```C#
Class Event 
```
### JSOM

```
PS.Event
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/Events({id})
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|EventName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of an event in Project Server.|
|Id|&#x2713;|&#x2713;|&#x2713;|Integer|Gets the identifier of a Project Server event.|
|SourceName|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of an event source.|






## See Also
