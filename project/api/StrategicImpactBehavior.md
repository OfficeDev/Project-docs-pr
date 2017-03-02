[comment]: # (Name:StrategicImpactBehavior)
[comment]: # (Name:Microsoft.ProjectServer.StrategicImpactBehavior)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>StrategicImpactBehavior enumeration

<a name="description"></a>Specifies how strategic impact values behave in a Project Server workflow stage.

## <a name="syntax"></a>Syntax

### CSOM

```cs
enum StrategicImpactBehavior 
```
### JSOM

```javascript
PS.StrategicImpactBehavior
```
### REST Interface

StrategicImpactBehavior enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
> [!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NotSpecified"></a>NotSpecified|0|The strategic impact is not specified in the stage.|
|<a name="ReadOnly"></a>ReadOnly|1|The strategic impact values are read-only.|
|<a name="ReadWrite"></a>ReadWrite|2|The strategic impact values are read/write.|
|<a name="Required"></a>Required|3|The strategic impact values are required.|

## <a name="seeAlso"></a>See Also

[Stage](Stage.md)<br/>
[StageCreationInformation](StageCreationInformation.md)<br/>
