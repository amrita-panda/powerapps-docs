---
title: "PrincipalObjectAttributeAccess entity reference (Microsoft Dataverse)| MicrosoftDocs"
description: "Includes schema information and supported messages for the PrincipalObjectAttributeAccess table."
ms.date: 11/14/2020
ms.service: "powerapps"
ms.topic: "reference"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "KumarVivek"
ms.author: "kvivek"
search.audienceType: 
  - developer
search.app: 
  - PowerApps
  - D365CE
---
# PrincipalObjectAttributeAccess entity reference

> [!NOTE]
> Effective Nov 2020, Common Data Service has been renamed to [Microsoft Dataverse](/powerapps/maker/data-platform/data-platform-intro).

Defines CRM security principals (users and teams) access rights to secured field for an entity instance.


## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Create|POST [*org URI*]/api/data/v9.0/principalobjectattributeaccessset<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/principalobjectattributeaccessset(*principalobjectattributeaccessid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|Retrieve|GET [*org URI*]/api/data/v9.0/principalobjectattributeaccessset(*principalobjectattributeaccessid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/principalobjectattributeaccessset<br />See [Query Data](/powerapps/developer/data-platform/webapi/query-data-web-api)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|Update|PATCH [*org URI*]/api/data/v9.0/principalobjectattributeaccessset(*principalobjectattributeaccessid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Entity properties

|Property|Value|
|--------|-----|
|CollectionSchemaName|PrincipalObjectAttributeAccesses|
|DisplayCollectionName|Field Sharing|
|DisplayName|Field Sharing|
|EntitySetName|principalobjectattributeaccessset|
|IsBPFEntity|False|
|LogicalCollectionName|principalobjectattributeaccesses|
|LogicalName|principalobjectattributeaccess|
|OwnershipType|OrganizationOwned|
|PrimaryIdAttribute|principalobjectattributeaccessid|
|PrimaryNameAttribute||
|SchemaName|PrincipalObjectAttributeAccess|

