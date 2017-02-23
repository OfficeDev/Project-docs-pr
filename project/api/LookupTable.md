[comment]: # (Name:LookupTable)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupTable class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a lookup table.

## <a name="syntax"></a>Syntax

### CSOM

```C#
class LookupTable 
```
### JSOM

```JavaScript
PS.LookupTable
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, MERGE, and DELETE HTTP commands.

```
PS.LookupTable

http://<sitecollection>/<site>/api/ProjectServer/LookupTables('{tableid}')
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**.NET**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="AppAlternateId"></a>AppAlternateId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the alternate lookup table GUID that is specified in an App package for Project Online.|
|<a name="Entries"></a>Entries|&#x2713;|&#x2713;|&#x2713;|[LookupEntryCollection](LookupEntryCollection.md)|Gets the collection of entries in the lookup table.|
|<a name="FieldType"></a>FieldType|&#x2713;|&#x2713;|&#x2713;|[CustomFieldType](CustomFieldType.md)|Gets the custom field type that matches the values in the lookup table.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the lookup table.|
|<a name="Masks"></a>Masks|&#x2713;|&#x2713;|&#x2713;|ReadOnlyCollection`1|Gets the collection of mask definitions for the levels of a hierarchical lookup table.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the lookup table.|
|<a name="SortOrder"></a>SortOrder|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[LookupTableSortOrder](LookupTableSortOrder.md)|Gets or sets the sort-order for the entries in the table.|

### <a name="methods"></a>Methods

|**Name**|**.NET**|**JSOM**|**REST**|**Return Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the lookup table object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()
 
Deletes the lookup table object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[CustomField](CustomField.md)<br/>
[CustomFieldCreationInformation](CustomFieldCreationInformation.md)<br/>
[LocalCustomField](LocalCustomField.md)<br/>
[LocalLookupTable](LocalLookupTable.md)<br/>
[LookupTableCollection](LookupTableCollection.md)<br/>
[LookupTableCreationInformation](LookupTableCreationInformation.md)<br/>
