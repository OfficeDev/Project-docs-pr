[comment]: # (Name:Engagement)
[comment]: # (Type:class)
[comment]: # (Status:Incomplete)

# <a name="name"></a>Engagement class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>

## <a name="syntax"></a>Syntax

### CSOM

```C#
class Engagement 
```
### JSOM

```JavaScript
PS.Engagement
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.Engagement

http://<sitecollection>/<site>/_api/ProjectServer/?????
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties

|**Name**|**CSOM**|**JSOM**|**REST**|**Data Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="Comments"></a>Comments|&#x2713;|&#x2713;|&#x2713;|[EngagementCommentCollection](EngagementCommentCollection.md)||
|<a name="CreatedDate"></a>CreatedDate|&#x2713;|&#x2713;|&#x2713;|DateTime||
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String||
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid||
|<a name="Modified"></a>Modified|&#x2713;|&#x2713;|&#x2713;|DateTime||
|<a name="ModifiedBy"></a>ModifiedBy|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)||
|<a name="Project"></a>Project|&#x2713;|&#x2713;|&#x2713;|[Project](Project.md)||
|<a name="Resource"></a>Resource|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[EnterpriseResource](EnterpriseResource.md)||
|<a name="ReviewedBy"></a>ReviewedBy|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)||
|<a name="ReviewedDate"></a>ReviewedDate|&#x2713;|&#x2713;|&#x2713;|DateTime||
|<a name="Status"></a>Status|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[EngagementStatus](EngagementStatus.md)||
|<a name="SubmittedBy"></a>SubmittedBy|&#x2713;|&#x2713;|&#x2713;|[SPUser](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.spuser.aspx)||
|<a name="SubmittedDate"></a>SubmittedDate|&#x2713;|&#x2713;|&#x2713;|DateTime||
|<a name="TimephasedEditsOnly"></a>TimephasedEditsOnly|&#x2713;|&#x2713;|&#x2713;|Boolean||

## <a name="seeAlso"></a>See Also

[ProjectEngagement](ProjectEngagement.md)<br/>
[ProjectEngagementCollection](ProjectEngagementCollection.md)<br/>
[ResourceEngagement](ResourceEngagement.md)<br/>
[ResourceEngagementCollection](ResourceEngagementCollection.md)<br/>
[SPUser](https://msdn.microsoft.com/library/microsoft.sharepoint.spuser.aspx)<br/>