<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [AttributeId](#BKMK_AttributeId)
- [ObjectId](#BKMK_ObjectId)
- [ObjectTypeCode](#BKMK_ObjectTypeCode)
- [PrincipalId](#BKMK_PrincipalId)
- [PrincipalIdType](#BKMK_PrincipalIdType)
- [PrincipalObjectAttributeAccessId](#BKMK_PrincipalObjectAttributeAccessId)
- [ReadAccess](#BKMK_ReadAccess)
- [UpdateAccess](#BKMK_UpdateAccess)


### <a name="BKMK_AttributeId"></a> AttributeId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the shared secured field|
|DisplayName|Secured field|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|attributeid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_ObjectId"></a> ObjectId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the entity instance with shared secured field|
|DisplayName|Entity instance|
|IsValidForForm|True|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|objectid|
|RequiredLevel|SystemRequired|
|Targets|account,appelement,applicationuser,appmodulecomponentedge,appmodulecomponentnode,appointment,appsetting,attributeimageconfig,bot,botcomponent,businessunit,canvasappextendedmetadata,cascadegrantrevokeaccessrecordstracker,cascadegrantrevokeaccessversiontracker,catalog,catalogassignment,channelaccessprofile,connection,connectionreference,connector,contact,conversationtranscript,customapi,customapirequestparameter,customapiresponseproperty,customeraddress,datalakefolder,datalakefolderpermission,datalakeworkspace,datalakeworkspacepermission,email,entityanalyticsconfig,entityimageconfig,environmentvariabledefinition,environmentvariablevalue,exportsolutionupload,fax,feedback,flowsession,goal,holidaywrapper,internalcatalogassignment,kbarticle,knowledgearticle,knowledgearticleviews,knowledgebaserecord,letter,mailmergetemplate,msdynce_botcontent,msdyn_aibdataset,msdyn_aibdatasetfile,msdyn_aibdatasetrecord,msdyn_aibdatasetscontainer,msdyn_aibfile,msdyn_aibfileattacheddata,msdyn_aiconfiguration,msdyn_aifptrainingdocument,msdyn_aimodel,msdyn_aiodimage,msdyn_aiodlabel,msdyn_aiodtrainingboundingbox,msdyn_aiodtrainingimage,msdyn_aitemplate,msdyn_analysiscomponent,msdyn_analysisjob,msdyn_analysisresult,msdyn_analysisresultdetail,msdyn_dataflow,msdyn_federatedarticle,msdyn_federatedarticleincident,msdyn_helppage,msdyn_kmfederatedsearchconfig,msdyn_knowledgearticleimage,msdyn_knowledgearticletemplate,msdyn_knowledgeinteractioninsight,msdyn_knowledgesearchinsight,msdyn_richtextfile,msdyn_serviceconfiguration,msdyn_slakpi,msdyn_solutionhealthrule,msdyn_solutionhealthruleargument,msdyn_solutionhealthruleset,package,pdfsetting,phonecall,position,processstageparameter,provisionlanguageforuser,queue,queueitem,recurringappointmentmaster,relationshipattribute,reportcategory,serviceplan,settingdefinition,sharepointdocumentlocation,sharepointsite,socialactivity,socialprofile,solutioncomponentattributeconfiguration,solutioncomponentconfiguration,solutioncomponentrelationshipconfiguration,stagesolutionupload,systemuser,task,team,teammobileofflineprofilemembership,territory,usermobileofflineprofilemembership,workflowbinary|
|Type|Lookup|


### <a name="BKMK_ObjectTypeCode"></a> ObjectTypeCode

|Property|Value|
|--------|-----|
|Description|Type of the record with shared secured field|
|DisplayName|Entity object type|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|objecttypecode|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_PrincipalId"></a> PrincipalId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the principal to which secured field is shared|
|DisplayName|Principal|
|IsValidForForm|True|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|principalid|
|RequiredLevel|SystemRequired|
|Targets|systemuser,team|
|Type|Lookup|


### <a name="BKMK_PrincipalIdType"></a> PrincipalIdType

|Property|Value|
|--------|-----|
|Description|Type of the principal to which secured field is shared|
|DisplayName|Principal type|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|principalidtype|
|RequiredLevel|SystemRequired|
|Type|EntityName|


### <a name="BKMK_PrincipalObjectAttributeAccessId"></a> PrincipalObjectAttributeAccessId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the shared secured field instance|
|DisplayName|Shared secured field|
|IsValidForForm|False|
|IsValidForRead|True|
|IsValidForUpdate|False|
|LogicalName|principalobjectattributeaccessid|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|


### <a name="BKMK_ReadAccess"></a> ReadAccess

|Property|Value|
|--------|-----|
|Description|Read permission for secured field instance|
|DisplayName|Read permission|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|readaccess|
|RequiredLevel|SystemRequired|
|Type|Boolean|

#### ReadAccess Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False



### <a name="BKMK_UpdateAccess"></a> UpdateAccess

|Property|Value|
|--------|-----|
|Description|Update permission for secured field instance|
|DisplayName|Update permission|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|updateaccess|
|RequiredLevel|SystemRequired|
|Type|Boolean|

#### UpdateAccess Options

|Value|Label|
|-----|-----|
|1|Yes|
|0|No|

**DefaultValue**: False


<a name="read-only-attributes"></a>

## Read-only attributes

These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [OrganizationId](#BKMK_OrganizationId)
- [OrganizationIdName](#BKMK_OrganizationIdName)
- [PrincipalIdName](#BKMK_PrincipalIdName)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_OrganizationId"></a> OrganizationId

|Property|Value|
|--------|-----|
|Description|Unique identifier of the associated organization.|
|DisplayName|Organization|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|organizationid|
|RequiredLevel|SystemRequired|
|Targets|organization|
|Type|Lookup|


### <a name="BKMK_OrganizationIdName"></a> OrganizationIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|organizationidname|
|MaxLength|160|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_PrincipalIdName"></a> PrincipalIdName

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|FormatName|Text|
|IsLocalizable|False|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|principalidname|
|MaxLength|160|
|RequiredLevel|SystemRequired|
|Type|String|


### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|--------|-----|
|Description||
|DisplayName||
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|versionnumber|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|
|RequiredLevel|None|
|Type|BigInt|

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [account_principalobjectattributeaccess](#BKMK_account_principalobjectattributeaccess)
- [contact_principalobjectattributeaccess](#BKMK_contact_principalobjectattributeaccess)
- [lk_principalobjectattributeaccess_organizationid](#BKMK_lk_principalobjectattributeaccess_organizationid)
- [team_principalobjectattributeaccess_principalid](#BKMK_team_principalobjectattributeaccess_principalid)
- [systemuser_principalobjectattributeaccess_principalid](#BKMK_systemuser_principalobjectattributeaccess_principalid)
- [knowledgearticle_PrincipalObjectAttributeAccess](#BKMK_knowledgearticle_PrincipalObjectAttributeAccess)
- [KnowledgeBaseRecord_PrincipalObjectAttributeAccess](#BKMK_KnowledgeBaseRecord_PrincipalObjectAttributeAccess)
- [team_principalobjectattributeaccess](#BKMK_team_principalobjectattributeaccess)
- [reportcategory_principalobjectattributeaccess](#BKMK_reportcategory_principalobjectattributeaccess)
- [mailmergetemplate_principalobjectattributeaccess](#BKMK_mailmergetemplate_principalobjectattributeaccess)
- [fax_principalobjectattributeaccess](#BKMK_fax_principalobjectattributeaccess)
- [socialactivity_principalobjectattributeaccess](#BKMK_socialactivity_principalobjectattributeaccess)
- [kbarticle_principalobjectattributeaccess](#BKMK_kbarticle_principalobjectattributeaccess)
- [phonecall_principalobjectattributeaccess](#BKMK_phonecall_principalobjectattributeaccess)
- [position_principalobjectattributeaccess](#BKMK_position_principalobjectattributeaccess)
- [customeraddress_principalobjectattributeaccess](#BKMK_customeraddress_principalobjectattributeaccess)
- [sharepointsite_principalobjectattributeaccess](#BKMK_sharepointsite_principalobjectattributeaccess)
- [systemuser_principalobjectattributeaccess](#BKMK_systemuser_principalobjectattributeaccess)
- [connection_principalobjectattributeaccess](#BKMK_connection_principalobjectattributeaccess)
- [appointment_principalobjectattributeaccess](#BKMK_appointment_principalobjectattributeaccess)
- [goal_principalobjectattributeaccess](#BKMK_goal_principalobjectattributeaccess)
- [email_principalobjectattributeaccess](#BKMK_email_principalobjectattributeaccess)
- [knowledgearticleview_principalobjectattributeaccess](#BKMK_knowledgearticleview_principalobjectattributeaccess)
- [feedback_principalobjectattributeaccess](#BKMK_feedback_principalobjectattributeaccess)
- [businessunit_principalobjectattributeaccess](#BKMK_businessunit_principalobjectattributeaccess)
- [sharepointdocumentlocation_principalobjectattributeaccess](#BKMK_sharepointdocumentlocation_principalobjectattributeaccess)
- [queueitem_principalobjectattributeaccess](#BKMK_queueitem_principalobjectattributeaccess)
- [queue_principalobjectattributeaccess](#BKMK_queue_principalobjectattributeaccess)
- [recurringappointmentmaster_principalobjectattributeaccess](#BKMK_recurringappointmentmaster_principalobjectattributeaccess)
- [task_principalobjectattributeaccess](#BKMK_task_principalobjectattributeaccess)
- [letter_principalobjectattributeaccess](#BKMK_letter_principalobjectattributeaccess)
- [socialprofile_principalobjectattributeaccess](#BKMK_socialprofile_principalobjectattributeaccess)
- [solutioncomponentattributeconfiguration_PrincipalObjectAttributeAccesses](#BKMK_solutioncomponentattributeconfiguration_PrincipalObjectAttributeAccesses)
- [solutioncomponentconfiguration_PrincipalObjectAttributeAccesses](#BKMK_solutioncomponentconfiguration_PrincipalObjectAttributeAccesses)
- [solutioncomponentrelationshipconfiguration_PrincipalObjectAttributeAccesses](#BKMK_solutioncomponentrelationshipconfiguration_PrincipalObjectAttributeAccesses)
- [package_PrincipalObjectAttributeAccesses](#BKMK_package_PrincipalObjectAttributeAccesses)
- [stagesolutionupload_PrincipalObjectAttributeAccesses](#BKMK_stagesolutionupload_PrincipalObjectAttributeAccesses)
- [exportsolutionupload_PrincipalObjectAttributeAccesses](#BKMK_exportsolutionupload_PrincipalObjectAttributeAccesses)
- [attributeimageconfig_PrincipalObjectAttributeAccesses](#BKMK_attributeimageconfig_PrincipalObjectAttributeAccesses)
- [entityimageconfig_PrincipalObjectAttributeAccesses](#BKMK_entityimageconfig_PrincipalObjectAttributeAccesses)
- [provisionlanguageforuser_PrincipalObjectAttributeAccesses](#BKMK_provisionlanguageforuser_PrincipalObjectAttributeAccesses)
- [serviceplan_PrincipalObjectAttributeAccesses](#BKMK_serviceplan_PrincipalObjectAttributeAccesses)
- [applicationuser_PrincipalObjectAttributeAccesses](#BKMK_applicationuser_PrincipalObjectAttributeAccesses)
- [connector_PrincipalObjectAttributeAccesses](#BKMK_connector_PrincipalObjectAttributeAccesses)
- [environmentvariabledefinition_PrincipalObjectAttributeAccesses](#BKMK_environmentvariabledefinition_PrincipalObjectAttributeAccesses)
- [environmentvariablevalue_PrincipalObjectAttributeAccesses](#BKMK_environmentvariablevalue_PrincipalObjectAttributeAccesses)
- [processstageparameter_PrincipalObjectAttributeAccesses](#BKMK_processstageparameter_PrincipalObjectAttributeAccesses)
- [flowsession_PrincipalObjectAttributeAccesses](#BKMK_flowsession_PrincipalObjectAttributeAccesses)
- [workflowbinary_PrincipalObjectAttributeAccesses](#BKMK_workflowbinary_PrincipalObjectAttributeAccesses)
- [connectionreference_PrincipalObjectAttributeAccesses](#BKMK_connectionreference_PrincipalObjectAttributeAccesses)
- [msdyn_helppage_PrincipalObjectAttributeAccesses](#BKMK_msdyn_helppage_PrincipalObjectAttributeAccesses)
- [msdynce_botcontent_PrincipalObjectAttributeAccesses](#BKMK_msdynce_botcontent_PrincipalObjectAttributeAccesses)
- [conversationtranscript_PrincipalObjectAttributeAccesses](#BKMK_conversationtranscript_PrincipalObjectAttributeAccesses)
- [bot_PrincipalObjectAttributeAccesses](#BKMK_bot_PrincipalObjectAttributeAccesses)
- [botcomponent_PrincipalObjectAttributeAccesses](#BKMK_botcomponent_PrincipalObjectAttributeAccesses)
- [territory_principalobjectattributeaccess](#BKMK_territory_principalobjectattributeaccess)
- [msdyn_serviceconfiguration_PrincipalObjectAttributeAccesses](#BKMK_msdyn_serviceconfiguration_PrincipalObjectAttributeAccesses)
- [msdyn_slakpi_PrincipalObjectAttributeAccesses](#BKMK_msdyn_slakpi_PrincipalObjectAttributeAccesses)
- [msdyn_federatedarticle_PrincipalObjectAttributeAccesses](#BKMK_msdyn_federatedarticle_PrincipalObjectAttributeAccesses)
- [msdyn_federatedarticleincident_PrincipalObjectAttributeAccesses](#BKMK_msdyn_federatedarticleincident_PrincipalObjectAttributeAccesses)
- [msdyn_kmfederatedsearchconfig_PrincipalObjectAttributeAccesses](#BKMK_msdyn_kmfederatedsearchconfig_PrincipalObjectAttributeAccesses)
- [msdyn_knowledgearticleimage_PrincipalObjectAttributeAccesses](#BKMK_msdyn_knowledgearticleimage_PrincipalObjectAttributeAccesses)
- [msdyn_knowledgeinteractioninsight_PrincipalObjectAttributeAccesses](#BKMK_msdyn_knowledgeinteractioninsight_PrincipalObjectAttributeAccesses)
- [msdyn_knowledgesearchinsight_PrincipalObjectAttributeAccesses](#BKMK_msdyn_knowledgesearchinsight_PrincipalObjectAttributeAccesses)
- [msdyn_knowledgearticletemplate_PrincipalObjectAttributeAccesses](#BKMK_msdyn_knowledgearticletemplate_PrincipalObjectAttributeAccesses)
- [catalog_PrincipalObjectAttributeAccesses](#BKMK_catalog_PrincipalObjectAttributeAccesses)
- [catalogassignment_PrincipalObjectAttributeAccesses](#BKMK_catalogassignment_PrincipalObjectAttributeAccesses)
- [customapi_PrincipalObjectAttributeAccesses](#BKMK_customapi_PrincipalObjectAttributeAccesses)
- [customapirequestparameter_PrincipalObjectAttributeAccesses](#BKMK_customapirequestparameter_PrincipalObjectAttributeAccesses)
- [customapiresponseproperty_PrincipalObjectAttributeAccesses](#BKMK_customapiresponseproperty_PrincipalObjectAttributeAccesses)
- [entityanalyticsconfig_PrincipalObjectAttributeAccesses](#BKMK_entityanalyticsconfig_PrincipalObjectAttributeAccesses)
- [datalakefolder_PrincipalObjectAttributeAccesses](#BKMK_datalakefolder_PrincipalObjectAttributeAccesses)
- [datalakefolderpermission_PrincipalObjectAttributeAccesses](#BKMK_datalakefolderpermission_PrincipalObjectAttributeAccesses)
- [datalakeworkspace_PrincipalObjectAttributeAccesses](#BKMK_datalakeworkspace_PrincipalObjectAttributeAccesses)
- [datalakeworkspacepermission_PrincipalObjectAttributeAccesses](#BKMK_datalakeworkspacepermission_PrincipalObjectAttributeAccesses)
- [msdyn_dataflow_PrincipalObjectAttributeAccesses](#BKMK_msdyn_dataflow_PrincipalObjectAttributeAccesses)
- [msdyn_richtextfile_PrincipalObjectAttributeAccesses](#BKMK_msdyn_richtextfile_PrincipalObjectAttributeAccesses)
- [msdyn_aiconfiguration_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aiconfiguration_PrincipalObjectAttributeAccesses)
- [msdyn_aimodel_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aimodel_PrincipalObjectAttributeAccesses)
- [msdyn_aitemplate_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aitemplate_PrincipalObjectAttributeAccesses)
- [msdyn_aibdataset_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aibdataset_PrincipalObjectAttributeAccesses)
- [msdyn_aibdatasetfile_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aibdatasetfile_PrincipalObjectAttributeAccesses)
- [msdyn_aibdatasetrecord_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aibdatasetrecord_PrincipalObjectAttributeAccesses)
- [msdyn_aibdatasetscontainer_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aibdatasetscontainer_PrincipalObjectAttributeAccesses)
- [msdyn_aibfile_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aibfile_PrincipalObjectAttributeAccesses)
- [msdyn_aibfileattacheddata_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aibfileattacheddata_PrincipalObjectAttributeAccesses)
- [msdyn_aifptrainingdocument_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aifptrainingdocument_PrincipalObjectAttributeAccesses)
- [msdyn_aiodimage_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aiodimage_PrincipalObjectAttributeAccesses)
- [msdyn_aiodlabel_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aiodlabel_PrincipalObjectAttributeAccesses)
- [msdyn_aiodtrainingboundingbox_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aiodtrainingboundingbox_PrincipalObjectAttributeAccesses)
- [msdyn_aiodtrainingimage_PrincipalObjectAttributeAccesses](#BKMK_msdyn_aiodtrainingimage_PrincipalObjectAttributeAccesses)
- [msdyn_analysiscomponent_PrincipalObjectAttributeAccesses](#BKMK_msdyn_analysiscomponent_PrincipalObjectAttributeAccesses)
- [msdyn_analysisjob_PrincipalObjectAttributeAccesses](#BKMK_msdyn_analysisjob_PrincipalObjectAttributeAccesses)
- [msdyn_analysisresult_PrincipalObjectAttributeAccesses](#BKMK_msdyn_analysisresult_PrincipalObjectAttributeAccesses)
- [msdyn_analysisresultdetail_PrincipalObjectAttributeAccesses](#BKMK_msdyn_analysisresultdetail_PrincipalObjectAttributeAccesses)
- [msdyn_solutionhealthrule_PrincipalObjectAttributeAccesses](#BKMK_msdyn_solutionhealthrule_PrincipalObjectAttributeAccesses)
- [msdyn_solutionhealthruleargument_PrincipalObjectAttributeAccesses](#BKMK_msdyn_solutionhealthruleargument_PrincipalObjectAttributeAccesses)
- [msdyn_solutionhealthruleset_PrincipalObjectAttributeAccesses](#BKMK_msdyn_solutionhealthruleset_PrincipalObjectAttributeAccesses)


### <a name="BKMK_account_principalobjectattributeaccess"></a> account_principalobjectattributeaccess

See account Entity [account_principalobjectattributeaccess](account.md#BKMK_account_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_contact_principalobjectattributeaccess"></a> contact_principalobjectattributeaccess

See contact Entity [contact_principalobjectattributeaccess](contact.md#BKMK_contact_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_lk_principalobjectattributeaccess_organizationid"></a> lk_principalobjectattributeaccess_organizationid

See organization Entity [lk_principalobjectattributeaccess_organizationid](organization.md#BKMK_lk_principalobjectattributeaccess_organizationid) One-To-Many relationship.

### <a name="BKMK_team_principalobjectattributeaccess_principalid"></a> team_principalobjectattributeaccess_principalid

See team Entity [team_principalobjectattributeaccess_principalid](team.md#BKMK_team_principalobjectattributeaccess_principalid) One-To-Many relationship.

### <a name="BKMK_systemuser_principalobjectattributeaccess_principalid"></a> systemuser_principalobjectattributeaccess_principalid

See systemuser Entity [systemuser_principalobjectattributeaccess_principalid](systemuser.md#BKMK_systemuser_principalobjectattributeaccess_principalid) One-To-Many relationship.

### <a name="BKMK_knowledgearticle_PrincipalObjectAttributeAccess"></a> knowledgearticle_PrincipalObjectAttributeAccess

See knowledgearticle Entity [knowledgearticle_PrincipalObjectAttributeAccess](knowledgearticle.md#BKMK_knowledgearticle_PrincipalObjectAttributeAccess) One-To-Many relationship.

### <a name="BKMK_KnowledgeBaseRecord_PrincipalObjectAttributeAccess"></a> KnowledgeBaseRecord_PrincipalObjectAttributeAccess

See knowledgebaserecord Entity [KnowledgeBaseRecord_PrincipalObjectAttributeAccess](knowledgebaserecord.md#BKMK_KnowledgeBaseRecord_PrincipalObjectAttributeAccess) One-To-Many relationship.

### <a name="BKMK_team_principalobjectattributeaccess"></a> team_principalobjectattributeaccess

See team Entity [team_principalobjectattributeaccess](team.md#BKMK_team_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_reportcategory_principalobjectattributeaccess"></a> reportcategory_principalobjectattributeaccess

See reportcategory Entity [reportcategory_principalobjectattributeaccess](reportcategory.md#BKMK_reportcategory_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_mailmergetemplate_principalobjectattributeaccess"></a> mailmergetemplate_principalobjectattributeaccess

See mailmergetemplate Entity [mailmergetemplate_principalobjectattributeaccess](mailmergetemplate.md#BKMK_mailmergetemplate_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_fax_principalobjectattributeaccess"></a> fax_principalobjectattributeaccess

See fax Entity [fax_principalobjectattributeaccess](fax.md#BKMK_fax_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_socialactivity_principalobjectattributeaccess"></a> socialactivity_principalobjectattributeaccess

See socialactivity Entity [socialactivity_principalobjectattributeaccess](socialactivity.md#BKMK_socialactivity_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_kbarticle_principalobjectattributeaccess"></a> kbarticle_principalobjectattributeaccess

See kbarticle Entity [kbarticle_principalobjectattributeaccess](kbarticle.md#BKMK_kbarticle_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_phonecall_principalobjectattributeaccess"></a> phonecall_principalobjectattributeaccess

See phonecall Entity [phonecall_principalobjectattributeaccess](phonecall.md#BKMK_phonecall_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_position_principalobjectattributeaccess"></a> position_principalobjectattributeaccess

See position Entity [position_principalobjectattributeaccess](position.md#BKMK_position_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_customeraddress_principalobjectattributeaccess"></a> customeraddress_principalobjectattributeaccess

See customeraddress Entity [customeraddress_principalobjectattributeaccess](customeraddress.md#BKMK_customeraddress_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_sharepointsite_principalobjectattributeaccess"></a> sharepointsite_principalobjectattributeaccess

See sharepointsite Entity [sharepointsite_principalobjectattributeaccess](sharepointsite.md#BKMK_sharepointsite_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_systemuser_principalobjectattributeaccess"></a> systemuser_principalobjectattributeaccess

See systemuser Entity [systemuser_principalobjectattributeaccess](systemuser.md#BKMK_systemuser_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_connection_principalobjectattributeaccess"></a> connection_principalobjectattributeaccess

See connection Entity [connection_principalobjectattributeaccess](connection.md#BKMK_connection_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_appointment_principalobjectattributeaccess"></a> appointment_principalobjectattributeaccess

See appointment Entity [appointment_principalobjectattributeaccess](appointment.md#BKMK_appointment_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_goal_principalobjectattributeaccess"></a> goal_principalobjectattributeaccess

See goal Entity [goal_principalobjectattributeaccess](goal.md#BKMK_goal_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_email_principalobjectattributeaccess"></a> email_principalobjectattributeaccess

See email Entity [email_principalobjectattributeaccess](email.md#BKMK_email_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_knowledgearticleview_principalobjectattributeaccess"></a> knowledgearticleview_principalobjectattributeaccess

See knowledgearticleviews Entity [knowledgearticleview_principalobjectattributeaccess](knowledgearticleviews.md#BKMK_knowledgearticleview_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_feedback_principalobjectattributeaccess"></a> feedback_principalobjectattributeaccess

See feedback Entity [feedback_principalobjectattributeaccess](feedback.md#BKMK_feedback_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_businessunit_principalobjectattributeaccess"></a> businessunit_principalobjectattributeaccess

See businessunit Entity [businessunit_principalobjectattributeaccess](businessunit.md#BKMK_businessunit_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_sharepointdocumentlocation_principalobjectattributeaccess"></a> sharepointdocumentlocation_principalobjectattributeaccess

See sharepointdocumentlocation Entity [sharepointdocumentlocation_principalobjectattributeaccess](sharepointdocumentlocation.md#BKMK_sharepointdocumentlocation_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_queueitem_principalobjectattributeaccess"></a> queueitem_principalobjectattributeaccess

See queueitem Entity [queueitem_principalobjectattributeaccess](queueitem.md#BKMK_queueitem_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_queue_principalobjectattributeaccess"></a> queue_principalobjectattributeaccess

See queue Entity [queue_principalobjectattributeaccess](queue.md#BKMK_queue_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_recurringappointmentmaster_principalobjectattributeaccess"></a> recurringappointmentmaster_principalobjectattributeaccess

See recurringappointmentmaster Entity [recurringappointmentmaster_principalobjectattributeaccess](recurringappointmentmaster.md#BKMK_recurringappointmentmaster_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_task_principalobjectattributeaccess"></a> task_principalobjectattributeaccess

See task Entity [task_principalobjectattributeaccess](task.md#BKMK_task_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_letter_principalobjectattributeaccess"></a> letter_principalobjectattributeaccess

See letter Entity [letter_principalobjectattributeaccess](letter.md#BKMK_letter_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_socialprofile_principalobjectattributeaccess"></a> socialprofile_principalobjectattributeaccess

See socialprofile Entity [socialprofile_principalobjectattributeaccess](socialprofile.md#BKMK_socialprofile_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_solutioncomponentattributeconfiguration_PrincipalObjectAttributeAccesses"></a> solutioncomponentattributeconfiguration_PrincipalObjectAttributeAccesses

**Added by**: Solution Component Configuration Solution

See solutioncomponentattributeconfiguration Entity [solutioncomponentattributeconfiguration_PrincipalObjectAttributeAccesses](solutioncomponentattributeconfiguration.md#BKMK_solutioncomponentattributeconfiguration_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_solutioncomponentconfiguration_PrincipalObjectAttributeAccesses"></a> solutioncomponentconfiguration_PrincipalObjectAttributeAccesses

**Added by**: Solution Component Configuration Solution

See solutioncomponentconfiguration Entity [solutioncomponentconfiguration_PrincipalObjectAttributeAccesses](solutioncomponentconfiguration.md#BKMK_solutioncomponentconfiguration_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_solutioncomponentrelationshipconfiguration_PrincipalObjectAttributeAccesses"></a> solutioncomponentrelationshipconfiguration_PrincipalObjectAttributeAccesses

**Added by**: Solution Component Configuration Solution

See solutioncomponentrelationshipconfiguration Entity [solutioncomponentrelationshipconfiguration_PrincipalObjectAttributeAccesses](solutioncomponentrelationshipconfiguration.md#BKMK_solutioncomponentrelationshipconfiguration_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_package_PrincipalObjectAttributeAccesses"></a> package_PrincipalObjectAttributeAccesses

**Added by**: msdyn_SolutionPackageMapping Solution

See package Entity [package_PrincipalObjectAttributeAccesses](package.md#BKMK_package_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_stagesolutionupload_PrincipalObjectAttributeAccesses"></a> stagesolutionupload_PrincipalObjectAttributeAccesses

**Added by**: StageSolutionUpload Solution

See stagesolutionupload Entity [stagesolutionupload_PrincipalObjectAttributeAccesses](stagesolutionupload.md#BKMK_stagesolutionupload_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_exportsolutionupload_PrincipalObjectAttributeAccesses"></a> exportsolutionupload_PrincipalObjectAttributeAccesses

**Added by**: ExportSolutionUpload Solution

See exportsolutionupload Entity [exportsolutionupload_PrincipalObjectAttributeAccesses](exportsolutionupload.md#BKMK_exportsolutionupload_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_attributeimageconfig_PrincipalObjectAttributeAccesses"></a> attributeimageconfig_PrincipalObjectAttributeAccesses

**Added by**: Image Configuration Solution

See attributeimageconfig Entity [attributeimageconfig_PrincipalObjectAttributeAccesses](attributeimageconfig.md#BKMK_attributeimageconfig_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_entityimageconfig_PrincipalObjectAttributeAccesses"></a> entityimageconfig_PrincipalObjectAttributeAccesses

**Added by**: Image Configuration Solution

See entityimageconfig Entity [entityimageconfig_PrincipalObjectAttributeAccesses](entityimageconfig.md#BKMK_entityimageconfig_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_provisionlanguageforuser_PrincipalObjectAttributeAccesses"></a> provisionlanguageforuser_PrincipalObjectAttributeAccesses

**Added by**: msft_LocalizationExtension Solution

See provisionlanguageforuser Entity [provisionlanguageforuser_PrincipalObjectAttributeAccesses](provisionlanguageforuser.md#BKMK_provisionlanguageforuser_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_serviceplan_PrincipalObjectAttributeAccesses"></a> serviceplan_PrincipalObjectAttributeAccesses

**Added by**: License Enforcement Solution

See serviceplan Entity [serviceplan_PrincipalObjectAttributeAccesses](serviceplan.md#BKMK_serviceplan_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_applicationuser_PrincipalObjectAttributeAccesses"></a> applicationuser_PrincipalObjectAttributeAccesses

**Added by**: ApplicationUserSolution Solution

See applicationuser Entity [applicationuser_PrincipalObjectAttributeAccesses](applicationuser.md#BKMK_applicationuser_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_connector_PrincipalObjectAttributeAccesses"></a> connector_PrincipalObjectAttributeAccesses

**Added by**: Power Connector Solution Solution

See connector Entity [connector_PrincipalObjectAttributeAccesses](connector.md#BKMK_connector_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_environmentvariabledefinition_PrincipalObjectAttributeAccesses"></a> environmentvariabledefinition_PrincipalObjectAttributeAccesses

**Added by**: Environment Variables Solution

See environmentvariabledefinition Entity [environmentvariabledefinition_PrincipalObjectAttributeAccesses](environmentvariabledefinition.md#BKMK_environmentvariabledefinition_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_environmentvariablevalue_PrincipalObjectAttributeAccesses"></a> environmentvariablevalue_PrincipalObjectAttributeAccesses

**Added by**: Environment Variables Solution

See environmentvariablevalue Entity [environmentvariablevalue_PrincipalObjectAttributeAccesses](environmentvariablevalue.md#BKMK_environmentvariablevalue_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_processstageparameter_PrincipalObjectAttributeAccesses"></a> processstageparameter_PrincipalObjectAttributeAccesses

**Added by**: Microsoft Flow Extensions core package Solution

See processstageparameter Entity [processstageparameter_PrincipalObjectAttributeAccesses](processstageparameter.md#BKMK_processstageparameter_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_flowsession_PrincipalObjectAttributeAccesses"></a> flowsession_PrincipalObjectAttributeAccesses

**Added by**: Microsoft Flow Extensions core package Solution

See flowsession Entity [flowsession_PrincipalObjectAttributeAccesses](flowsession.md#BKMK_flowsession_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_workflowbinary_PrincipalObjectAttributeAccesses"></a> workflowbinary_PrincipalObjectAttributeAccesses

**Added by**: Microsoft Flow Extensions core package Solution

See workflowbinary Entity [workflowbinary_PrincipalObjectAttributeAccesses](workflowbinary.md#BKMK_workflowbinary_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_connectionreference_PrincipalObjectAttributeAccesses"></a> connectionreference_PrincipalObjectAttributeAccesses

**Added by**: Power Platform Connection References Solution

See connectionreference Entity [connectionreference_PrincipalObjectAttributeAccesses](connectionreference.md#BKMK_connectionreference_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_helppage_PrincipalObjectAttributeAccesses"></a> msdyn_helppage_PrincipalObjectAttributeAccesses

**Added by**: Contextual Help Solution

See msdyn_helppage Entity [msdyn_helppage_PrincipalObjectAttributeAccesses](msdyn_helppage.md#BKMK_msdyn_helppage_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdynce_botcontent_PrincipalObjectAttributeAccesses"></a> msdynce_botcontent_PrincipalObjectAttributeAccesses

**Added by**: Customer Care Intelligence Bots Solution

See msdynce_botcontent Entity [msdynce_botcontent_PrincipalObjectAttributeAccesses](msdynce_botcontent.md#BKMK_msdynce_botcontent_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_conversationtranscript_PrincipalObjectAttributeAccesses"></a> conversationtranscript_PrincipalObjectAttributeAccesses

**Added by**: Power Virtual Agents Common Solution

See conversationtranscript Entity [conversationtranscript_PrincipalObjectAttributeAccesses](conversationtranscript.md#BKMK_conversationtranscript_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_bot_PrincipalObjectAttributeAccesses"></a> bot_PrincipalObjectAttributeAccesses

**Added by**: Power Virtual Agents Solution

See bot Entity [bot_PrincipalObjectAttributeAccesses](bot.md#BKMK_bot_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_botcomponent_PrincipalObjectAttributeAccesses"></a> botcomponent_PrincipalObjectAttributeAccesses

**Added by**: Power Virtual Agents Solution

See botcomponent Entity [botcomponent_PrincipalObjectAttributeAccesses](botcomponent.md#BKMK_botcomponent_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_territory_principalobjectattributeaccess"></a> territory_principalobjectattributeaccess

**Added by**: Application Common Solution

See territory Entity [territory_principalobjectattributeaccess](territory.md#BKMK_territory_principalobjectattributeaccess) One-To-Many relationship.

### <a name="BKMK_msdyn_serviceconfiguration_PrincipalObjectAttributeAccesses"></a> msdyn_serviceconfiguration_PrincipalObjectAttributeAccesses

**Added by**: Service Level Agreement (SLA) Extension Solution

See msdyn_serviceconfiguration Entity [msdyn_serviceconfiguration_PrincipalObjectAttributeAccesses](msdyn_serviceconfiguration.md#BKMK_msdyn_serviceconfiguration_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_slakpi_PrincipalObjectAttributeAccesses"></a> msdyn_slakpi_PrincipalObjectAttributeAccesses

**Added by**: Service Level Agreement (SLA) Extension Solution

See msdyn_slakpi Entity [msdyn_slakpi_PrincipalObjectAttributeAccesses](msdyn_slakpi.md#BKMK_msdyn_slakpi_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_federatedarticle_PrincipalObjectAttributeAccesses"></a> msdyn_federatedarticle_PrincipalObjectAttributeAccesses

**Added by**: Knowledge Management Online Features Solution

See msdyn_federatedarticle Entity [msdyn_federatedarticle_PrincipalObjectAttributeAccesses](msdyn_federatedarticle.md#BKMK_msdyn_federatedarticle_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_federatedarticleincident_PrincipalObjectAttributeAccesses"></a> msdyn_federatedarticleincident_PrincipalObjectAttributeAccesses

**Added by**: Knowledge Management Online Features Solution

See msdyn_federatedarticleincident Entity [msdyn_federatedarticleincident_PrincipalObjectAttributeAccesses](msdyn_federatedarticleincident.md#BKMK_msdyn_federatedarticleincident_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_kmfederatedsearchconfig_PrincipalObjectAttributeAccesses"></a> msdyn_kmfederatedsearchconfig_PrincipalObjectAttributeAccesses

**Added by**: Knowledge Management Online Features Solution

See msdyn_kmfederatedsearchconfig Entity [msdyn_kmfederatedsearchconfig_PrincipalObjectAttributeAccesses](msdyn_kmfederatedsearchconfig.md#BKMK_msdyn_kmfederatedsearchconfig_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_knowledgearticleimage_PrincipalObjectAttributeAccesses"></a> msdyn_knowledgearticleimage_PrincipalObjectAttributeAccesses

**Added by**: Knowledge Management Online Features Solution

See msdyn_knowledgearticleimage Entity [msdyn_knowledgearticleimage_PrincipalObjectAttributeAccesses](msdyn_knowledgearticleimage.md#BKMK_msdyn_knowledgearticleimage_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_knowledgeinteractioninsight_PrincipalObjectAttributeAccesses"></a> msdyn_knowledgeinteractioninsight_PrincipalObjectAttributeAccesses

**Added by**: Knowledge Management Online Features Solution

See msdyn_knowledgeinteractioninsight Entity [msdyn_knowledgeinteractioninsight_PrincipalObjectAttributeAccesses](msdyn_knowledgeinteractioninsight.md#BKMK_msdyn_knowledgeinteractioninsight_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_knowledgesearchinsight_PrincipalObjectAttributeAccesses"></a> msdyn_knowledgesearchinsight_PrincipalObjectAttributeAccesses

**Added by**: Knowledge Management Online Features Solution

See msdyn_knowledgesearchinsight Entity [msdyn_knowledgesearchinsight_PrincipalObjectAttributeAccesses](msdyn_knowledgesearchinsight.md#BKMK_msdyn_knowledgesearchinsight_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_knowledgearticletemplate_PrincipalObjectAttributeAccesses"></a> msdyn_knowledgearticletemplate_PrincipalObjectAttributeAccesses

**Added by**: Knowledge Management Features Solution

See msdyn_knowledgearticletemplate Entity [msdyn_knowledgearticletemplate_PrincipalObjectAttributeAccesses](msdyn_knowledgearticletemplate.md#BKMK_msdyn_knowledgearticletemplate_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_catalog_PrincipalObjectAttributeAccesses"></a> catalog_PrincipalObjectAttributeAccesses

**Added by**: CatalogFramework Solution

See catalog Entity [catalog_PrincipalObjectAttributeAccesses](catalog.md#BKMK_catalog_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_catalogassignment_PrincipalObjectAttributeAccesses"></a> catalogassignment_PrincipalObjectAttributeAccesses

**Added by**: CatalogFramework Solution

See catalogassignment Entity [catalogassignment_PrincipalObjectAttributeAccesses](catalogassignment.md#BKMK_catalogassignment_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_customapi_PrincipalObjectAttributeAccesses"></a> customapi_PrincipalObjectAttributeAccesses

**Added by**: Custom API Framework Solution

See customapi Entity [customapi_PrincipalObjectAttributeAccesses](customapi.md#BKMK_customapi_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_customapirequestparameter_PrincipalObjectAttributeAccesses"></a> customapirequestparameter_PrincipalObjectAttributeAccesses

**Added by**: Custom API Framework Solution

See customapirequestparameter Entity [customapirequestparameter_PrincipalObjectAttributeAccesses](customapirequestparameter.md#BKMK_customapirequestparameter_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_customapiresponseproperty_PrincipalObjectAttributeAccesses"></a> customapiresponseproperty_PrincipalObjectAttributeAccesses

**Added by**: Custom API Framework Solution

See customapiresponseproperty Entity [customapiresponseproperty_PrincipalObjectAttributeAccesses](customapiresponseproperty.md#BKMK_customapiresponseproperty_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_entityanalyticsconfig_PrincipalObjectAttributeAccesses"></a> entityanalyticsconfig_PrincipalObjectAttributeAccesses

**Added by**: Advanced Analytics Infrastructure Solution

See entityanalyticsconfig Entity [entityanalyticsconfig_PrincipalObjectAttributeAccesses](entityanalyticsconfig.md#BKMK_entityanalyticsconfig_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_datalakefolder_PrincipalObjectAttributeAccesses"></a> datalakefolder_PrincipalObjectAttributeAccesses

**Added by**: Data lake workspaces Solution

See datalakefolder Entity [datalakefolder_PrincipalObjectAttributeAccesses](datalakefolder.md#BKMK_datalakefolder_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_datalakefolderpermission_PrincipalObjectAttributeAccesses"></a> datalakefolderpermission_PrincipalObjectAttributeAccesses

**Added by**: Data lake workspaces Solution

See datalakefolderpermission Entity [datalakefolderpermission_PrincipalObjectAttributeAccesses](datalakefolderpermission.md#BKMK_datalakefolderpermission_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_datalakeworkspace_PrincipalObjectAttributeAccesses"></a> datalakeworkspace_PrincipalObjectAttributeAccesses

**Added by**: Data lake workspaces Solution

See datalakeworkspace Entity [datalakeworkspace_PrincipalObjectAttributeAccesses](datalakeworkspace.md#BKMK_datalakeworkspace_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_datalakeworkspacepermission_PrincipalObjectAttributeAccesses"></a> datalakeworkspacepermission_PrincipalObjectAttributeAccesses

**Added by**: Data lake workspaces Solution

See datalakeworkspacepermission Entity [datalakeworkspacepermission_PrincipalObjectAttributeAccesses](datalakeworkspacepermission.md#BKMK_datalakeworkspacepermission_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_dataflow_PrincipalObjectAttributeAccesses"></a> msdyn_dataflow_PrincipalObjectAttributeAccesses

**Added by**: Dataflow Solution Solution

See msdyn_dataflow Entity [msdyn_dataflow_PrincipalObjectAttributeAccesses](msdyn_dataflow.md#BKMK_msdyn_dataflow_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_richtextfile_PrincipalObjectAttributeAccesses"></a> msdyn_richtextfile_PrincipalObjectAttributeAccesses

**Added by**: Rich Text Editor Solution

See msdyn_richtextfile Entity [msdyn_richtextfile_PrincipalObjectAttributeAccesses](msdyn_richtextfile.md#BKMK_msdyn_richtextfile_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aiconfiguration_PrincipalObjectAttributeAccesses"></a> msdyn_aiconfiguration_PrincipalObjectAttributeAccesses

**Added by**: AISolution Solution

See msdyn_aiconfiguration Entity [msdyn_aiconfiguration_PrincipalObjectAttributeAccesses](msdyn_aiconfiguration.md#BKMK_msdyn_aiconfiguration_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aimodel_PrincipalObjectAttributeAccesses"></a> msdyn_aimodel_PrincipalObjectAttributeAccesses

**Added by**: AISolution Solution

See msdyn_aimodel Entity [msdyn_aimodel_PrincipalObjectAttributeAccesses](msdyn_aimodel.md#BKMK_msdyn_aimodel_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aitemplate_PrincipalObjectAttributeAccesses"></a> msdyn_aitemplate_PrincipalObjectAttributeAccesses

**Added by**: AISolution Solution

See msdyn_aitemplate Entity [msdyn_aitemplate_PrincipalObjectAttributeAccesses](msdyn_aitemplate.md#BKMK_msdyn_aitemplate_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aibdataset_PrincipalObjectAttributeAccesses"></a> msdyn_aibdataset_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aibdataset Entity [msdyn_aibdataset_PrincipalObjectAttributeAccesses](msdyn_aibdataset.md#BKMK_msdyn_aibdataset_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aibdatasetfile_PrincipalObjectAttributeAccesses"></a> msdyn_aibdatasetfile_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aibdatasetfile Entity [msdyn_aibdatasetfile_PrincipalObjectAttributeAccesses](msdyn_aibdatasetfile.md#BKMK_msdyn_aibdatasetfile_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aibdatasetrecord_PrincipalObjectAttributeAccesses"></a> msdyn_aibdatasetrecord_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aibdatasetrecord Entity [msdyn_aibdatasetrecord_PrincipalObjectAttributeAccesses](msdyn_aibdatasetrecord.md#BKMK_msdyn_aibdatasetrecord_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aibdatasetscontainer_PrincipalObjectAttributeAccesses"></a> msdyn_aibdatasetscontainer_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aibdatasetscontainer Entity [msdyn_aibdatasetscontainer_PrincipalObjectAttributeAccesses](msdyn_aibdatasetscontainer.md#BKMK_msdyn_aibdatasetscontainer_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aibfile_PrincipalObjectAttributeAccesses"></a> msdyn_aibfile_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aibfile Entity [msdyn_aibfile_PrincipalObjectAttributeAccesses](msdyn_aibfile.md#BKMK_msdyn_aibfile_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aibfileattacheddata_PrincipalObjectAttributeAccesses"></a> msdyn_aibfileattacheddata_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aibfileattacheddata Entity [msdyn_aibfileattacheddata_PrincipalObjectAttributeAccesses](msdyn_aibfileattacheddata.md#BKMK_msdyn_aibfileattacheddata_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aifptrainingdocument_PrincipalObjectAttributeAccesses"></a> msdyn_aifptrainingdocument_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aifptrainingdocument Entity [msdyn_aifptrainingdocument_PrincipalObjectAttributeAccesses](msdyn_aifptrainingdocument.md#BKMK_msdyn_aifptrainingdocument_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aiodimage_PrincipalObjectAttributeAccesses"></a> msdyn_aiodimage_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aiodimage Entity [msdyn_aiodimage_PrincipalObjectAttributeAccesses](msdyn_aiodimage.md#BKMK_msdyn_aiodimage_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aiodlabel_PrincipalObjectAttributeAccesses"></a> msdyn_aiodlabel_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aiodlabel Entity [msdyn_aiodlabel_PrincipalObjectAttributeAccesses](msdyn_aiodlabel.md#BKMK_msdyn_aiodlabel_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aiodtrainingboundingbox_PrincipalObjectAttributeAccesses"></a> msdyn_aiodtrainingboundingbox_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aiodtrainingboundingbox Entity [msdyn_aiodtrainingboundingbox_PrincipalObjectAttributeAccesses](msdyn_aiodtrainingboundingbox.md#BKMK_msdyn_aiodtrainingboundingbox_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_aiodtrainingimage_PrincipalObjectAttributeAccesses"></a> msdyn_aiodtrainingimage_PrincipalObjectAttributeAccesses

**Added by**: AI Solution default templates Solution

See msdyn_aiodtrainingimage Entity [msdyn_aiodtrainingimage_PrincipalObjectAttributeAccesses](msdyn_aiodtrainingimage.md#BKMK_msdyn_aiodtrainingimage_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_analysiscomponent_PrincipalObjectAttributeAccesses"></a> msdyn_analysiscomponent_PrincipalObjectAttributeAccesses

**Added by**: Power Apps Checker Solution

See msdyn_analysiscomponent Entity [msdyn_analysiscomponent_PrincipalObjectAttributeAccesses](msdyn_analysiscomponent.md#BKMK_msdyn_analysiscomponent_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_analysisjob_PrincipalObjectAttributeAccesses"></a> msdyn_analysisjob_PrincipalObjectAttributeAccesses

**Added by**: Power Apps Checker Solution

See msdyn_analysisjob Entity [msdyn_analysisjob_PrincipalObjectAttributeAccesses](msdyn_analysisjob.md#BKMK_msdyn_analysisjob_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_analysisresult_PrincipalObjectAttributeAccesses"></a> msdyn_analysisresult_PrincipalObjectAttributeAccesses

**Added by**: Power Apps Checker Solution

See msdyn_analysisresult Entity [msdyn_analysisresult_PrincipalObjectAttributeAccesses](msdyn_analysisresult.md#BKMK_msdyn_analysisresult_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_analysisresultdetail_PrincipalObjectAttributeAccesses"></a> msdyn_analysisresultdetail_PrincipalObjectAttributeAccesses

**Added by**: Power Apps Checker Solution

See msdyn_analysisresultdetail Entity [msdyn_analysisresultdetail_PrincipalObjectAttributeAccesses](msdyn_analysisresultdetail.md#BKMK_msdyn_analysisresultdetail_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_solutionhealthrule_PrincipalObjectAttributeAccesses"></a> msdyn_solutionhealthrule_PrincipalObjectAttributeAccesses

**Added by**: Power Apps Checker Solution

See msdyn_solutionhealthrule Entity [msdyn_solutionhealthrule_PrincipalObjectAttributeAccesses](msdyn_solutionhealthrule.md#BKMK_msdyn_solutionhealthrule_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_solutionhealthruleargument_PrincipalObjectAttributeAccesses"></a> msdyn_solutionhealthruleargument_PrincipalObjectAttributeAccesses

**Added by**: Power Apps Checker Solution

See msdyn_solutionhealthruleargument Entity [msdyn_solutionhealthruleargument_PrincipalObjectAttributeAccesses](msdyn_solutionhealthruleargument.md#BKMK_msdyn_solutionhealthruleargument_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### <a name="BKMK_msdyn_solutionhealthruleset_PrincipalObjectAttributeAccesses"></a> msdyn_solutionhealthruleset_PrincipalObjectAttributeAccesses

**Added by**: Power Apps Checker Solution

See msdyn_solutionhealthruleset Entity [msdyn_solutionhealthruleset_PrincipalObjectAttributeAccesses](msdyn_solutionhealthruleset.md#BKMK_msdyn_solutionhealthruleset_PrincipalObjectAttributeAccesses) One-To-Many relationship.

### See also

[About entity reference](../about-entity-reference.md)<br />
[Web API reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.principalobjectattributeaccess?text=principalobjectattributeaccess EntityType" />

[!INCLUDE[footer-include](../../../../includes/footer-banner.md)]