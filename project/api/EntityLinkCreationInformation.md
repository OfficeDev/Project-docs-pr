[comment]: # (Name:EntityLinkCreationInformation)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>EntityLinkCreationInformation class

<a name="description"></a>Contains the properties that can be set when creating a [EntityLink](EntityLink.md).

## <a name="syntax"></a>Syntax

### REST Interface

This resource supports POST HTTP commands.

```
PS.EntityLinkCreationInformation

http://<sitecollection>/<site>/_api/ProjectServer/?????
```
POST Example (not all fields may be required)
```
body = {
	'parameters': {
		'EntityLinkType':'value', 
		'Id':'value', 
		'Url':'value'		
	}
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="EntityLinkType"></a>EntityLinkType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[EntityLinkType](EntityLinkType.md)||
|<a name="Id"></a>Id|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid||
|<a name="Url"></a>Url|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String||

## <a name="seeAlso"></a>See Also

[EntityLink](EntityLink.md)<br/>
[EntityLinksCollection](EntityLinksCollection.md)<br/>
