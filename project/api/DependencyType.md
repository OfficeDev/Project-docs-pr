[comment]: # (Name:DependencyType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>DependencyType enumeration

<a name="description"></a>Specifies the type of dependency to establish between two tasks.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum DependencyType 
```
### JSOM

```JavaScript
PS.DependencyType
```
### REST Interface

DependencyType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="FinishFinish"></a>FinishFinish|0|Finish to finish (FF) task link type. The successor task B cannot finish until the predecessor task A finishes.|
|<a name="FinishStart"></a>FinishStart|1|This is the default value. Finish to start (FS) task link type. The predecessor task A must finish before the successor task B can start.|
|<a name="StartFinish"></a>StartFinish|2|Start to finish (SF) task link type. The predecessor task A must start before the successor task B finishes. This is the least common of the four dependency types.|
|<a name="StartStart"></a>StartStart|3|Start to start (SS) task link type. The successor task B cannot start until the predecessor task A starts.|

## <a name="remarks"></a>Remarks

For an example of the SF task dependency type, in a scenario where you are setting a fence post, the successor task B is **Pour Cement** and the predecessor task A is **Set Post**.<br/>
The successor (**Pour Cement**) must start first; however, the predecessor (**Set Post**) must finish before the successor (**Pour Cement**) finishes.<br/>
The **DependencyType** enumeration in the CSOM is equivalent to the [LINK_TYPE](https://msdn.microsoft.com/en-us/library/office/websvcproject.projectdataset.dependencyrow.link_type_di_pj14mref.aspx) property in the **Project** service.

## <a name="seeAlso"></a>See Also

[DraftTaskLink](DraftTaskLink.md)<br/>
[PublishedTaskLink](PublishedTaskLink.md)<br/>
[TaskLinkCreationInformation](TaskLinkCreationInformation.md)<br/>
