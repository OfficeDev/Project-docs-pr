[comment]: # (Name:StageCustomField)
[comment]: # (Name:Microsoft.ProjectServer.StageCustomField)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>StageCustomField class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a custom field for a project stage.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class StageCustomField 
```
### JSOM

```javascript
PS.StageCustomField
```
### REST Interface

Supported.

```
PS.StageCustomField

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/Stages('{stageid}')/CustomFields('{fieldid}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the stage custom field.|
|<a name="Name"></a>Name|&#x2713;|&#x2713;|&#x2713;|String|Gets the name of the custom field.|
|<a name="ReadOnly"></a>ReadOnly|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the customer field is read-only in the stage.|
|<a name="Required"></a>Required|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the custom field is required in the stage.|
|<a name="Stage"></a>Stage|&#x2713;|&#x2713;|&#x2713;|[Stage](Stage.md)|Gets a link to the Stage entity.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the stage custom field object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the stage custom field object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[StageCustomFieldCollection](StageCustomFieldCollection.md)<br/>
[StageCustomFieldCreationInformation](StageCustomFieldCreationInformation.md)<br/>
