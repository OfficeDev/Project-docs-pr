
# EnterpriseResourceCreationInformation class

Provides information for the creation of an enterprise resource ([EnterpriseResource](EnterpriseResource.md)) object.

## Syntax

### CSOM

```C#
Class EnterpriseResourceCreationInformation Inherits from ClientValueObject
```

### JSOM

```
PS.EnterpriseResourceCreationInformation
```

### REST Interface

<!-- 
    This needs to be verified, then added to the document. 
    This resource supports GET HTTP command.

```
http://<sitecollection>/<site>/_api/ProjectServer/Projects('projectid')/Assignments('assignmentid')
```

    End of comment  -->


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the enterprise resource.|
|IsBudget|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether this is a budget resource.|
|IsGeneric|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether this is a generic resource.|
|IsInactive|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a Boolean value that indicates whether this resource should be created in an inactive state.|
|Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the enterprise resource.|
|ResourceType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[EnterpriseResourceType](EnterpriseResourceType.md)|Gets or sets a value that represents the resource type.|


### Methods

The **EnterpriseResourceCreationInformation** object has no methods.

