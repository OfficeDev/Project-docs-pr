[comment]: # (Name:CurrencySymbolPosition)
[comment]: # (Name:Microsoft.ProjectServer.CurrencySymbolPosition)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>CurrencySymbolPosition enumeration

<a name="description"></a>Specifies the placement of the currency symbol.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum CurrencySymbolPosition 
```
### JSOM

```JavaScript
PS.CurrencySymbolPosition
```
### REST Interface

CurrencySymbolPosition enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>
[!div class="mx-tdBreakAll"]
|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NotSpecified"></a>NotSpecified|0| The currency symbol position is not specified. This constant is used in place of a DBNull value.|
|<a name="Before"></a>Before|1| Before, no space ($0).|
|<a name="After"></a>After|2| After, no space (0$).|
|<a name="BeforeWithSpace"></a>BeforeWithSpace|3| Before, with space ($ 0).|
|<a name="AfterWithSpace"></a>AfterWithSpace|4|After, with space (0 $).|

## <a name="seeAlso"></a>See Also

[DraftProject](DraftProject.md)<br/>
[PublishedProject](PublishedProject.md)<br/>
