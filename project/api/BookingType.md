[comment]: # (Name:BookingType)
[comment]: # (Type:Enum)
[comment]: # (Status:Verified)

# <a name="name"></a>BookingType enumeration

<a name="description"></a>Specifies how resources are booked for assignments.

## <a name="syntax"></a>Syntax

### CSOM

```C#
enum BookingType 
```
### JSOM

```JavaScript
PS.BookingType
```
### REST Interface

BookingType enumeration is not expliclity defined in REST.  Use the values below to understand what can be returned and set.

## <a name="members"></a>Members

<a name="enumMembers"></a>

|**Name**|**Value**|**Description**|
|:------ |:----: |:----- |
|<a name="NotSpecified"></a>NotSpecified|0| The resource booking type is not specified. This is the default value. This constant is used in place of a DBNull value.|
|<a name="Committed"></a>Committed|1|Resources are booked as "Committed".|
|<a name="Proposed"></a>Proposed|2|Resources are booked as "Proposed".|

## <a name="seeAlso"></a>See Also

[DraftAssignment](DraftAssignment.md)<br/>
[DraftProjectResource](DraftProjectResource.md)<br/>
[EnterpriseResource](EnterpriseResource.md)<br/>
[PlanAssignment](PlanAssignment.md)<br/>
[PlanAssignmentCreationInformation](PlanAssignmentCreationInformation.md)<br/>
[PublishedAssignment](PublishedAssignment.md)<br/>
[PublishedProjectResource](PublishedProjectResource.md)<br/>
