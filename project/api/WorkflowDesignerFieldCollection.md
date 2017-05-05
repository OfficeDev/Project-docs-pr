[comment]: # (Name:WorkflowDesignerFieldCollection)
[comment]: # (Name:Microsoft.ProjectServer.WorkflowDesignerFieldCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>WorkflowDesignerFieldCollection class

inherits members from [ClientObjectCollection<WorkflowDesignerField>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a filtered collection of enterprise project custom fields that can be used in a workflow designer.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class WorkflowDesignerFieldCollection 
```
### JSOM

```javascript
PS.WorkflowDesignerFieldCollection
```
### REST Interface

Supported.

```
PS.WorkflowDesignerFieldCollection

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/?????
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[WorkflowDesignerField](WorkflowDesignerField.md)|Gets a [WorkflowDesignerField](WorkflowDesignerField.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[WorkflowDesignerField](WorkflowDesignerField.md)|Gets a [WorkflowDesignerField](WorkflowDesignerField.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[WorkflowDesignerField](WorkflowDesignerField.md)|Gets a [WorkflowDesignerField](WorkflowDesignerField.md) from the collection with the Guid value.|

<br/>
#### Method Details

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [WorkflowDesignerField](WorkflowDesignerField.md) from the collection with the Guid value.

##### Syntax

```
WorkflowDesignerField GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [WorkflowDesignerField](WorkflowDesignerField.md).|

##### Return Value

[WorkflowDesignerField](WorkflowDesignerField.md)

## <a name="seeAlso"></a>See Also

[WorkflowDesigner](WorkflowDesigner.md)<br/>
[WorkflowDesignerField](WorkflowDesignerField.md)<br/>
