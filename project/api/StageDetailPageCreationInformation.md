[comment]: # (Name:StageDetailPageCreationInformation)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# StageDetailPageCreationInformation

Provides property settings and methods that are used to create a project detail page (PDP) for a workflow stage.



## Syntax

### CSOM

```C#
Class StageDetailPageCreationInformation 
```
### JSOM

```
PS.StageDetailPageCreationInformation
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
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the stage PDP.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the PDP for the stage.|
|Position|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer|Gets or sets the position of a PDP relative to the other PDPs that are displayed in the stage.|
|RequiresAttention|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the stage PDP requires attention.|






## See Also
