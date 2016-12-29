[comment]: # (Name:EngagementCommentCollection)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>EngagementCommentCollection class

inherits members from [ClientObjectCollection<EngagementComment>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```C#
class EngagementCommentCollection 
```
### JSOM

```JavaScript
PS.EngagementCommentCollection
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.EngagementCommentCollection

http://<sitecollection>/<site>/_api/ProjectServer/?????
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[EngagementComment](EngagementComment.md)|Gets a [EngagementComment](EngagementComment.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[EngagementComment](EngagementComment.md)|Gets a [EngagementComment](EngagementComment.md) from the collection at the specified index.|

### <a name="methods"></a>Methods

|**Name**|**CSOM**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[Add(String comment)](#Add_String_comment_)|&#x2713;|&#x2713;|&#x2713;|[EngagementComment](EngagementComment.md)||

<br/>
#### Method Details

#### <a name="Add_String_comment_"></a>Add(String comment)


##### Syntax

```
EngagementComment Add(String comment)
```

##### Parameters
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|comment| String | 

##### Return Value

[EngagementComment](EngagementComment.md)

## <a name="seeAlso"></a>See Also

[Engagement](Engagement.md)<br/>
[EngagementComment](EngagementComment.md)<br/>
