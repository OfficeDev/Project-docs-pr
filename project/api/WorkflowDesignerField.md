[comment]: # (Name:WorkflowDesignerField)
[comment]: # (Name:Microsoft.ProjectServer.WorkflowDesignerField)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>WorkflowDesignerField class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Represents a field that is created in a workflow designer.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class WorkflowDesignerField 
```
### JSOM

```javascript
PS.WorkflowDesignerField
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.WorkflowDesignerField

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/?????
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="DisplayName"></a>DisplayName|&#x2713;|&#x2713;|&#x2713;|String|Gets the workflow designer field display name|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|String|Gets the GUID of the workflow designer field.|
|<a name="IsLookupField"></a>IsLookupField|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the field uses a lookup table.|
|<a name="IsReadOnly"></a>IsReadOnly|&#x2713;|&#x2713;|&#x2713;|Boolean|Gets a value that indicates whether the field is read-only.|
|<a name="LookupEntries"></a>LookupEntries|&#x2713;|&#x2713;|&#x2713;|[LookupEntryCollection](LookupEntryCollection.md)|Gets a collection of valid lookup table entries for the field.|
|<a name="SPFieldType"></a>SPFieldType|&#x2713;|&#x2713;|&#x2713;|SPFieldType|Gets the SPFieldType equivalent to the type of the Project Server field.|

## <a name="seeAlso"></a>See Also

[SPFieldType](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spfieldtype.aspx)<br/>
[WorkflowDesignerFieldCollection](WorkflowDesignerFieldCollection.md)<br/>
