---
title: "Duplicate Detection Rule (DuplicateRule)  table/entity reference (Microsoft Dataverse) | Microsoft Docs"
description: "Includes schema information and supported messages for the Duplicate Detection Rule (DuplicateRule)  table/entity."
ms.date: 06/04/2024
ms.service: "powerapps"
ms.topic: "reference"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "phecke"
ms.author: "pehecke"
search.audienceType: 
  - developer
---

# Duplicate Detection Rule (DuplicateRule)  table/entity reference

> [!NOTE]
> Unsure about table vs. entity? See [Developers: Understand terminology in Microsoft Dataverse](/powerapps/developer/data-platform/understand-terminology).

Rule used to identify potential duplicates.


## Messages

|Message|Web API Operation|SDK class or method|
|-|-|-|
|Assign|PATCH /duplicaterules(*duplicateruleid*)<br />[Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) `ownerid` property.|<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
|CompoundUpdateDuplicateDetectionRule|<xref:Microsoft.Dynamics.CRM.CompoundUpdateDuplicateDetectionRule?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.CompoundUpdateDuplicateDetectionRuleRequest>|
|Create|POST /duplicaterules<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE /duplicaterules(*duplicateruleid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|GrantAccess|<xref:Microsoft.Dynamics.CRM.GrantAccess?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
|ModifyAccess|<xref:Microsoft.Dynamics.CRM.ModifyAccess?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
|PublishDuplicateRule|<xref:Microsoft.Dynamics.CRM.PublishDuplicateRule?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.PublishDuplicateRuleRequest>|
|PublishXml|<xref:Microsoft.Dynamics.CRM.PublishXml?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.PublishXmlRequest>|
|Retrieve|GET /duplicaterules(*duplicateruleid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET /duplicaterules<br />See [Query Data](/powerapps/developer/data-platform/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RetrievePrincipalAccess|<xref:Microsoft.Dynamics.CRM.RetrievePrincipalAccess?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
|RetrieveSharedPrincipalsAndAccess|<xref:Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
|RevokeAccess|<xref:Microsoft.Dynamics.CRM.RevokeAccess?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
|UnpublishDuplicateRule|<xref:Microsoft.Dynamics.CRM.UnpublishDuplicateRule?displayProperty=nameWithType />|<xref:Microsoft.Crm.Sdk.Messages.UnpublishDuplicateRuleRequest>|
|Update|PATCH /duplicaterules(*duplicateruleid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|DuplicateRules|
|DisplayCollectionName|Duplicate Detection Rules|
|DisplayName|Duplicate Detection Rule|
|EntitySetName|duplicaterules|
|IsBPFEntity|False|
|LogicalCollectionName|duplicaterules|
|LogicalName|duplicaterule|
|OwnershipType|UserOwned|
|PrimaryIdAttribute|duplicateruleid|
|PrimaryNameAttribute|name|
|SchemaName|DuplicateRule|

<a name="writable-attributes"></a>

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [BaseEntityName](#BKMK_BaseEntityName)
- [Description](#BKMK_Description)
- [DuplicateRuleId](#BKMK_DuplicateRuleId)
- [ExcludeInactiveRecords](#BKMK_ExcludeInactiveRecords)
- [IsCaseSensitive](#BKMK_IsCaseSensitive)
- [IsCustomizable](#BKMK_IsCustomizable)
- [MatchingEntityName](#BKMK_MatchingEntityName)
- [Name](#BKMK_Name)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [StatusCode](#BKMK_StatusCode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UniqueName](#BKMK_UniqueName)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)


### <a name="BKMK_BaseEntityName"></a> BaseEntityName

|Property|Value|
|--------|-----|
|Description|Record type of the record being evaluated for potential duplicates.|
|DisplayName|Base Record Type|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|baseentityname|
|MaxLength|160|
|RequiredLevel|ApplicationRequired|
|Type|String|


### <a name="BKMK_Description"></a> Description

|Property|Value|
|--------|-----|
|Description|Description of the duplicate detection rule.|
|DisplayName|Description|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|description|
|MaxLength|2000|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_DuplicateRuleId"></a> DuplicateRuleId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the duplicate detection rule.|
|DisplayName|Duplicate Detection Rule|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|duplicateruleid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_ExcludeInactiveRecords"></a> ExcludeInactiveRecords

|Property|Value|
|--------|-----|
|Description|Determines whether to flag inactive records as duplicates|
|DisplayName|Exclude Inactive Records|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|excludeinactiverecords|
|RequiredLevel|None|
|Type|Boolean|

#### ExcludeInactiveRecords Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|True||
|0|False||

**DefaultValue**: 0



### <a name="BKMK_IsCaseSensitive"></a> IsCaseSensitive

|Property|Value|
|--------|-----|
|Description|Indicates if the operator is case-sensitive.|
|DisplayName|Case Sensitive|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|iscasesensitive|
|RequiredLevel|None|
|Type|Boolean|

#### IsCaseSensitive Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|True||
|0|False||

**DefaultValue**: 0



### <a name="BKMK_IsCustomizable"></a> IsCustomizable

**Added by**: Basic Solution Solution

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Is Customizable|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|iscustomizable|
|RequiredLevel|SystemRequired|
|Type|ManagedProperty|


### <a name="BKMK_MatchingEntityName"></a> MatchingEntityName

|Property|Value|
|--------|-----|
|Description|Record type of the records being evaluated as potential duplicates.|
|DisplayName|Matching Record Type|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|matchingentityname|
|MaxLength|160|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_Name"></a> Name

|Property|Value|
|--------|-----|
|Description|Name of the duplicate detection rule.|
|DisplayName|Rule Name|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|name|
|MaxLength|160|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwnerId"></a> OwnerId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user or team who owns the duplicate detection rule.|
|DisplayName|Owner|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|ownerid|
|RequiredLevel|SystemRequired|
|Targets|systemuser,team|
|Type|Owner|


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridtype|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_StatusCode"></a> StatusCode

|Property|Value|
|--------|-----|
|Description|Reason for the status of the duplicate detection rule.|
|DisplayName|Status Reason|
|IsValidForForm|True|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|statuscode|
|RequiredLevel|SystemRequired|
|Type|Status|

#### StatusCode Choices/Options

|Value|Label|State|
|-----|-----|-----|
|0|Unpublished|0|
|1|Publishing|0|
|2|Published|1|



### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName||
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|timezoneruleversionnumber|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|


### <a name="BKMK_UniqueName"></a> UniqueName

**Added by**: msft_DupDetectionNewColumnsExtension Solution

|Property|Value|
|--------|-----|
|Description||
|DisplayName|UniqueName|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|True|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|uniquename|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|--------|-----|
|Description|Time zone code that was in use when the record was created.|
|DisplayName||
|Format|None|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|utcconversiontimezonecode|
|MaxValue|2147483647|
|MinValue|-1|
|RequiredLevel|None|
|Type|Integer|

<a name="read-only-attributes"></a>

## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [BaseEntityMatchCodeTable](#BKMK_BaseEntityMatchCodeTable)
- [BaseEntityTypeCode](#BKMK_BaseEntityTypeCode)
- [ComponentIdUnique](#BKMK_ComponentIdUnique)
- [ComponentState](#BKMK_ComponentState)
- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedByYomiName](#BKMK_CreatedByYomiName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [IsManaged](#BKMK_IsManaged)
- [MatchingEntityMatchCodeTable](#BKMK_MatchingEntityMatchCodeTable)
- [MatchingEntityTypeCode](#BKMK_MatchingEntityTypeCode)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [OverwriteTime](#BKMK_OverwriteTime)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningBusinessUnitName](#BKMK_OwningBusinessUnitName)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [SolutionId](#BKMK_SolutionId)
- [StateCode](#BKMK_StateCode)
- [SupportingSolutionId](#BKMK_SupportingSolutionId)


### <a name="BKMK_BaseEntityMatchCodeTable"></a> BaseEntityMatchCodeTable

|Property|Value|
|--------|-----|
|Description|Database table that stores match codes for the record type being evaluated for potential duplicates.|
|DisplayName|Base Record Type Match Code Table|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|baseentitymatchcodetable|
|MaxLength|50|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_BaseEntityTypeCode"></a> BaseEntityTypeCode

|Property|Value|
|--------|-----|
|Description|Record type of the record being evaluated for potential duplicates.|
|DisplayName|Base Record Type|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|baseentitytypecode|
|RequiredLevel|SystemRequired|
|Type|Picklist|

#### BaseEntityTypeCode Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Account|Business that represents a customer or potential customer. The company that is billed in business transactions.|
|2|Contact|Person with whom a business unit has a relationship, such as customer, supplier, and colleague.|
|5|Note|Note that is attached to one or more objects, including other notes.|
|6|Business Unit Map|Stores mapping attributes for business units.|
|7|Owner|Group of undeleted system users and undeleted teams. Owners can be used to control access to specific objects.|
|8|User|Person with access to the Microsoft CRM system and who owns objects in the Microsoft CRM database.|
|9|Team|Collection of system users that routinely collaborate. Teams can be used to simplify record sharing and provide team members with common access to organization data when team members belong to different Business Units.|
|10|Business Unit|Business, division, or department in the Microsoft Dynamics 365 database.|
|14|System User Principal|For internal use only.|
|29|Subscription|For internal use only.|
|30|Filter Template|Template for a filter.|
|31|Privilege Object Type Code|For internal use only.|
|33|Subscription Synchronization Information|For internal use only.|
|35|Tracking information for deleted entities|For internal use only.|
|36|Client update|Microsoft Dynamics 365 client for Outlook offline database update.|
|37|Subscription Manually Tracked Object|For internal use only.|
|42|SystemUser BusinessUnit Entity Map|Stores mapping attributes for business units.|
|44|Field Sharing|Defines CRM security principals (users and teams) access rights to secured field for an entity instance.|
|45|Subscription Statistic Offline|Subscription Statistic Offline|
|46|Subscription Statistic Outlook|Subscription Statistic Outlook|
|47|Subscription Sync Entry Offline|Used for offline sync, internal use only.|
|48|Subscription Sync Entry Outlook|Used for outlook sync, internal use only.|
|50|Position|Position of a user in the hierarchy|
|51|System User Manager Map|For internal use only.|
|52|User Search Facet||
|54|Global Search Configuration||
|55|FileAttachment|File Attachment|
|60|SystemUserAuthorizationChangeTracker|Internal authorization table to track user authorization changes|
|61|PrincipalEntityBusinessUnitMap|Internal authorization table to track user authorization changes|
|72|Record Filter|Record Access Filter|
|73|EntityRecordFilter|RecordFilter Object Type Codes|
|74|Secured Masking Rule|Secured Masking Rules to apply to fields.|
|78|Virtual Entity Data Provider|Developers can register plug-ins on a data provider to enable data access for virtual entities in the system.|
|85|Virtual Entity Data Source|Internal entity that stores data source information for all installed providers.|
|92|Team template|Team template for an entity enabled for automatically created access teams.|
|99|Social Profile|This entity is used to store social profile information of its associated account and contacts on different social channels.|
|101|Service Plan|Service Plan|
|103|Privileges Removal Setting|Privileges Removal Setting|
|126|Indexed Article|Article indexed for search purposes.|
|127|Article|Structured content that is part of the knowledge base.|
|129|Subject|Information regarding subjects available in the system.|
|132|Announcement|Announcement associated with an organization.|
|135|Activity Party|Person or group associated with an activity. An activity can have multiple activity parties.|
|150|User Settings|User's preferred settings.|
|300|Canvas App|An application built through a canvas-based editing experience.|
|301|Callback Registration|Callback Registration that stores configuration.|
|372|Connector|Connector Entity to support Solutioning Integration|
|373|Connection Instance||
|380|Environment Variable Definition|Contains information about the settable variable: its type, default value, and etc.|
|381|Environment Variable Value|Holds the value for the associated EnvironmentVariableDefinition entity.|
|400|AI Template||
|401|AI Model||
|402|AI Configuration||
|418|Dataflow||
|430|Entity Analytics Config|This entity contains information about which entities are enabled for Azure Data Lake Services integration|
|431|Image Attribute Configuration|Store configuration for each image attribute|
|432|Entity Image Configuration|Store image configuration for each entity|
|950|New Process|New Process Business Process Flow|
|951|Translation Process|Translation Process Business Process Flow|
|955|Expired Process|Expired Process Business Process Flow|
|1001|Attachment|MIME attachment for an activity.|
|1002|Attachment|Attachment for an email activity.|
|1003|Internal Address|Storage of addresses for a user, business unit, or site.|
|1007|Image Descriptor|For internal use only.|
|1016|Article Template|Template for a knowledge base article that contains the standard attributes of an article.|
|1019|Organization|Top level of the Microsoft Dynamics 365 business hierarchy. The organization can be a specific business, holding company, or corporation.|
|1021|Organization UI|Entity customizations including form layout and icons. Includes current and past versions.|
|1023|Privilege|Permission to perform an action in Microsoft CRM. The platform checks for the privilege and rejects the attempt if the user does not hold the privilege.|
|1030|System Form|Organization-owned entity customizations including form layout and dashboards.|
|1031|User Dashboard|User-owned dashboards.|
|1036|Security Role|Grouping of security privileges. Users are assigned roles that authorize their access to the Microsoft CRM system.|
|1037|Role Template|Template for a role. Defines initial attributes that will be used when creating a new role.|
|1039|View|Saved query against the database.|
|1043|String Map|Mapping between strings.|
|1071|Address|Address and shipping information. Used to store additional addresses for an account or contact.|
|1072|Subscription Clients|For internal use only.|
|1075|Status Map|Mapping between statuses.|
|1082|Article Comment|Comment on a knowledge base article.|
|1086|User Fiscal Calendar|Custom fiscal calendar used for tracking sales quotas.|
|1094|Authorization Server|Authorization servers that trust this organization|
|1095|Partner Application|Partner applications registered for this organization|
|1111|System Chart|System chart attached to an entity.|
|1112|User Chart|Chart attached to an entity.|
|1113|Ribbon Tab To Command Mapping|A mapping between Tab Ids, and the Commands within those tabs.|
|1115|Ribbon Context Group|Groupings of contextual tabs.|
|1116|Ribbon Command|Ribbon Commands - the command definition, rules, etc.|
|1117|Ribbon Rule|Ribbon rule definitions, used to enable and disable, show and hide ribbon elements.|
|1120|Application Ribbons|Ribbon customizations for the application ribbon and entity ribbon templates.|
|1130|Ribbon Difference|All layout customizations to be applied to the ribbons, which contain only the differences from the base ribbon.|
|1140|Replication Backlog|Entity to hold replication backlog tasks. For internal use only.|
|1189|Document Suggestions|Document Suggestions|
|1190|SuggestionCardTemplate|Templates for Suggestion Card in Grid|
|1200|Field Security Profile|Profile which defines access level for secured attributes|
|1201|Field Permission|Group of privileges used to categorize users to provide appropriate access to secured columns.|
|1203|Team Profiles|Team Profiles|
|1204|Application|Application|
|1234|Channel Property Group|Group or collection of channel properties provided by the external channel for a Microsoft Dynamics 365 activity.|
|1236|Channel Property|Instance of a channel property containing its name and corresponding data type.|
|1300|SocialInsightsConfiguration|Configuration for the social insights.|
|1309|Saved Organization Insights Configuration|Saved configuration for the organization insights|
|1400|Sync Attribute Mapping Profile|Profile which defines sync attribute mapping|
|1401|Sync Attribute Mapping|Group of Sync-Attribute Mappings used to provide Attribute mappings during sync for a particular user|
|1403|Team Sync-Attribute Mapping Profiles|Team Sync-Attribute Mapping Profiles|
|1404|Principal Sync Attribute Map|Maps security principals (users and teams) to sync attribute mappings.|
|2000|Annual Fiscal Calendar|Year long fiscal calendar of an organization. A span of time during which the financial activities of an organization are calculated.|
|2001|Semiannual Fiscal Calendar|Calendar representing the semi-annual span of time during which the financial activities of an organization are calculated.|
|2002|Quarterly Fiscal Calendar|Quarterly fiscal calendar of an organization. A span of time during which the financial activities of an organization are calculated.|
|2003|Monthly Fiscal Calendar|Monthly fiscal calendar of an organization. A span of time during which the financial activities of an organization are calculated.|
|2004|Fixed Monthly Fiscal Calendar|Fixed monthly fiscal calendar of an organization. A span of time during which the financial activities of an organization are calculated.|
|2010|Email Template|Template for an email message that contains the standard attributes of an email message.|
|2012|Unresolved Address|For internal use only.|
|2013|Territory|Territory represents sales regions.|
|2015|Theme|Information that's used to set custom visual theme options for client applications.|
|2016|User Mapping|User Mapping|
|2020|Queue|A list of records that require action, such as accounts, activities, and cases.|
|2023|QueueItemCount|For internal use only.|
|2024|QueueMemberCount|For internal use only.|
|2027|License|Stores information about a Microsoft CRM license.|
|2029|Queue Item|A specific item in a queue, such as a case record or an activity record.|
|2500|User Entity UI Settings|Stores user settings for entity views.|
|2501|User Entity Instance Data|Per User item instance data|
|3000|Integration Status|Contains integration status information.|
|3005|Channel Access Profile|Information about permissions needed to access Dynamics 365 through external channels.For internal use only|
|3008|External Party|Information about external parties that need to access Dynamics 365 from external channels.For internal use only|
|3231|Connection Role|Role describing a relationship between a two records.|
|3233|Connection Role Object Type Code|Specifies the entity type that can play specific role in a connection.|
|3234|Connection|Relationship between two entities.|
|4003|Calendar|Calendar used by the scheduling system to define when an appointment or activity is to occur.|
|4004|Calendar Rule|Defines free/busy times for a service and for resources or resource groups, such as working, non-working, vacation, and blocked.|
|4011|Inter Process Lock|Inter Process Locks.|
|4023|Email Hash|Email activity hashes used for correlation purposes.|
|4101|Display String Map|Maps customized display strings to entities.|
|4102|Display String|Customized messages for an entity that has been renamed.|
|4110|Notification|For internal use only.|
|4120|Exchange Sync Id Mapping|The mapping used to keep track of the IDs for items synced between CRM and Exchange.|
|4200|Activity|Task performed, or to be performed, by a user. An activity is any action for which an entry can be made on a calendar.|
|4201|Appointment|Commitment representing a time interval with start/end times and duration.|
|4202|Email|Activity that is delivered using email protocols.|
|4204|Fax|Activity that tracks call outcome and number of pages for a fax and optionally stores an electronic copy of the document.|
|4207|Letter|Activity that tracks the delivery of a letter. The activity can contain the electronic copy of the letter.|
|4210|Phone Call|Activity to track a telephone call.|
|4212|Task|Generic activity representing work needed to be done.|
|4216|Social Activity|For internal use only.|
|4220|UntrackedEmail|Activity that is delivered using UntrackedEmail protocols.|
|4230|Saved View|Saved database query that is owned by a user.|
|4231|Metadata Difference|Metadata Difference|
|4232|Business Data Localized Label|Business Data Localized Label|
|4250|Recurrence Rule|Recurrence Rule represents the pattern of incidence of recurring entities.|
|4251|Recurring Appointment|The Master appointment of a recurring appointment series.|
|4299|Email Search|Email Address Search Table.|
|4410|Data Import|Status and ownership information for an import job.|
|4411|Data Map|Data map used in import.|
|4412|Import Source File|File name of file used for import.|
|4413|Import Data|Unprocessed data from imported files.|
|4414|Duplicate Detection Rule|Rule used to identify potential duplicates.|
|4415|Duplicate Record|Potential duplicate record.|
|4416|Duplicate Rule Condition|Condition of a duplicate detection rule.|
|4417|Column Mapping|Mapping for columns in a data map.|
|4418|List Value Mapping|In a data map, maps list values from the source file to Microsoft Dynamics 365.|
|4419|Lookup Mapping|In a data map, maps a lookup attribute in a source file to Microsoft Dynamics 365.|
|4420|Owner Mapping|In a data map, maps ownership data from the source file to Microsoft Dynamics 365.|
|4423|Import Log|Failure reason and other detailed information for a record that failed to import.|
|4424|Bulk Delete Operation|User-submitted bulk deletion job.|
|4425|Bulk Delete Failure|Record that was not deleted during a bulk deletion job.|
|4426|Transformation Mapping|In a data map, maps the transformation of source attributes to Microsoft Dynamics 365 attributes.|
|4427|Transformation Parameter Mapping|In a data map, defines parameters for a transformation.|
|4428|Import Entity Mapping|Mapping for entities in a data map.|
|4450|Data Performance Dashboard|Data Performance Dashboard.|
|4490|Office Document|Used to store Office Documents in database in binary format.|
|4500|Relationship Role|Relationship between an account or contact and an opportunity.|
|4501|Relationship Role Map|Mapping of the primary associated objects between which the relationship role is valid.|
|4502|Customer Relationship|Relationship between a customer and a partner in which either can be an account or contact.|
|4567|Auditing|Track changes to records for analysis, record keeping, and compliance.|
|4579|Ribbon Client Metadata.|A ribbon client metadata.|
|4600|Entity Map|Represents a mapping between two related entities so that data from one record can be copied into the form of a new related record.|
|4601|Attribute Map|Represents a mapping between attributes where the attribute values should be copied from a record into the form of a new related record.|
|4602|Plug-in Type|Type that inherits from the IPlugin interface and is contained within a plug-in assembly.|
|4603|Plug-in Type Statistic|Plug-in type statistic.|
|4605|Plug-in Assembly|Assembly that contains one or more plug-in types.|
|4606|Sdk Message|Message that is supported by the SDK.|
|4607|Sdk Message Filter|Filter that defines which SDK messages are valid for each type of entity.|
|4608|Sdk Message Processing Step|Stage in the execution pipeline that a plug-in is to execute.|
|4609|Sdk Message Request|For internal use only.|
|4610|Sdk Message Response|For internal use only.|
|4611|Sdk Message Response Field|For internal use only.|
|4613|Sdk Message Pair|For internal use only.|
|4614|Sdk Message Request Field|For internal use only.|
|4615|Sdk Message Processing Step Image|Copy of an entity's attributes before or after the core system operation.|
|4616|Sdk Message Processing Step Secure Configuration|Non-public custom configuration that is passed to a plug-in's constructor.|
|4618|Service Endpoint|Service endpoint that can be contacted.|
|4619|Plug-in Trace Log|Trace and exception information generated by plug-ins and custom workflow activities.|
|4700|System Job|Process whose execution can proceed independently or in the background.|
|4702|Workflow Wait Subscription|For internal use only.|
|4703|Process|Set of logical rules that define the steps necessary to automate a specific business process, task, or set of actions to be performed.|
|4704|Process Dependency|Dependencies for a process.|
|4705|ISV Config|An XML document used to configure client extension controls.|
|4706|Process Log|Log used to track process execution.|
|4707|Application File|Files used by the application|
|4708|Organization Statistic|Statistics measuring the organization's usage of the Microsoft Dynamics 365 system over the past 24 hours.|
|4709|Site Map|XML data used to control the application navigation pane.|
|4710|Process Session|Information that is generated when a dialog is run. Every time that you run a dialog, a dialog session is created.|
|4711|Expander Event|For internal use only. An event that will be expanded into jobs whose executions can proceed in the background.|
|4712|Process Trigger|Trigger that invoke a rule.|
|4720|Flow Session|Entity to store the information that is generated when a Power Automate Desktop flow runs.|
|4724|Process Stage|Stage associated with a process.|
|4725|Business Process Flow Instance|Active path associated with every Business Process Flow instance|
|4800|Web Wizard|Definition for a Web-based wizard.|
|4802|Wizard Page|Page in a Web-based wizard.|
|4803|Web Wizard Access Privilege|Privilege needed to access a Web-based wizard.|
|4810|Time Zone Definition|Time zone definition, including name and time zone code.|
|4811|Time Zone Rule|Definition for time conversion between local time and Coordinated Universal Time (UTC) for a particular time zone at a particular time period.|
|4812|Time Zone Localized Name|Localized name of the time zone.|
|5000|Recently Used|Most recently used data table.|
|5004|NL2SQ Registration Information|Org registration status, AllowedEntity list, and registration error message.|
|7000|System Application Metadata|For internal use only.|
|7001|User Application Metadata|For internal use only.|
|7100|Solution|A solution which contains CRM customizations.|
|7101|Publisher|A publisher of a CRM solution.|
|7102|Publisher Address|Address and shipping information. Used to store additional addresses for a publisher.|
|7103|Solution Component|A component of a CRM solution.|
|7104|Solution Component Definition|Contains all the information required to process a solution aware entity|
|7105|Dependency|A component dependency in CRM.|
|7106|Dependency Node|The representation of a component dependency node in CRM.|
|7107|Invalid Dependency|An invalid dependency in the CRM system.|
|7108|Dependency Feature|A dependency feature.|
|7200|RuntimeDependency|Form Level dependencies in CRM.|
|7755|ElasticFileAttachment|Elastic File Attachment|
|8000|Post|An activity feed post.|
|8001|Post Role|Represents the objects with which an activity feed post is associated. For internal use only.|
|8002|Post Regarding|Represents which object an activity feed post is regarding. For internal use only.|
|8003|Follow|Represents a user following the activity feed of an object.|
|8005|Comment|A comment on an activity feed post.|
|8006|Like|A like on an activity feed post.|
|8040|ACIViewMapper|Customized messages for an entity that has been renamed.|
|8050|Trace|A trace log.|
|8051|Trace Association|Represents the objects with which a trace record is associated. For internal use only.|
|8052|Trace Regarding|Represents which object a trace record is regarding. For internal use only.|
|8181|Routing Rule Set|Define Routing Rule to route cases to right people at the right time|
|8199|Rule Item|Please provide the description for entity|
|8700|AppModule Metadata|For internal use only.|
|8701|AppModule Metadata Dependency|For internal use only.|
|8702|AppModule Metadata Async Operation|For internal use only.|
|8840|Hierarchy Rule|Organization-owned entity customizations including mapping Quick view form with Relationship Id|
|9006|Model-driven App|A role-based, modular business app that provides task-based functionality for a particular area of work.|
|9007|App Module Component|A component available in a business app such as entity, dashboard, form, view, chart, and business process.|
|9009|App Module Roles|Security roles that have access to a business app.|
|9011|App Config Master|Contains the master list of all properties that can be customized for apps in Dynamics 365. For internal use only.|
|9012|App Configuration|Contains a mapping between an app configuration instance and an app, which defines the properties that can be customized for the app. Optionally, also contains navigation setting for an app. For internal use only.|
|9013|App Configuration Instance|Contains a property or a list of properties from the app configuration master list that can be customized for any app in Dynamics 365. For internal use only.|
|9100|Report|Data summary in an easy-to-read layout.|
|9101|Report Related Entity|Entities related to a report. A report can be related to multiple entities.|
|9102|Report Related Category|Categories related to a report. A report can be related to multiple categories.|
|9103|Report Visibility|Area in which to show a report. A report can be shown in multiple areas.|
|9104|Report Link|Links and dependencies between reports. A report may drill through to another report, or it may have another report as a sub-report.|
|9105|Currency|Currency in which a financial transaction is carried out.|
|9106|Mail Merge Template|Template for a mail merge document that contains the standard attributes of that document.|
|9107|Import Job|For internal use only.|
|9201|LocalConfigStore||
|9300|Record Creation and Update Rule|Defines the settings for automatic record creation.|
|9301|Record Creation and Update Rule Item|Defines the individual conditions required for creating records automatically.|
|9333|Web Resource|Data equivalent to files used in Web development. Web resources provide client-side components that are used to provide custom user interface elements.|
|9400|Channel Access Profile Rule|Defines the rules for automatically associating channel access profiles to external party records.For internal use only|
|9401|Channel Access Profile Rule Item|Defines the rule items of a profile rule set for the automated profile association.For internal use only|
|9502|SharePoint Site|SharePoint site from where documents can be managed in Microsoft Dynamics 365.|
|9507|Sharepoint Document|Document libraries or folders on a SharePoint server from where documents can be managed in Microsoft Dynamics 365.|
|9508|Document Location|Document libraries or folders on a SharePoint server from where documents can be managed in Microsoft Dynamics 365.|
|9509|SharePoint Data|SharePoint's Data Corresponding to a user , Record , Location and Page|
|9510|Rollup Properties|Stores properties related to rollup fields.|
|9511|Rollup Job|Stores rollup jobs.|
|9600|Goal|Target objective for a user or a team for a specified time period.|
|9602|Rollup Query|Query that is used to filter the results of the goal rollup.|
|9603|Goal Metric|Type of measurement for a goal, such as money amount or count.|
|9604|Rollup Field|Field to be rolled up to calculate the actual and in-progress values against the goal.|
|9605|Email Server Profile|Holds the Email Server Profiles of an organization|
|9606|Mailbox||
|9607|Mailbox Statistics|Stores data regarding Mailbox processing cycles|
|9608|Mailbox Auto Tracking Folder|Stores data about what folders for a mailbox are auto tracked|
|9609|Mailbox Tracking Category|Stores data about what categories for a mailbox are tracked|
|9650|Process Configuration|For internal use only.|
|9690|Organization Insights Notification|Stores data regarding organization insights notification|
|9699|Organization Insights Metric|Stores data regarding organization insights metric|
|9750|SLA|Contains information about the tracked service-level KPIs for cases that belong to different customers.|
|9751|SLA Item|Contains information about a tracked support KPI for a specific customer.|
|9752|SLA KPI Instance|Service level agreement (SLA) key performance indicator (KPI) instance that is tracked for an individual case|
|9753|Custom Control|For internal use only.|
|9754|Custom Control Resource|Custom Control Resource Id|
|9755|Custom Control Default Config|For internal use only.|
|9800|Entity||
|9808|Attribute||
|9809|OptionSet||
|9810|Entity Key||
|9811|Entity Relationship||
|9812|Managed Property||
|9813|Relationship Entity||
|9814|Relationship Attribute|Stores relationship attributes mapping for Multi-predicate relationship|
|9815|Entity Index|Metadata describing index of an entity|
|9816|Index Attribute|Stores index attributes|
|9820|Secured Masking Column|Defines secured masking rule for column|
|9866|Mobile Offline Profile|Information to administer and manage the data available to mobile devices in offline mode.|
|9867|Mobile Offline Profile Item|Information on entity availability to mobile devices in offline mode for a mobile offline profile item.|
|9868|Mobile Offline Profile Item Association|Information on relationships to be used to follow related entity's records for mobile offline profile item.|
|9869|Sync Error|Failure reason and other detailed information for a record that failed to sync.|
|9870|Offline Command Definition|For internal use only.|
|9875|Language Provisioning State|Container for language provisioning checkpoint states|
|9880|Ribbon Metadata To Process|Container for Ribbon Metadata To Process|
|9890|SolutionHistoryData|solution history data|
|9900|Navigation Setting|Navigation Setting: A setting page or group of pages available for configuration within an app. A record representing a group of pages is regarded as the parent navigation setting of one or more other records. For internal use only.|
|9910|MultiEntitySearch|Multi Entity Search.|
|9912|Multi Select Option Value|Multi Select Option Value|
|9919|Hierarchy Security Configuration||
|9930|Knowledge Base Record|Metadata of knowledge base (KB) articles associated with Microsoft Dynamics 365 entities.|
|9932|Time Stamp Date Mapping|For internal use only.`|
|9936|Azure Service Connection|Stores connection information for an Azure service|
|9940|Document Template|Used to store Document Templates in database in binary format.|
|9941|Personal Document Template|Used to store Personal Document Templates in database in binary format.|
|9945|Text Analytics Entity Mapping||
|9947|Knowledge Search Model|Configuration for automatic suggestion of knowledge articles using text analytics and search|
|9949|Advanced Similarity Rule|A text match rule identifies similar records using keywords and key phrases determined with text analytics|
|9950|Office Graph Document|Office Graph Documents Description|
|9951|Similarity Rule||
|9953|Knowledge Article|Organizational knowledge for internal and external use.|
|9955|Knowledge Article Views|No of times an article is viewed per day|
|9957|Language|Language|
|9958|Feedback|Feedback and rating.|
|9959|Category|Entity for categorizing records to make it easier for your customers to find them on portals and through search.|
|9960|Knowledge Article Category|Category for a Knowledge Article.|
|9961|DelveActionHub|Delve Action Hubs Description|
|9962|Action Card|Action card entity to show action cards.|
|9968|ActionCardUserState||
|9973|Action Card User Settings|Stores user settings for action cards|
|9983|Action Card Type|To provide master data for the card types list. For internal use only|
|9986|Interaction for Email||
|9987|External Party Item|Information about external party items that need to access Dynamics 365 from external channels.For internal use only|
|9996|HolidayWrapper||
|9997|Email Signature|Signature for email message|
|10000|Solution Component Attribute Configuration||
|10001|Solution Component Batch Configuration||
|10002|Solution Component Configuration||
|10003|Solution Component Relationship Configuration||
|10004|Solution History||
|10005|Solution History Data Source||
|10006|Component Layer||
|10007|Component Layer Data Source||
|10008|Package||
|10009|Package History||
|10011|StageSolutionUpload||
|10012|ExportSolutionUpload||
|10013|FeatureControlSetting|featurecontrolsetting|
|10014|Solution Component Summary||
|10015|Solution Component Count Summary||
|10016|Solution Component Data Source||
|10017|Solution Component Count Data Source||
|10018|Microsoft Entra ID|Virtual entity that represents Microsoft Entra ID|
|10019|Staged Entity|Stores staged entity metadata to be processed before fully created.|
|10020|Staged Entity Attribute|Stores staged entity attribute metadata to be processed in async.|
|10021|Staged Metadata Async Operation|Stores staged entity metadata to be processed before fully created.|
|10022|Key Vault Reference|Contains data that refers to an Azure Key Vault containing credentials used to connect to secure web-hosted resources.|
|10023|Managed Identity|Contains data to represent an Azure Active Directory Application used to connect to secure web-hosted resources.|
|10024|Catalog|Entity for cataloging records to make it easier for your customers to find them on portals and through search.|
|10025|Catalog Assignment|Entity for assigning records to a specific catalog |
|10026|Internal Catalog Assignment||
|10027|Custom API|Entity that defines a custom API|
|10028|Custom API Request Parameter|Entity that defines a request parameter for a custom API|
|10029|Custom API Response Property|Entity that defines a response property for a custom API |
|10030|Plugin Package||
|10031|NonRelational Data Source||
|10032|ProvisionLanguageForUser||
|10033|Shared Object|A record that is being shared in a real time collaboration session.|
|10034|Shared Workspace|References a container that stores real-time collaboration data.|
|10035|Shared Workspace Access Token|Contains information about the shared workspace access tokens.|
|10036|Shared Workspace Non-Relational|References a container that stores real-time collaboration data.|
|10037|Shared Workspace Pool|Contains metadata about a container used to store real-time collaboration data. Once claimed, a sharedworkspace record would be created with copied metadata.|
|10038|Data Lake Folder|A folder is a place to store data in Azure Data Lake.|
|10039|Data Lake Folder Permission||
|10040|Data Lake Workspace|A workspace is a place to store data in Azure Data Lake.|
|10041|Data Lake Workspace Permission||
|10042|Data Processing configuration||
|10043|Exported Excel|A Place holder entity to save excel file for each exportretaineddata custom api requests.|
|10044|RetainedData Excel|A Place holder entity to save excel file for each exportretaineddata custom api requests.|
|10045|Synapse Database|This entity represents an external Synapse database and its associated datalake folder link.|
|10046|Synapse Link External Table State|Synapse Link external table states|
|10047|Synapse Link Profile|Synapse Link Profile|
|10048|Synapse Link Profile Entity|Entities associated with the Synapse Link profile|
|10049|Synapse Link Profile Entity State|Runtime state of the Synapse Link entity|
|10050|Synapse Link Schedule|Synapse link schedules|
|10051|Component Version||
|10052|Component Version Data Source||
|10053|Component Version (Internal)||
|10054|DataflowRefreshHistory||
|10055|EntityRefreshHistory||
|10056|Shared Link Setting|Shared Link Setting|
|10057|DelegatedAuthorization|Context for delegated authorization.|
|10059|CascadeGrantRevokeAccessRecordsTracker||
|10060|CascadeGrantRevokeAccessVersionTracker||
|10061|RevokeInheritedAccessRecordsTracker||
|10062|TdsMetadata||
|10063|Model-Driven App Element|Associates a model-driven app with its components.|
|10064|Model-Driven App Component Node's Edge|Contains Model-Driven App Component Node's Edge Information.|
|10065|Model-Driven App Component Node|Contains Model-Driven App Component Node Information|
|10066|Model-Driven App Setting|Holds the value for the associated App Setting Definition.|
|10067|Model-Driven App User Setting|Holds the value for the associated App User Setting Definition.|
|10068|Organization Setting|Holds the value for the associated Organization Setting Definition.|
|10069|Setting Definition|Contains Setting Definitions|
|10070|CanvasApp Extended Metadata|Holds extended metadata values for canvas apps that are not solution aware|
|10071|Service Plan Mapping|Service Plan Mapping|
|10072|Service Plan Custom Control|Service Plan Custom Controls|
|10074|ApplicationUser|Application User that has non-interactive access to the CDS system|
|10077|OData v4 Data Source|Data sources used by the OData v4 data provider to access data from an external web service.|
|10078|Workflow Binary||
|10079|Credential||
|10080|Desktop Flow Module||
|10081|Flow Capacity Assignment|Capacity assignment for usage in Power Automate|
|10082|Flow Credential Application||
|10083|Flow Event|Entity to store the events that happen during usage of Power Automate.|
|10084|Flow Machine||
|10085|Flow Machine Group||
|10086|Flow Machine Image||
|10087|Flow Machine Image Version||
|10088|Flow Machine Network||
|10089|ProcessStageParameter||
|10090|Work Queue||
|10091|Work Queue Item||
|10092|Desktop Flow Binary||
|10093|Flow Log||
|10094|Flow Run||
|10095|Connection Reference||
|10096|DVFileSearch|DVFileSearches Component|
|10097|DVFileSearchAttribute||
|10098|DVFileSearchEntity|DVFileSearchEntities component.|
|10099|DVTableSearch|DVTableSearches component|
|10100|DVTableSearchAttribute|DVTableSearchAttribute component|
|10101|DVTableSearchEntity|DVTableSearchEntities component|
|10102|AICopilot|AI Copilot|
|10103|AIPluginAuth|Entity to store AIPlugin Auth Information|
|10104|AI Plugin Conversation Starter|Conversation Starters for AI Plugins.|
|10105|AI Plugin Conversation Starter Mapping|AIPlugins component|
|10106|AI Plugin Governance||
|10107|AI Plugin Governance Extended||
|10108|AIPluginOperationResponseTemplate|Content for the AI Plugin Operation Response Template|
|10109|AIPluginTitle|AIPlugin Title|
|10110|SideloadedAIPlugin|Sideloaded AIPlugins metadata.|
|10111|AIPlugin|AIPlugins component|
|10112|AIPluginExternalSchema|AIPluginExternalSchemas component|
|10113|AIPluginExternalSchemaProperty|AIPluginExternalSchemaProperties component|
|10114|AIPluginInstance|AI Plugin Instances Component|
|10115|AIPluginOperation|AIPluginOperations component|
|10116|AIPluginOperationParameter|Parameter overrides for AI Operation|
|10117|AIPluginUserSetting||
|10119|AI Event||
|10120|AI Builder Feedback Loop||
|10121|AI Form Processing Document||
|10122|AI Object Detection Image||
|10123|AI Object Detection Label||
|10124|AI Object Detection Bounding Box||
|10125|AI Object Detection Image Mapping||
|10127|AI Builder Dataset||
|10128|AI Builder Dataset File||
|10129|AI Builder Dataset Record||
|10130|AI Builder Datasets Container||
|10131|AI Builder File||
|10132|AI Builder File Attached Data||
|10133|Help Page||
|10134|Tour||
|10135|BotContent||
|10136|ConversationTranscript|Contains the transcripts of conversations between participants such as customers, Virtual Agents or Human agents.|
|10137|Chatbot|Represents a Power Virtual Agents Chatbot. https://powerva.microsoft.com/|
|10138|Chatbot subcomponent|Holds key authoring components of a Chatbot such a topics, entities, variables, etc.|
|10139|Chatbot component collection||
|10150|Comment|A collaborative comment on a maker artifact|
|10151|Fabric AISkill|AISkills published from Fabric.|
|10152|App Insights Metadata|Metadata for App Insights Platform components|
|10153|Dataflow Connection Reference|Intersecting table between Dataflow and Connection Reference|
|10154|Schedule|Generic refresh schedule|
|10155|Dataflow Template|An entity to store information about dataflow templates|
|10156|Dataflow DatalakeFolder||
|10157|Data Movement Service Request|Table for Data Movement Service Requests|
|10158|Data Movement Service Request Status|Table for Data Movement Service Request Status|
|10159|DMS Sync Request|An entity to save DMS sync requests.|
|10160|DMS Sync Status|An entity to save DMS sync statuses.|
|10161|Knowledge Asset Configuration|Knowledge asset configurations for data sources configured in knowledge hub.|
|10162|Module Run Detail|Result of execution of a MEF model|
|10163|Salesforce Structured Object|Entity that represents the Salesforce Structured Object.|
|10164|Salesforce Structured QnA Config|Entity that represents the Salesforce Structured QnA Config.|
|10165|Workflow Action Status|PA Workflows action processing status|
|10166|PDF Setting|PDF Settings to save enabled pdf entities|
|10167|Activity File Attachment|Attachment entity with data stored in file type attribute|
|10168|Teams chat|For internal use only. Entity which stores association data of Dynamics 365 records with Microsoft Teams chat|
|10169|Service Configuration||
|10170|SLA KPI||
|10171|Integrated search provider|Ingest and search files, documents, or articles from data sources outside of your current Dynamics 365 organization with a unified ranking.|
|10172|Knowledge Management Setting|Setup knowledge management for your organization.|
|10173|Knowledge Federated Article||
|10174|Knowledge Federated Article Incident||
|10175|Search provider||
|10176|Knowledge Article Image||
|10177|Knowledge Configuration|Represents the possible settings used in Knowledge management|
|10178|Knowledge Interaction Insight|Knowledge Interaction Insight|
|10179|Knowledge Search Insight|Knowledge Search Insight|
|10180|Favorite knowledge article|Entity for favorite knowledge articles|
|10181|Knowledge article language setting|Allows you to select default language for knowledge authoring.|
|10182|Knowledge Article Attachment||
|10183|Knowledge personalization|Allows users to personalize their knowledge search filters and knowledge authoring language.|
|10184|Knowledge Article Template|Organizational Knowledge Article Template for Internal and external creation of Knowledge Articles.|
|10185|Knowledge search personal filter config|Allows you to configure and manage personal filter settings.|
|10186|Knowledge search filter|Allows you to configure and manage filter settings.|
|10188|SupportUserTable||
|10189|FxExpression||
|10190|PowerfxRule||
|10191|Planner Business Scenario|For internal use only. The Business Scenario record to be created in Planner.|
|10192|Planner Sync Action|The Planner Sync Action to be executed.|
|10193|Ms Graph Resource To Subscription|For internal use only. The mapping between Ms Graph Resources and Subscriptions.|
|10194|Virtual Entity  Metadata|Holds  metadata values for virtual entities|
|10195|Background Operation||
|10196|MobileOfflineProfileExtension||
|10197|MobileOfflineProfileItemFilter||
|10198|TeamMobileOfflineProfileMembership||
|10199|UserMobileOfflineProfileMembership||
|10200|OrganizationDataSyncSubscription||
|10201|OrganizationDataSyncSubscriptionEntity||
|10202|OrganizationDataSyncSubscriptionFnoTable||
|10203|OrganizationDataSyncFnoState|Information regarding data synchronization state|
|10204|OrganizationDataSyncState|Information regarding data synchronization state|
|10205|ArchiveCleanupInfo|This is Deprecated Entity.|
|10206|ArchiveCleanupOperation|This is Deprecated Entity.|
|10207|BulkArchiveConfig|This is Deprecated Entity.|
|10208|BulkArchiveFailureDetail|This is Deprecated Entity.|
|10209|BulkArchiveOperation|This is Deprecated Entity.|
|10210|BulkArchiveOperationDetail|This is Deprecated Entity.|
|10211|EnableArchivalRequest|For internal use only.|
|10212|MetadataForArchival|Holds  metadata values of tables for retention|
|10213|ReconciliationEntityInfo|Table level details of the data lake reconciliation process. For internal use only.|
|10214|ReconciliationEntityStepInfo|Step level details of the data lake reconciliation process. For internal use only.|
|10215|ReconciliationInfo|Information about data lake reconciliation operation. For internal use only.|
|10216|RetentionCleanupInfo|Holds watermark information about retention cleanup operations. For internal use only.|
|10217|RetentionCleanupOperation|Holds data of cleanup operations such as reconcile and purge.  For internal use only.|
|10218|RetentionConfig|Holds retention policies for a table.|
|10219|RetentionFailureDetail|Retention failure details.|
|10220|RetentionOperation|Retention policy execution details.|
|10221|RetentionOperationDetail|Table level details of retention execution.|
|10222|Notification|Notification to be provided to a user.|
|10223|User Rating||
|10224|Mobile App|Mobile App|
|10225|Insights Store Data Source||
|10226|Insights Store Virtual Entity|Insights Store Virtual Entity|
|10227|RoleEditorLayout||
|10228|Deleted Record Reference|Deleted Record Reference|
|10229|Restore Deleted Records Configuration|Holds Restore Deleted Records configuration for entities|
|10230|App Action|Contains Modern Command Information|
|10231|App Action Migration||
|10232|App Action Rule||
|10235|Card|Card|
|10236|Card State Item||
|10239|Entity link chat configuration||
|10240|Rich Text Attachment|Image or file attached to a rich text field|
|10241|Custom Control Extended Setting||
|10242|Timeline Pin|Timeline Pin Record|
|10243|Virtual Connector Data Source||
|10244|Virtual Table Column Candidate||
|10245|PM Analysis History||
|10246|PM Business Rule Automation Config||
|10247|PM Calendar||
|10248|PM Calendar Version||
|10249|PM Inferred Task||
|10250|PM Process Extended Metadata Version||
|10251|PM Process Template||
|10252|PM Process User Settings||
|10253|PM Process Version||
|10254|PM Recording||
|10255|PM Template||
|10256|PM View||
|10257|Analysis Component||
|10258|Analysis Job||
|10259|Analysis Override||
|10260|Analysis Result||
|10261|Analysis Result Detail||
|10262|Solution Health Rule||
|10263|Solution Health Rule Argument||
|10264|Solution Health Rule Set|Represents a set that owns a number of solution health rules.|
|10265|Power BI Dataset||
|10266|powerbidatasetapdx|PowerBI Dataset appendix entity - for unmanaged technical attributes|
|10267|Power BI Mashup Parameter||
|10268|Power BI Report||
|10269|powerbireportapdx|PowerBI Report appendix entity for unmanaged technical attributes|
|10270|File Upload||
|10271|MainFewShot|This fewshot entity will only be updated during solution installation.|
|10272|MakerFewShot|This fewshot is updated by maker for testing the queries and by the NL2SQ with the results|
|10273|SearchAttributeSettings||
|10274|SearchCustomAnalyzer||
|10275|SearchRelationshipSettings||
|10276|SearchResultsCache|Cache search results internally|
|10277|Search Telemetry|Entity to log telemetry that used to improve search quality|
|10278|CopilotExampleQuestion|CopilotExampleQuestions Component|
|10279|CopilotGlossaryTerm|CopilotGlossaryTerm Component|
|10280|CopilotSynonyms|CopilotSynonyms Component|
|10281|Site Component||
|10282|Site||
|10283|Site Language||
|10284|Power Pages Site Published||
|10287|External Identity||
|10288|Invitation|Send invitations to existing contacts or email addresses and assign them to web roles upon redemption.|
|10289|Invite Redemption|Holds information about the redemption of an invite.|
|10290|Portal Comment|An activity which is used to share information between the user and the customer on the portal.|
|10291|Setting||
|10292|Multistep Form Session|Serves as a mechanism to log the occurrence of an incomplete multistep form entry for a given user so they can return and complete it later.|
|10296|Ad Placement||
|10297|Column Permission||
|10298|Column Permission Profile||
|10299|Content Snippet|Content snippets are inserted in page templates so that any label, text string or image in the template can be content-managed.|
|10300|Basic Form|Defines the form to render for a given entity type.|
|10301|Basic Form Metadata|Defines the additional behavior modification logic to augment or override the functionality of form components that is not possible with Dynamics 365 entity and form metadata.|
|10302|List||
|10303|Table Permission||
|10304|Page Template|URL of the .aspx page used to create new webpages.|
|10305|Poll Placement||
|10306|Power Pages Core Entity DS||
|10307|Publishing State||
|10308|Publishing State Transition Rule||
|10309|Redirect||
|10310|Shortcut||
|10311|Site Marker|Used by web page templates to locate a specific page of content.|
|10312|Site Setting|Site specific settings or variables refferenced by the web site code files.|
|10313|Web File|Storage of files used in the web Portals.|
|10314|Multistep Form|Defines the necessary properties and relationships to the other key entities in order to control the initialization of the form within a web portal.|
|10315|Multistep Form Metadata|Defines the additional behavior modification logic to augment or override the functionality of form fields that is not possible with Dynamics 365 entity and form metadata.|
|10316|Form Step|Defines the flow logic of the form's user experience such as steps and conditional branching.|
|10317|Web Link|A textual or imaged based link to an interal or external URL.|
|10318|Web Link Set|A grouping of web links.|
|10319|Web Page|Web Page|
|10320|Web Page Access Control Rule||
|10321|Web Role|Sets the user's role for the Portal.|
|10322|Website|Web Portal|
|10323|Website Access||
|10324|Website Language|Languages supported and publishing status for the portal|
|10325|Web Template||
|10332|Power Pages Scan Report|Power Pages Scan Report|
|10333|Power Pages Log||
|10338|Catalog Submission Files|Files associated with the package that will be used as part of the submission to the catalog system.|
|10339|Package Submission Store|Manages submissions to the Catalog and provisioning|
|18085|Event Expander Breadcrumb|Table to store breadcrumb records of Event Expander pipeline.|



### <a name="BKMK_ComponentIdUnique"></a> ComponentIdUnique

**Added by**: Basic Solution Solution

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Row id unique|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|componentidunique|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_ComponentState"></a> ComponentState

**Added by**: Basic Solution Solution

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Component State|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|componentstate|
|RequiredLevel|SystemRequired|
|Type|Picklist|

#### ComponentState Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|0|Published||
|1|Unpublished||
|2|Deleted||
|3|Deleted Unpublished||



### <a name="BKMK_CreatedBy"></a> CreatedBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who created the duplicate detection rule.|
|DisplayName|Created By|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedByName"></a> CreatedByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedByYomiName"></a> CreatedByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdbyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the duplicate detection rule was created.|
|DisplayName|Created On|
|Format|DateAndTime|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who created the duplicaterule.|
|DisplayName|Created By (Delegate)|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|createdonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_IsManaged"></a> IsManaged

**Added by**: Basic Solution Solution

|Property|Value|
|--------|-----|
|Description|Indicates whether the solution component is part of a managed solution.|
|DisplayName|Is Managed|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|ismanaged|
|RequiredLevel|SystemRequired|
|Type|Boolean|

#### IsManaged Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Managed||
|0|Unmanaged||

**DefaultValue**: 0



### <a name="BKMK_MatchingEntityMatchCodeTable"></a> MatchingEntityMatchCodeTable

|Property|Value|
|--------|-----|
|Description|Database table that stores match codes for potential duplicate records.|
|DisplayName|Matching Record Type Match Code Table|
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|matchingentitymatchcodetable|
|MaxLength|50|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_MatchingEntityTypeCode"></a> MatchingEntityTypeCode

|Property|Value|
|--------|-----|
|Description|Record type of the records being evaluated as potential duplicates.|
|DisplayName|Matching Record Type|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|matchingentitytypecode|
|RequiredLevel|SystemRequired|
|Type|Picklist|

#### MatchingEntityTypeCode Choices/Options

|Value|Label|Description|
|-----|-----|--------|
|1|Account|Business that represents a customer or potential customer. The company that is billed in business transactions.|
|2|Contact|Person with whom a business unit has a relationship, such as customer, supplier, and colleague.|
|5|Note|Note that is attached to one or more objects, including other notes.|
|6|Business Unit Map|Stores mapping attributes for business units.|
|7|Owner|Group of undeleted system users and undeleted teams. Owners can be used to control access to specific objects.|
|8|User|Person with access to the Microsoft CRM system and who owns objects in the Microsoft CRM database.|
|9|Team|Collection of system users that routinely collaborate. Teams can be used to simplify record sharing and provide team members with common access to organization data when team members belong to different Business Units.|
|10|Business Unit|Business, division, or department in the Microsoft Dynamics 365 database.|
|14|System User Principal|For internal use only.|
|29|Subscription|For internal use only.|
|30|Filter Template|Template for a filter.|
|31|Privilege Object Type Code|For internal use only.|
|33|Subscription Synchronization Information|For internal use only.|
|35|Tracking information for deleted entities|For internal use only.|
|36|Client update|Microsoft Dynamics 365 client for Outlook offline database update.|
|37|Subscription Manually Tracked Object|For internal use only.|
|42|SystemUser BusinessUnit Entity Map|Stores mapping attributes for business units.|
|44|Field Sharing|Defines CRM security principals (users and teams) access rights to secured field for an entity instance.|
|45|Subscription Statistic Offline|Subscription Statistic Offline|
|46|Subscription Statistic Outlook|Subscription Statistic Outlook|
|47|Subscription Sync Entry Offline|Used for offline sync, internal use only.|
|48|Subscription Sync Entry Outlook|Used for outlook sync, internal use only.|
|50|Position|Position of a user in the hierarchy|
|51|System User Manager Map|For internal use only.|
|52|User Search Facet||
|54|Global Search Configuration||
|55|FileAttachment|File Attachment|
|60|SystemUserAuthorizationChangeTracker|Internal authorization table to track user authorization changes|
|61|PrincipalEntityBusinessUnitMap|Internal authorization table to track user authorization changes|
|72|Record Filter|Record Access Filter|
|73|EntityRecordFilter|RecordFilter Object Type Codes|
|74|Secured Masking Rule|Secured Masking Rules to apply to fields.|
|78|Virtual Entity Data Provider|Developers can register plug-ins on a data provider to enable data access for virtual entities in the system.|
|85|Virtual Entity Data Source|Internal entity that stores data source information for all installed providers.|
|92|Team template|Team template for an entity enabled for automatically created access teams.|
|99|Social Profile|This entity is used to store social profile information of its associated account and contacts on different social channels.|
|101|Service Plan|Service Plan|
|103|Privileges Removal Setting|Privileges Removal Setting|
|126|Indexed Article|Article indexed for search purposes.|
|127|Article|Structured content that is part of the knowledge base.|
|129|Subject|Information regarding subjects available in the system.|
|132|Announcement|Announcement associated with an organization.|
|135|Activity Party|Person or group associated with an activity. An activity can have multiple activity parties.|
|150|User Settings|User's preferred settings.|
|300|Canvas App|An application built through a canvas-based editing experience.|
|301|Callback Registration|Callback Registration that stores configuration.|
|372|Connector|Connector Entity to support Solutioning Integration|
|373|Connection Instance||
|380|Environment Variable Definition|Contains information about the settable variable: its type, default value, and etc.|
|381|Environment Variable Value|Holds the value for the associated EnvironmentVariableDefinition entity.|
|400|AI Template||
|401|AI Model||
|402|AI Configuration||
|418|Dataflow||
|430|Entity Analytics Config|This entity contains information about which entities are enabled for Azure Data Lake Services integration|
|431|Image Attribute Configuration|Store configuration for each image attribute|
|432|Entity Image Configuration|Store image configuration for each entity|
|950|New Process|New Process Business Process Flow|
|951|Translation Process|Translation Process Business Process Flow|
|955|Expired Process|Expired Process Business Process Flow|
|1001|Attachment|MIME attachment for an activity.|
|1002|Attachment|Attachment for an email activity.|
|1003|Internal Address|Storage of addresses for a user, business unit, or site.|
|1007|Image Descriptor|For internal use only.|
|1016|Article Template|Template for a knowledge base article that contains the standard attributes of an article.|
|1019|Organization|Top level of the Microsoft Dynamics 365 business hierarchy. The organization can be a specific business, holding company, or corporation.|
|1021|Organization UI|Entity customizations including form layout and icons. Includes current and past versions.|
|1023|Privilege|Permission to perform an action in Microsoft CRM. The platform checks for the privilege and rejects the attempt if the user does not hold the privilege.|
|1030|System Form|Organization-owned entity customizations including form layout and dashboards.|
|1031|User Dashboard|User-owned dashboards.|
|1036|Security Role|Grouping of security privileges. Users are assigned roles that authorize their access to the Microsoft CRM system.|
|1037|Role Template|Template for a role. Defines initial attributes that will be used when creating a new role.|
|1039|View|Saved query against the database.|
|1043|String Map|Mapping between strings.|
|1071|Address|Address and shipping information. Used to store additional addresses for an account or contact.|
|1072|Subscription Clients|For internal use only.|
|1075|Status Map|Mapping between statuses.|
|1082|Article Comment|Comment on a knowledge base article.|
|1086|User Fiscal Calendar|Custom fiscal calendar used for tracking sales quotas.|
|1094|Authorization Server|Authorization servers that trust this organization|
|1095|Partner Application|Partner applications registered for this organization|
|1111|System Chart|System chart attached to an entity.|
|1112|User Chart|Chart attached to an entity.|
|1113|Ribbon Tab To Command Mapping|A mapping between Tab Ids, and the Commands within those tabs.|
|1115|Ribbon Context Group|Groupings of contextual tabs.|
|1116|Ribbon Command|Ribbon Commands - the command definition, rules, etc.|
|1117|Ribbon Rule|Ribbon rule definitions, used to enable and disable, show and hide ribbon elements.|
|1120|Application Ribbons|Ribbon customizations for the application ribbon and entity ribbon templates.|
|1130|Ribbon Difference|All layout customizations to be applied to the ribbons, which contain only the differences from the base ribbon.|
|1140|Replication Backlog|Entity to hold replication backlog tasks. For internal use only.|
|1189|Document Suggestions|Document Suggestions|
|1190|SuggestionCardTemplate|Templates for Suggestion Card in Grid|
|1200|Field Security Profile|Profile which defines access level for secured attributes|
|1201|Field Permission|Group of privileges used to categorize users to provide appropriate access to secured columns.|
|1203|Team Profiles|Team Profiles|
|1204|Application|Application|
|1234|Channel Property Group|Group or collection of channel properties provided by the external channel for a Microsoft Dynamics 365 activity.|
|1236|Channel Property|Instance of a channel property containing its name and corresponding data type.|
|1300|SocialInsightsConfiguration|Configuration for the social insights.|
|1309|Saved Organization Insights Configuration|Saved configuration for the organization insights|
|1400|Sync Attribute Mapping Profile|Profile which defines sync attribute mapping|
|1401|Sync Attribute Mapping|Group of Sync-Attribute Mappings used to provide Attribute mappings during sync for a particular user|
|1403|Team Sync-Attribute Mapping Profiles|Team Sync-Attribute Mapping Profiles|
|1404|Principal Sync Attribute Map|Maps security principals (users and teams) to sync attribute mappings.|
|2000|Annual Fiscal Calendar|Year long fiscal calendar of an organization. A span of time during which the financial activities of an organization are calculated.|
|2001|Semiannual Fiscal Calendar|Calendar representing the semi-annual span of time during which the financial activities of an organization are calculated.|
|2002|Quarterly Fiscal Calendar|Quarterly fiscal calendar of an organization. A span of time during which the financial activities of an organization are calculated.|
|2003|Monthly Fiscal Calendar|Monthly fiscal calendar of an organization. A span of time during which the financial activities of an organization are calculated.|
|2004|Fixed Monthly Fiscal Calendar|Fixed monthly fiscal calendar of an organization. A span of time during which the financial activities of an organization are calculated.|
|2010|Email Template|Template for an email message that contains the standard attributes of an email message.|
|2012|Unresolved Address|For internal use only.|
|2013|Territory|Territory represents sales regions.|
|2015|Theme|Information that's used to set custom visual theme options for client applications.|
|2016|User Mapping|User Mapping|
|2020|Queue|A list of records that require action, such as accounts, activities, and cases.|
|2023|QueueItemCount|For internal use only.|
|2024|QueueMemberCount|For internal use only.|
|2027|License|Stores information about a Microsoft CRM license.|
|2029|Queue Item|A specific item in a queue, such as a case record or an activity record.|
|2500|User Entity UI Settings|Stores user settings for entity views.|
|2501|User Entity Instance Data|Per User item instance data|
|3000|Integration Status|Contains integration status information.|
|3005|Channel Access Profile|Information about permissions needed to access Dynamics 365 through external channels.For internal use only|
|3008|External Party|Information about external parties that need to access Dynamics 365 from external channels.For internal use only|
|3231|Connection Role|Role describing a relationship between a two records.|
|3233|Connection Role Object Type Code|Specifies the entity type that can play specific role in a connection.|
|3234|Connection|Relationship between two entities.|
|4003|Calendar|Calendar used by the scheduling system to define when an appointment or activity is to occur.|
|4004|Calendar Rule|Defines free/busy times for a service and for resources or resource groups, such as working, non-working, vacation, and blocked.|
|4011|Inter Process Lock|Inter Process Locks.|
|4023|Email Hash|Email activity hashes used for correlation purposes.|
|4101|Display String Map|Maps customized display strings to entities.|
|4102|Display String|Customized messages for an entity that has been renamed.|
|4110|Notification|For internal use only.|
|4120|Exchange Sync Id Mapping|The mapping used to keep track of the IDs for items synced between CRM and Exchange.|
|4200|Activity|Task performed, or to be performed, by a user. An activity is any action for which an entry can be made on a calendar.|
|4201|Appointment|Commitment representing a time interval with start/end times and duration.|
|4202|Email|Activity that is delivered using email protocols.|
|4204|Fax|Activity that tracks call outcome and number of pages for a fax and optionally stores an electronic copy of the document.|
|4207|Letter|Activity that tracks the delivery of a letter. The activity can contain the electronic copy of the letter.|
|4210|Phone Call|Activity to track a telephone call.|
|4212|Task|Generic activity representing work needed to be done.|
|4216|Social Activity|For internal use only.|
|4220|UntrackedEmail|Activity that is delivered using UntrackedEmail protocols.|
|4230|Saved View|Saved database query that is owned by a user.|
|4231|Metadata Difference|Metadata Difference|
|4232|Business Data Localized Label|Business Data Localized Label|
|4250|Recurrence Rule|Recurrence Rule represents the pattern of incidence of recurring entities.|
|4251|Recurring Appointment|The Master appointment of a recurring appointment series.|
|4299|Email Search|Email Address Search Table.|
|4410|Data Import|Status and ownership information for an import job.|
|4411|Data Map|Data map used in import.|
|4412|Import Source File|File name of file used for import.|
|4413|Import Data|Unprocessed data from imported files.|
|4414|Duplicate Detection Rule|Rule used to identify potential duplicates.|
|4415|Duplicate Record|Potential duplicate record.|
|4416|Duplicate Rule Condition|Condition of a duplicate detection rule.|
|4417|Column Mapping|Mapping for columns in a data map.|
|4418|List Value Mapping|In a data map, maps list values from the source file to Microsoft Dynamics 365.|
|4419|Lookup Mapping|In a data map, maps a lookup attribute in a source file to Microsoft Dynamics 365.|
|4420|Owner Mapping|In a data map, maps ownership data from the source file to Microsoft Dynamics 365.|
|4423|Import Log|Failure reason and other detailed information for a record that failed to import.|
|4424|Bulk Delete Operation|User-submitted bulk deletion job.|
|4425|Bulk Delete Failure|Record that was not deleted during a bulk deletion job.|
|4426|Transformation Mapping|In a data map, maps the transformation of source attributes to Microsoft Dynamics 365 attributes.|
|4427|Transformation Parameter Mapping|In a data map, defines parameters for a transformation.|
|4428|Import Entity Mapping|Mapping for entities in a data map.|
|4450|Data Performance Dashboard|Data Performance Dashboard.|
|4490|Office Document|Used to store Office Documents in database in binary format.|
|4500|Relationship Role|Relationship between an account or contact and an opportunity.|
|4501|Relationship Role Map|Mapping of the primary associated objects between which the relationship role is valid.|
|4502|Customer Relationship|Relationship between a customer and a partner in which either can be an account or contact.|
|4567|Auditing|Track changes to records for analysis, record keeping, and compliance.|
|4579|Ribbon Client Metadata.|A ribbon client metadata.|
|4600|Entity Map|Represents a mapping between two related entities so that data from one record can be copied into the form of a new related record.|
|4601|Attribute Map|Represents a mapping between attributes where the attribute values should be copied from a record into the form of a new related record.|
|4602|Plug-in Type|Type that inherits from the IPlugin interface and is contained within a plug-in assembly.|
|4603|Plug-in Type Statistic|Plug-in type statistic.|
|4605|Plug-in Assembly|Assembly that contains one or more plug-in types.|
|4606|Sdk Message|Message that is supported by the SDK.|
|4607|Sdk Message Filter|Filter that defines which SDK messages are valid for each type of entity.|
|4608|Sdk Message Processing Step|Stage in the execution pipeline that a plug-in is to execute.|
|4609|Sdk Message Request|For internal use only.|
|4610|Sdk Message Response|For internal use only.|
|4611|Sdk Message Response Field|For internal use only.|
|4613|Sdk Message Pair|For internal use only.|
|4614|Sdk Message Request Field|For internal use only.|
|4615|Sdk Message Processing Step Image|Copy of an entity's attributes before or after the core system operation.|
|4616|Sdk Message Processing Step Secure Configuration|Non-public custom configuration that is passed to a plug-in's constructor.|
|4618|Service Endpoint|Service endpoint that can be contacted.|
|4619|Plug-in Trace Log|Trace and exception information generated by plug-ins and custom workflow activities.|
|4700|System Job|Process whose execution can proceed independently or in the background.|
|4702|Workflow Wait Subscription|For internal use only.|
|4703|Process|Set of logical rules that define the steps necessary to automate a specific business process, task, or set of actions to be performed.|
|4704|Process Dependency|Dependencies for a process.|
|4705|ISV Config|An XML document used to configure client extension controls.|
|4706|Process Log|Log used to track process execution.|
|4707|Application File|Files used by the application|
|4708|Organization Statistic|Statistics measuring the organization's usage of the Microsoft Dynamics 365 system over the past 24 hours.|
|4709|Site Map|XML data used to control the application navigation pane.|
|4710|Process Session|Information that is generated when a dialog is run. Every time that you run a dialog, a dialog session is created.|
|4711|Expander Event|For internal use only. An event that will be expanded into jobs whose executions can proceed in the background.|
|4712|Process Trigger|Trigger that invoke a rule.|
|4720|Flow Session|Entity to store the information that is generated when a Power Automate Desktop flow runs.|
|4724|Process Stage|Stage associated with a process.|
|4725|Business Process Flow Instance|Active path associated with every Business Process Flow instance|
|4800|Web Wizard|Definition for a Web-based wizard.|
|4802|Wizard Page|Page in a Web-based wizard.|
|4803|Web Wizard Access Privilege|Privilege needed to access a Web-based wizard.|
|4810|Time Zone Definition|Time zone definition, including name and time zone code.|
|4811|Time Zone Rule|Definition for time conversion between local time and Coordinated Universal Time (UTC) for a particular time zone at a particular time period.|
|4812|Time Zone Localized Name|Localized name of the time zone.|
|5000|Recently Used|Most recently used data table.|
|5004|NL2SQ Registration Information|Org registration status, AllowedEntity list, and registration error message.|
|7000|System Application Metadata|For internal use only.|
|7001|User Application Metadata|For internal use only.|
|7100|Solution|A solution which contains CRM customizations.|
|7101|Publisher|A publisher of a CRM solution.|
|7102|Publisher Address|Address and shipping information. Used to store additional addresses for a publisher.|
|7103|Solution Component|A component of a CRM solution.|
|7104|Solution Component Definition|Contains all the information required to process a solution aware entity|
|7105|Dependency|A component dependency in CRM.|
|7106|Dependency Node|The representation of a component dependency node in CRM.|
|7107|Invalid Dependency|An invalid dependency in the CRM system.|
|7108|Dependency Feature|A dependency feature.|
|7200|RuntimeDependency|Form Level dependencies in CRM.|
|7755|ElasticFileAttachment|Elastic File Attachment|
|8000|Post|An activity feed post.|
|8001|Post Role|Represents the objects with which an activity feed post is associated. For internal use only.|
|8002|Post Regarding|Represents which object an activity feed post is regarding. For internal use only.|
|8003|Follow|Represents a user following the activity feed of an object.|
|8005|Comment|A comment on an activity feed post.|
|8006|Like|A like on an activity feed post.|
|8040|ACIViewMapper|Customized messages for an entity that has been renamed.|
|8050|Trace|A trace log.|
|8051|Trace Association|Represents the objects with which a trace record is associated. For internal use only.|
|8052|Trace Regarding|Represents which object a trace record is regarding. For internal use only.|
|8181|Routing Rule Set|Define Routing Rule to route cases to right people at the right time|
|8199|Rule Item|Please provide the description for entity|
|8700|AppModule Metadata|For internal use only.|
|8701|AppModule Metadata Dependency|For internal use only.|
|8702|AppModule Metadata Async Operation|For internal use only.|
|8840|Hierarchy Rule|Organization-owned entity customizations including mapping Quick view form with Relationship Id|
|9006|Model-driven App|A role-based, modular business app that provides task-based functionality for a particular area of work.|
|9007|App Module Component|A component available in a business app such as entity, dashboard, form, view, chart, and business process.|
|9009|App Module Roles|Security roles that have access to a business app.|
|9011|App Config Master|Contains the master list of all properties that can be customized for apps in Dynamics 365. For internal use only.|
|9012|App Configuration|Contains a mapping between an app configuration instance and an app, which defines the properties that can be customized for the app. Optionally, also contains navigation setting for an app. For internal use only.|
|9013|App Configuration Instance|Contains a property or a list of properties from the app configuration master list that can be customized for any app in Dynamics 365. For internal use only.|
|9100|Report|Data summary in an easy-to-read layout.|
|9101|Report Related Entity|Entities related to a report. A report can be related to multiple entities.|
|9102|Report Related Category|Categories related to a report. A report can be related to multiple categories.|
|9103|Report Visibility|Area in which to show a report. A report can be shown in multiple areas.|
|9104|Report Link|Links and dependencies between reports. A report may drill through to another report, or it may have another report as a sub-report.|
|9105|Currency|Currency in which a financial transaction is carried out.|
|9106|Mail Merge Template|Template for a mail merge document that contains the standard attributes of that document.|
|9107|Import Job|For internal use only.|
|9201|LocalConfigStore||
|9300|Record Creation and Update Rule|Defines the settings for automatic record creation.|
|9301|Record Creation and Update Rule Item|Defines the individual conditions required for creating records automatically.|
|9333|Web Resource|Data equivalent to files used in Web development. Web resources provide client-side components that are used to provide custom user interface elements.|
|9400|Channel Access Profile Rule|Defines the rules for automatically associating channel access profiles to external party records.For internal use only|
|9401|Channel Access Profile Rule Item|Defines the rule items of a profile rule set for the automated profile association.For internal use only|
|9502|SharePoint Site|SharePoint site from where documents can be managed in Microsoft Dynamics 365.|
|9507|Sharepoint Document|Document libraries or folders on a SharePoint server from where documents can be managed in Microsoft Dynamics 365.|
|9508|Document Location|Document libraries or folders on a SharePoint server from where documents can be managed in Microsoft Dynamics 365.|
|9509|SharePoint Data|SharePoint's Data Corresponding to a user , Record , Location and Page|
|9510|Rollup Properties|Stores properties related to rollup fields.|
|9511|Rollup Job|Stores rollup jobs.|
|9600|Goal|Target objective for a user or a team for a specified time period.|
|9602|Rollup Query|Query that is used to filter the results of the goal rollup.|
|9603|Goal Metric|Type of measurement for a goal, such as money amount or count.|
|9604|Rollup Field|Field to be rolled up to calculate the actual and in-progress values against the goal.|
|9605|Email Server Profile|Holds the Email Server Profiles of an organization|
|9606|Mailbox||
|9607|Mailbox Statistics|Stores data regarding Mailbox processing cycles|
|9608|Mailbox Auto Tracking Folder|Stores data about what folders for a mailbox are auto tracked|
|9609|Mailbox Tracking Category|Stores data about what categories for a mailbox are tracked|
|9650|Process Configuration|For internal use only.|
|9690|Organization Insights Notification|Stores data regarding organization insights notification|
|9699|Organization Insights Metric|Stores data regarding organization insights metric|
|9750|SLA|Contains information about the tracked service-level KPIs for cases that belong to different customers.|
|9751|SLA Item|Contains information about a tracked support KPI for a specific customer.|
|9752|SLA KPI Instance|Service level agreement (SLA) key performance indicator (KPI) instance that is tracked for an individual case|
|9753|Custom Control|For internal use only.|
|9754|Custom Control Resource|Custom Control Resource Id|
|9755|Custom Control Default Config|For internal use only.|
|9800|Entity||
|9808|Attribute||
|9809|OptionSet||
|9810|Entity Key||
|9811|Entity Relationship||
|9812|Managed Property||
|9813|Relationship Entity||
|9814|Relationship Attribute|Stores relationship attributes mapping for Multi-predicate relationship|
|9815|Entity Index|Metadata describing index of an entity|
|9816|Index Attribute|Stores index attributes|
|9820|Secured Masking Column|Defines secured masking rule for column|
|9866|Mobile Offline Profile|Information to administer and manage the data available to mobile devices in offline mode.|
|9867|Mobile Offline Profile Item|Information on entity availability to mobile devices in offline mode for a mobile offline profile item.|
|9868|Mobile Offline Profile Item Association|Information on relationships to be used to follow related entity's records for mobile offline profile item.|
|9869|Sync Error|Failure reason and other detailed information for a record that failed to sync.|
|9870|Offline Command Definition|For internal use only.|
|9875|Language Provisioning State|Container for language provisioning checkpoint states|
|9880|Ribbon Metadata To Process|Container for Ribbon Metadata To Process|
|9890|SolutionHistoryData|solution history data|
|9900|Navigation Setting|Navigation Setting: A setting page or group of pages available for configuration within an app. A record representing a group of pages is regarded as the parent navigation setting of one or more other records. For internal use only.|
|9910|MultiEntitySearch|Multi Entity Search.|
|9912|Multi Select Option Value|Multi Select Option Value|
|9919|Hierarchy Security Configuration||
|9930|Knowledge Base Record|Metadata of knowledge base (KB) articles associated with Microsoft Dynamics 365 entities.|
|9932|Time Stamp Date Mapping|For internal use only.`|
|9936|Azure Service Connection|Stores connection information for an Azure service|
|9940|Document Template|Used to store Document Templates in database in binary format.|
|9941|Personal Document Template|Used to store Personal Document Templates in database in binary format.|
|9945|Text Analytics Entity Mapping||
|9947|Knowledge Search Model|Configuration for automatic suggestion of knowledge articles using text analytics and search|
|9949|Advanced Similarity Rule|A text match rule identifies similar records using keywords and key phrases determined with text analytics|
|9950|Office Graph Document|Office Graph Documents Description|
|9951|Similarity Rule||
|9953|Knowledge Article|Organizational knowledge for internal and external use.|
|9955|Knowledge Article Views|No of times an article is viewed per day|
|9957|Language|Language|
|9958|Feedback|Feedback and rating.|
|9959|Category|Entity for categorizing records to make it easier for your customers to find them on portals and through search.|
|9960|Knowledge Article Category|Category for a Knowledge Article.|
|9961|DelveActionHub|Delve Action Hubs Description|
|9962|Action Card|Action card entity to show action cards.|
|9968|ActionCardUserState||
|9973|Action Card User Settings|Stores user settings for action cards|
|9983|Action Card Type|To provide master data for the card types list. For internal use only|
|9986|Interaction for Email||
|9987|External Party Item|Information about external party items that need to access Dynamics 365 from external channels.For internal use only|
|9996|HolidayWrapper||
|9997|Email Signature|Signature for email message|
|10000|Solution Component Attribute Configuration||
|10001|Solution Component Batch Configuration||
|10002|Solution Component Configuration||
|10003|Solution Component Relationship Configuration||
|10004|Solution History||
|10005|Solution History Data Source||
|10006|Component Layer||
|10007|Component Layer Data Source||
|10008|Package||
|10009|Package History||
|10011|StageSolutionUpload||
|10012|ExportSolutionUpload||
|10013|FeatureControlSetting|featurecontrolsetting|
|10014|Solution Component Summary||
|10015|Solution Component Count Summary||
|10016|Solution Component Data Source||
|10017|Solution Component Count Data Source||
|10018|Microsoft Entra ID|Virtual entity that represents Microsoft Entra ID|
|10019|Staged Entity|Stores staged entity metadata to be processed before fully created.|
|10020|Staged Entity Attribute|Stores staged entity attribute metadata to be processed in async.|
|10021|Staged Metadata Async Operation|Stores staged entity metadata to be processed before fully created.|
|10022|Key Vault Reference|Contains data that refers to an Azure Key Vault containing credentials used to connect to secure web-hosted resources.|
|10023|Managed Identity|Contains data to represent an Azure Active Directory Application used to connect to secure web-hosted resources.|
|10024|Catalog|Entity for cataloging records to make it easier for your customers to find them on portals and through search.|
|10025|Catalog Assignment|Entity for assigning records to a specific catalog |
|10026|Internal Catalog Assignment||
|10027|Custom API|Entity that defines a custom API|
|10028|Custom API Request Parameter|Entity that defines a request parameter for a custom API|
|10029|Custom API Response Property|Entity that defines a response property for a custom API |
|10030|Plugin Package||
|10031|NonRelational Data Source||
|10032|ProvisionLanguageForUser||
|10033|Shared Object|A record that is being shared in a real time collaboration session.|
|10034|Shared Workspace|References a container that stores real-time collaboration data.|
|10035|Shared Workspace Access Token|Contains information about the shared workspace access tokens.|
|10036|Shared Workspace Non-Relational|References a container that stores real-time collaboration data.|
|10037|Shared Workspace Pool|Contains metadata about a container used to store real-time collaboration data. Once claimed, a sharedworkspace record would be created with copied metadata.|
|10038|Data Lake Folder|A folder is a place to store data in Azure Data Lake.|
|10039|Data Lake Folder Permission||
|10040|Data Lake Workspace|A workspace is a place to store data in Azure Data Lake.|
|10041|Data Lake Workspace Permission||
|10042|Data Processing configuration||
|10043|Exported Excel|A Place holder entity to save excel file for each exportretaineddata custom api requests.|
|10044|RetainedData Excel|A Place holder entity to save excel file for each exportretaineddata custom api requests.|
|10045|Synapse Database|This entity represents an external Synapse database and its associated datalake folder link.|
|10046|Synapse Link External Table State|Synapse Link external table states|
|10047|Synapse Link Profile|Synapse Link Profile|
|10048|Synapse Link Profile Entity|Entities associated with the Synapse Link profile|
|10049|Synapse Link Profile Entity State|Runtime state of the Synapse Link entity|
|10050|Synapse Link Schedule|Synapse link schedules|
|10051|Component Version||
|10052|Component Version Data Source||
|10053|Component Version (Internal)||
|10054|DataflowRefreshHistory||
|10055|EntityRefreshHistory||
|10056|Shared Link Setting|Shared Link Setting|
|10057|DelegatedAuthorization|Context for delegated authorization.|
|10059|CascadeGrantRevokeAccessRecordsTracker||
|10060|CascadeGrantRevokeAccessVersionTracker||
|10061|RevokeInheritedAccessRecordsTracker||
|10062|TdsMetadata||
|10063|Model-Driven App Element|Associates a model-driven app with its components.|
|10064|Model-Driven App Component Node's Edge|Contains Model-Driven App Component Node's Edge Information.|
|10065|Model-Driven App Component Node|Contains Model-Driven App Component Node Information|
|10066|Model-Driven App Setting|Holds the value for the associated App Setting Definition.|
|10067|Model-Driven App User Setting|Holds the value for the associated App User Setting Definition.|
|10068|Organization Setting|Holds the value for the associated Organization Setting Definition.|
|10069|Setting Definition|Contains Setting Definitions|
|10070|CanvasApp Extended Metadata|Holds extended metadata values for canvas apps that are not solution aware|
|10071|Service Plan Mapping|Service Plan Mapping|
|10072|Service Plan Custom Control|Service Plan Custom Controls|
|10074|ApplicationUser|Application User that has non-interactive access to the CDS system|
|10077|OData v4 Data Source|Data sources used by the OData v4 data provider to access data from an external web service.|
|10078|Workflow Binary||
|10079|Credential||
|10080|Desktop Flow Module||
|10081|Flow Capacity Assignment|Capacity assignment for usage in Power Automate|
|10082|Flow Credential Application||
|10083|Flow Event|Entity to store the events that happen during usage of Power Automate.|
|10084|Flow Machine||
|10085|Flow Machine Group||
|10086|Flow Machine Image||
|10087|Flow Machine Image Version||
|10088|Flow Machine Network||
|10089|ProcessStageParameter||
|10090|Work Queue||
|10091|Work Queue Item||
|10092|Desktop Flow Binary||
|10093|Flow Log||
|10094|Flow Run||
|10095|Connection Reference||
|10096|DVFileSearch|DVFileSearches Component|
|10097|DVFileSearchAttribute||
|10098|DVFileSearchEntity|DVFileSearchEntities component.|
|10099|DVTableSearch|DVTableSearches component|
|10100|DVTableSearchAttribute|DVTableSearchAttribute component|
|10101|DVTableSearchEntity|DVTableSearchEntities component|
|10102|AICopilot|AI Copilot|
|10103|AIPluginAuth|Entity to store AIPlugin Auth Information|
|10104|AI Plugin Conversation Starter|Conversation Starters for AI Plugins.|
|10105|AI Plugin Conversation Starter Mapping|AIPlugins component|
|10106|AI Plugin Governance||
|10107|AI Plugin Governance Extended||
|10108|AIPluginOperationResponseTemplate|Content for the AI Plugin Operation Response Template|
|10109|AIPluginTitle|AIPlugin Title|
|10110|SideloadedAIPlugin|Sideloaded AIPlugins metadata.|
|10111|AIPlugin|AIPlugins component|
|10112|AIPluginExternalSchema|AIPluginExternalSchemas component|
|10113|AIPluginExternalSchemaProperty|AIPluginExternalSchemaProperties component|
|10114|AIPluginInstance|AI Plugin Instances Component|
|10115|AIPluginOperation|AIPluginOperations component|
|10116|AIPluginOperationParameter|Parameter overrides for AI Operation|
|10117|AIPluginUserSetting||
|10119|AI Event||
|10120|AI Builder Feedback Loop||
|10121|AI Form Processing Document||
|10122|AI Object Detection Image||
|10123|AI Object Detection Label||
|10124|AI Object Detection Bounding Box||
|10125|AI Object Detection Image Mapping||
|10127|AI Builder Dataset||
|10128|AI Builder Dataset File||
|10129|AI Builder Dataset Record||
|10130|AI Builder Datasets Container||
|10131|AI Builder File||
|10132|AI Builder File Attached Data||
|10133|Help Page||
|10134|Tour||
|10135|BotContent||
|10136|ConversationTranscript|Contains the transcripts of conversations between participants such as customers, Virtual Agents or Human agents.|
|10137|Chatbot|Represents a Power Virtual Agents Chatbot. https://powerva.microsoft.com/|
|10138|Chatbot subcomponent|Holds key authoring components of a Chatbot such a topics, entities, variables, etc.|
|10139|Chatbot component collection||
|10150|Comment|A collaborative comment on a maker artifact|
|10151|Fabric AISkill|AISkills published from Fabric.|
|10152|App Insights Metadata|Metadata for App Insights Platform components|
|10153|Dataflow Connection Reference|Intersecting table between Dataflow and Connection Reference|
|10154|Schedule|Generic refresh schedule|
|10155|Dataflow Template|An entity to store information about dataflow templates|
|10156|Dataflow DatalakeFolder||
|10157|Data Movement Service Request|Table for Data Movement Service Requests|
|10158|Data Movement Service Request Status|Table for Data Movement Service Request Status|
|10159|DMS Sync Request|An entity to save DMS sync requests.|
|10160|DMS Sync Status|An entity to save DMS sync statuses.|
|10161|Knowledge Asset Configuration|Knowledge asset configurations for data sources configured in knowledge hub.|
|10162|Module Run Detail|Result of execution of a MEF model|
|10163|Salesforce Structured Object|Entity that represents the Salesforce Structured Object.|
|10164|Salesforce Structured QnA Config|Entity that represents the Salesforce Structured QnA Config.|
|10165|Workflow Action Status|PA Workflows action processing status|
|10166|PDF Setting|PDF Settings to save enabled pdf entities|
|10167|Activity File Attachment|Attachment entity with data stored in file type attribute|
|10168|Teams chat|For internal use only. Entity which stores association data of Dynamics 365 records with Microsoft Teams chat|
|10169|Service Configuration||
|10170|SLA KPI||
|10171|Integrated search provider|Ingest and search files, documents, or articles from data sources outside of your current Dynamics 365 organization with a unified ranking.|
|10172|Knowledge Management Setting|Setup knowledge management for your organization.|
|10173|Knowledge Federated Article||
|10174|Knowledge Federated Article Incident||
|10175|Search provider||
|10176|Knowledge Article Image||
|10177|Knowledge Configuration|Represents the possible settings used in Knowledge management|
|10178|Knowledge Interaction Insight|Knowledge Interaction Insight|
|10179|Knowledge Search Insight|Knowledge Search Insight|
|10180|Favorite knowledge article|Entity for favorite knowledge articles|
|10181|Knowledge article language setting|Allows you to select default language for knowledge authoring.|
|10182|Knowledge Article Attachment||
|10183|Knowledge personalization|Allows users to personalize their knowledge search filters and knowledge authoring language.|
|10184|Knowledge Article Template|Organizational Knowledge Article Template for Internal and external creation of Knowledge Articles.|
|10185|Knowledge search personal filter config|Allows you to configure and manage personal filter settings.|
|10186|Knowledge search filter|Allows you to configure and manage filter settings.|
|10188|SupportUserTable||
|10189|FxExpression||
|10190|PowerfxRule||
|10191|Planner Business Scenario|For internal use only. The Business Scenario record to be created in Planner.|
|10192|Planner Sync Action|The Planner Sync Action to be executed.|
|10193|Ms Graph Resource To Subscription|For internal use only. The mapping between Ms Graph Resources and Subscriptions.|
|10194|Virtual Entity  Metadata|Holds  metadata values for virtual entities|
|10195|Background Operation||
|10196|MobileOfflineProfileExtension||
|10197|MobileOfflineProfileItemFilter||
|10198|TeamMobileOfflineProfileMembership||
|10199|UserMobileOfflineProfileMembership||
|10200|OrganizationDataSyncSubscription||
|10201|OrganizationDataSyncSubscriptionEntity||
|10202|OrganizationDataSyncSubscriptionFnoTable||
|10203|OrganizationDataSyncFnoState|Information regarding data synchronization state|
|10204|OrganizationDataSyncState|Information regarding data synchronization state|
|10205|ArchiveCleanupInfo|This is Deprecated Entity.|
|10206|ArchiveCleanupOperation|This is Deprecated Entity.|
|10207|BulkArchiveConfig|This is Deprecated Entity.|
|10208|BulkArchiveFailureDetail|This is Deprecated Entity.|
|10209|BulkArchiveOperation|This is Deprecated Entity.|
|10210|BulkArchiveOperationDetail|This is Deprecated Entity.|
|10211|EnableArchivalRequest|For internal use only.|
|10212|MetadataForArchival|Holds  metadata values of tables for retention|
|10213|ReconciliationEntityInfo|Table level details of the data lake reconciliation process. For internal use only.|
|10214|ReconciliationEntityStepInfo|Step level details of the data lake reconciliation process. For internal use only.|
|10215|ReconciliationInfo|Information about data lake reconciliation operation. For internal use only.|
|10216|RetentionCleanupInfo|Holds watermark information about retention cleanup operations. For internal use only.|
|10217|RetentionCleanupOperation|Holds data of cleanup operations such as reconcile and purge.  For internal use only.|
|10218|RetentionConfig|Holds retention policies for a table.|
|10219|RetentionFailureDetail|Retention failure details.|
|10220|RetentionOperation|Retention policy execution details.|
|10221|RetentionOperationDetail|Table level details of retention execution.|
|10222|Notification|Notification to be provided to a user.|
|10223|User Rating||
|10224|Mobile App|Mobile App|
|10225|Insights Store Data Source||
|10226|Insights Store Virtual Entity|Insights Store Virtual Entity|
|10227|RoleEditorLayout||
|10228|Deleted Record Reference|Deleted Record Reference|
|10229|Restore Deleted Records Configuration|Holds Restore Deleted Records configuration for entities|
|10230|App Action|Contains Modern Command Information|
|10231|App Action Migration||
|10232|App Action Rule||
|10235|Card|Card|
|10236|Card State Item||
|10239|Entity link chat configuration||
|10240|Rich Text Attachment|Image or file attached to a rich text field|
|10241|Custom Control Extended Setting||
|10242|Timeline Pin|Timeline Pin Record|
|10243|Virtual Connector Data Source||
|10244|Virtual Table Column Candidate||
|10245|PM Analysis History||
|10246|PM Business Rule Automation Config||
|10247|PM Calendar||
|10248|PM Calendar Version||
|10249|PM Inferred Task||
|10250|PM Process Extended Metadata Version||
|10251|PM Process Template||
|10252|PM Process User Settings||
|10253|PM Process Version||
|10254|PM Recording||
|10255|PM Template||
|10256|PM View||
|10257|Analysis Component||
|10258|Analysis Job||
|10259|Analysis Override||
|10260|Analysis Result||
|10261|Analysis Result Detail||
|10262|Solution Health Rule||
|10263|Solution Health Rule Argument||
|10264|Solution Health Rule Set|Represents a set that owns a number of solution health rules.|
|10265|Power BI Dataset||
|10266|powerbidatasetapdx|PowerBI Dataset appendix entity - for unmanaged technical attributes|
|10267|Power BI Mashup Parameter||
|10268|Power BI Report||
|10269|powerbireportapdx|PowerBI Report appendix entity for unmanaged technical attributes|
|10270|File Upload||
|10271|MainFewShot|This fewshot entity will only be updated during solution installation.|
|10272|MakerFewShot|This fewshot is updated by maker for testing the queries and by the NL2SQ with the results|
|10273|SearchAttributeSettings||
|10274|SearchCustomAnalyzer||
|10275|SearchRelationshipSettings||
|10276|SearchResultsCache|Cache search results internally|
|10277|Search Telemetry|Entity to log telemetry that used to improve search quality|
|10278|CopilotExampleQuestion|CopilotExampleQuestions Component|
|10279|CopilotGlossaryTerm|CopilotGlossaryTerm Component|
|10280|CopilotSynonyms|CopilotSynonyms Component|
|10281|Site Component||
|10282|Site||
|10283|Site Language||
|10284|Power Pages Site Published||
|10287|External Identity||
|10288|Invitation|Send invitations to existing contacts or email addresses and assign them to web roles upon redemption.|
|10289|Invite Redemption|Holds information about the redemption of an invite.|
|10290|Portal Comment|An activity which is used to share information between the user and the customer on the portal.|
|10291|Setting||
|10292|Multistep Form Session|Serves as a mechanism to log the occurrence of an incomplete multistep form entry for a given user so they can return and complete it later.|
|10296|Ad Placement||
|10297|Column Permission||
|10298|Column Permission Profile||
|10299|Content Snippet|Content snippets are inserted in page templates so that any label, text string or image in the template can be content-managed.|
|10300|Basic Form|Defines the form to render for a given entity type.|
|10301|Basic Form Metadata|Defines the additional behavior modification logic to augment or override the functionality of form components that is not possible with Dynamics 365 entity and form metadata.|
|10302|List||
|10303|Table Permission||
|10304|Page Template|URL of the .aspx page used to create new webpages.|
|10305|Poll Placement||
|10306|Power Pages Core Entity DS||
|10307|Publishing State||
|10308|Publishing State Transition Rule||
|10309|Redirect||
|10310|Shortcut||
|10311|Site Marker|Used by web page templates to locate a specific page of content.|
|10312|Site Setting|Site specific settings or variables refferenced by the web site code files.|
|10313|Web File|Storage of files used in the web Portals.|
|10314|Multistep Form|Defines the necessary properties and relationships to the other key entities in order to control the initialization of the form within a web portal.|
|10315|Multistep Form Metadata|Defines the additional behavior modification logic to augment or override the functionality of form fields that is not possible with Dynamics 365 entity and form metadata.|
|10316|Form Step|Defines the flow logic of the form's user experience such as steps and conditional branching.|
|10317|Web Link|A textual or imaged based link to an interal or external URL.|
|10318|Web Link Set|A grouping of web links.|
|10319|Web Page|Web Page|
|10320|Web Page Access Control Rule||
|10321|Web Role|Sets the user's role for the Portal.|
|10322|Website|Web Portal|
|10323|Website Access||
|10324|Website Language|Languages supported and publishing status for the portal|
|10325|Web Template||
|10332|Power Pages Scan Report|Power Pages Scan Report|
|10333|Power Pages Log||
|10338|Catalog Submission Files|Files associated with the package that will be used as part of the submission to the catalog system.|
|10339|Package Submission Store|Manages submissions to the Catalog and provisioning|
|18085|Event Expander Breadcrumb|Table to store breadcrumb records of Event Expander pipeline.|



### <a name="BKMK_ModifiedBy"></a> ModifiedBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who last modified the duplicate detection rule.|
|DisplayName|Modified By|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedByYomiName"></a> ModifiedByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedbyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|Date and time when the duplicate detection rule was last modified.|
|DisplayName|Modified On|
|Format|DateAndTime|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|modifiedon|
|RequiredLevel|None|
|Type|DateTime|


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

|Property|Value|
|--------|-----|
|Description|Unique identifier of the delegate user who last modified the duplicaterule.|
|DisplayName|Modified By (Delegate)|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfby|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyname|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|modifiedonbehalfbyyominame|
|MaxLength|100|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_OverwriteTime"></a> OverwriteTime

**Added by**: Basic Solution Solution

|Property|Value|
|--------|-----|
|DateTimeBehavior|UserLocal|
|Description|For internal use only.|
|DisplayName|Record Overwrite Time|
|Format|DateAndTime|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|overwritetime|
|RequiredLevel|SystemRequired|
|Type|DateTime|


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridname|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owneridyominame|
|MaxLength|100|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

|Property|Value|
|--------|-----|
|Description|Unique identifier of the business unit that owns duplicate detection rule.|
|DisplayName||
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|owningbusinessunit|
|RequiredLevel|None|
|Targets|businessunit|
|Type|Lookup|


### <a name="BKMK_OwningBusinessUnitName"></a> OwningBusinessUnitName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningbusinessunitname|
|MaxLength|160|
|RequiredLevel|None|
|Type|String|


### <a name="BKMK_OwningTeam"></a> OwningTeam

|Property|Value|
|--------|-----|
|Description|Unique identifier of the team who owns the duplicate detection rule.|
|DisplayName|Owning Team|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owningteam|
|RequiredLevel|None|
|Targets|team|
|Type|Lookup|


### <a name="BKMK_OwningUser"></a> OwningUser

|Property|Value|
|--------|-----|
|Description|Unique identifier of the user who owns the duplicate detection rule.|
|DisplayName|Owning User|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|owninguser|
|RequiredLevel|None|
|Targets|systemuser|
|Type|Lookup|


### <a name="BKMK_SolutionId"></a> SolutionId

**Added by**: Basic Solution Solution

|Property|Value|
|--------|-----|
|Description|Unique identifier of the associated solution.|
|DisplayName|Solution|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|solutionid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_StateCode"></a> StateCode

|Property|Value|
|--------|-----|
|Description|Status of the duplicate detection rule.|
|DisplayName|Status|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|statecode|
|RequiredLevel|SystemRequired|
|Type|State|

#### StateCode Choices/Options

|Value|Label|DefaultStatus|InvariantName|
|-----|-----|-------------|-------------|
|0|Inactive|0|Inactive|
|1|Active|2|Active|



### <a name="BKMK_SupportingSolutionId"></a> SupportingSolutionId

**Added by**: Basic Solution Solution

|Property|Value|
|--------|-----|
|Description|For internal use only.|
|DisplayName|Solution|
|IsValidForForm|False|
|IsValidForRead|False|
|LogicalName|supportingsolutionid|
|RequiredLevel|None|
|Type|Uniqueidentifier|

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.

- [DuplicateRule_Annotation](#BKMK_DuplicateRule_Annotation)
- [DuplicateRule_SyncErrors](#BKMK_DuplicateRule_SyncErrors)
- [DuplicateRule_DuplicateRuleConditions](#BKMK_DuplicateRule_DuplicateRuleConditions)
- [DuplicateRule_DuplicateBaseRecord](#BKMK_DuplicateRule_DuplicateBaseRecord)


### <a name="BKMK_DuplicateRule_Annotation"></a> DuplicateRule_Annotation

Same as the [DuplicateRule_Annotation](annotation.md#BKMK_DuplicateRule_Annotation) many-to-one relationship for the [annotation](annotation.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|annotation|
|ReferencingAttribute|objectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|DuplicateRule_Annotation|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: Cascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: Cascade<br />Share: Cascade<br />Unshare: Cascade|


### <a name="BKMK_DuplicateRule_SyncErrors"></a> DuplicateRule_SyncErrors

Same as the [DuplicateRule_SyncErrors](syncerror.md#BKMK_DuplicateRule_SyncErrors) many-to-one relationship for the [syncerror](syncerror.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|syncerror|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|True|
|ReferencedEntityNavigationPropertyName|DuplicateRule_SyncErrors|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: Cascade<br />Delete: Cascade<br />Merge: Cascade<br />Reparent: Cascade<br />Share: Cascade<br />Unshare: Cascade|


### <a name="BKMK_DuplicateRule_DuplicateRuleConditions"></a> DuplicateRule_DuplicateRuleConditions

Same as the [DuplicateRule_DuplicateRuleConditions](duplicaterulecondition.md#BKMK_DuplicateRule_DuplicateRuleConditions) many-to-one relationship for the [duplicaterulecondition](duplicaterulecondition.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|duplicaterulecondition|
|ReferencingAttribute|regardingobjectid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|DuplicateRule_DuplicateRuleConditions|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|


### <a name="BKMK_DuplicateRule_DuplicateBaseRecord"></a> DuplicateRule_DuplicateBaseRecord

Same as the [DuplicateRule_DuplicateBaseRecord](duplicaterecord.md#BKMK_DuplicateRule_DuplicateBaseRecord) many-to-one relationship for the [duplicaterecord](duplicaterecord.md) table/entity.

|Property|Value|
|--------|-----|
|ReferencingEntity|duplicaterecord|
|ReferencingAttribute|duplicateruleid|
|IsHierarchical|False|
|IsCustomizable|False|
|ReferencedEntityNavigationPropertyName|DuplicateRule_DuplicateBaseRecord|
|AssociatedMenuConfiguration|Behavior: DoNotDisplay<br />Group: Details<br />Label: <br />Order: |
|CascadeConfiguration|Assign: NoCascade<br />Delete: Cascade<br />Merge: NoCascade<br />Reparent: NoCascade<br />Share: NoCascade<br />Unshare: NoCascade|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related table. Listed by **SchemaName**.

- [lk_duplicaterulebase_createdby](#BKMK_lk_duplicaterulebase_createdby)
- [lk_duplicaterule_createdonbehalfby](#BKMK_lk_duplicaterule_createdonbehalfby)
- [SystemUser_DuplicateRules](#BKMK_SystemUser_DuplicateRules)
- [team_DuplicateRules](#BKMK_team_DuplicateRules)
- [lk_duplicaterule_modifiedonbehalfby](#BKMK_lk_duplicaterule_modifiedonbehalfby)
- [lk_duplicaterulebase_modifiedby](#BKMK_lk_duplicaterulebase_modifiedby)
- [BusinessUnit_DuplicateRules](#BKMK_BusinessUnit_DuplicateRules)


### <a name="BKMK_lk_duplicaterulebase_createdby"></a> lk_duplicaterulebase_createdby

See the [lk_duplicaterulebase_createdby](systemuser.md#BKMK_lk_duplicaterulebase_createdby) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_lk_duplicaterule_createdonbehalfby"></a> lk_duplicaterule_createdonbehalfby

See the [lk_duplicaterule_createdonbehalfby](systemuser.md#BKMK_lk_duplicaterule_createdonbehalfby) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_SystemUser_DuplicateRules"></a> SystemUser_DuplicateRules

See the [SystemUser_DuplicateRules](systemuser.md#BKMK_SystemUser_DuplicateRules) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_team_DuplicateRules"></a> team_DuplicateRules

See the [team_DuplicateRules](team.md#BKMK_team_DuplicateRules) one-to-many relationship for the [team](team.md) table/entity.

### <a name="BKMK_lk_duplicaterule_modifiedonbehalfby"></a> lk_duplicaterule_modifiedonbehalfby

See the [lk_duplicaterule_modifiedonbehalfby](systemuser.md#BKMK_lk_duplicaterule_modifiedonbehalfby) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_lk_duplicaterulebase_modifiedby"></a> lk_duplicaterulebase_modifiedby

See the [lk_duplicaterulebase_modifiedby](systemuser.md#BKMK_lk_duplicaterulebase_modifiedby) one-to-many relationship for the [systemuser](systemuser.md) table/entity.

### <a name="BKMK_BusinessUnit_DuplicateRules"></a> BusinessUnit_DuplicateRules

See the [BusinessUnit_DuplicateRules](businessunit.md#BKMK_BusinessUnit_DuplicateRules) one-to-many relationship for the [businessunit](businessunit.md) table/entity.

### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Web API Reference](/dynamics365/customer-engagement/web-api/about)  
<xref href="Microsoft.Dynamics.CRM.duplicaterule?text=duplicaterule EntityType" />