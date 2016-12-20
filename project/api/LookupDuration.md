[comment]: # (Name:LookupDuration)
[comment]: # (Type:Object)
[comment]: # (Status:Incomplete)
[comment]: # (GeneratedDate:2016-12-13 02:07:22Z)

# LookupDuration

Contains a data value for a lookup table of type Duration.



## Syntax

### CSOM

```C#
Class LookupDuration 
```
### JSOM

```
PS.LookupDuration
```
### REST Interface

This resource supports PUT, MERGE, and DELETE HTTP commands.

```
http://<sitecollection>/<site>/api/ProjectServer/LookupTables('{tableid}')/Entries('{entryid}')
```


## Members

### Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|Value|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the string value in a lookup table of type Duration.|
|ValueMilliseconds||&#x2713;&#x02B7;|&#x2713;&#x02B7;|Integer||
|ValueTimeSpan|&#x2713;&#x02B7;||&#x2713;&#x02B7;|TimeSpan|Gets or sets the duration as a TimeSpan value in a lookup table of typeDuration.|






## See Also
