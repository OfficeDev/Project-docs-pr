[comment]: # (Name:LookupEntry)
[comment]: # (Name:Microsoft.ProjectServer.LookupEntry)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupEntry class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a lookup table entry.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class LookupEntry 
```
### JSOM

```javascript
PS.LookupEntry
```
### REST Interface

Supported.

```
PS.LookupEntry

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/LookupTables('{tableid}')/Entries('{entryid}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="AppAlternateId"></a>AppAlternateId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the alternate GUID that is specified in an App package for Project Online.|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the lookup table entry.|
|<a name="FullValue"></a>FullValue|&#x2713;|&#x2713;|&#x2713;|String|Gets the concatenated value of a hierarchical text lookup table entry.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID for the lookup table entry.|
|<a name="InternalName"></a>InternalName|&#x2713;|&#x2713;|&#x2713;|String|Gets the internal name of the lookup table entry. Reserved for internal use..|
|<a name="SortIndex"></a>SortIndex|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Decimal|Gets or sets an index number for the lookup table entry.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the lookup entry object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the lookup entry object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[LookupCost](LookupCost.md)<br/>
[LookupDate](LookupDate.md)<br/>
[LookupDuration](LookupDuration.md)<br/>
[LookupEntryCollection](LookupEntryCollection.md)<br/>
[LookupEntryCreationInformation](LookupEntryCreationInformation.md)<br/>
[LookupNumber](LookupNumber.md)<br/>
[LookupText](LookupText.md)<br/>
