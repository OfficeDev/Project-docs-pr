[comment]: # (Name:StageCreationInformation)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# StageCreationInformation

Provides methods and properties that are used to create a project workflow stage.



## Syntax

### CSOM

```C#
Class StageCreationInformation 
```
### JSOM

```
PS.StageCreationInformation
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
|Behavior|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[StrategicImpactBehavior](StrategicImpactBehavior.md)|Gets or sets the Strategic Impact value for a project stage; for example, Read Only.|
|CheckInRequired|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether project check in is required.|
|CustomFields|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|ReadOnlyCollection`1|Gets or sets the collection of all the custom fields that have values set for the project stage.|
|Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the stage description.|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the project stage.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the project stage.|
|PhaseId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the phase that contains the project stage.|
|ProjectDetailPages|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|ReadOnlyCollection`1|Gets or sets a collection of project detail pages for the project stage.|
|SubmitDescription|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description for submit.|
|WorkflowStatusPageId|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID for the stage workflow status project detail page.|






## See Also
