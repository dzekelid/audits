---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Audit Audittrail Action List
  description: List audit trail objects by filter and pager
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/audit_audittrail/action/add:
    get:
      summary: Get Service Audit Audittrail Action Add
      description: Allows you to add an audit trail object and audit trail content
        associated with Kaltura object
      operationId: auditTrail.add
      x-api-path-slug: serviceaudit-audittrailactionadd-get
      parameters:
      - in: query
        name: auditTrail[action]
        description: 'Enum Type: `KalturaAuditTrailAction`'
      - in: query
        name: auditTrail[auditObjectType]
        description: 'Enum Type: `KalturaAuditTrailObjectType`'
      - in: query
        name: auditTrail[data][changedItems]
      - in: query
        name: auditTrail[data][dc]
      - in: query
        name: auditTrail[data][fileType]
        description: 'Enum Type: `KalturaAuditTrailFileSyncType`'
      - in: query
        name: auditTrail[data][info]
      - in: query
        name: auditTrail[data][objectSubType]
      - in: query
        name: auditTrail[data][objectType]
      - in: query
        name: auditTrail[data][original]
      - in: query
        name: auditTrail[data][version]
      - in: query
        name: auditTrail[entryId]
      - in: query
        name: auditTrail[objectId]
      - in: query
        name: auditTrail[relatedObjectId]
      - in: query
        name: auditTrail[relatedObjectType]
        description: 'Enum Type: `KalturaAuditTrailObjectType`'
      - in: query
        name: auditTrail[userId]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Audit
      - Audittrail
      - Action
      - Add
  /service/audit_audittrail/action/get:
    get:
      summary: Get Service Audit Audittrail Action Get
      description: Retrieve an audit trail object by id
      operationId: auditTrail.get
      x-api-path-slug: serviceaudit-audittrailactionget-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Audit
      - Audittrail
      - Action
      - Get
  /service/audit_audittrail/action/list:
    get:
      summary: Get Service Audit Audittrail Action List
      description: List audit trail objects by filter and pager
      operationId: auditTrail.list
      x-api-path-slug: serviceaudit-audittrailactionlist-get
      parameters:
      - in: query
        name: filter[actionEqual]
        description: 'Enum Type: `KalturaAuditTrailAction`'
      - in: query
        name: filter[actionIn]
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[auditObjectTypeEqual]
        description: 'Enum Type: `KalturaAuditTrailObjectType`'
      - in: query
        name: filter[auditObjectTypeIn]
      - in: query
        name: filter[clientTagEqual]
      - in: query
        name: filter[contextEqual]
        description: 'Enum Type: `KalturaAuditTrailContext`'
      - in: query
        name: filter[contextIn]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[entryIdIn]
      - in: query
        name: filter[entryPointEqual]
      - in: query
        name: filter[entryPointIn]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[ipAddressEqual]
      - in: query
        name: filter[ipAddressIn]
      - in: query
        name: filter[ksEqual]
      - in: query
        name: filter[masterPartnerIdEqual]
      - in: query
        name: filter[masterPartnerIdIn]
      - in: query
        name: filter[objectIdEqual]
      - in: query
        name: filter[objectIdIn]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[parsedAtGreaterThanOrEqual]
      - in: query
        name: filter[parsedAtLessThanOrEqual]
      - in: query
        name: filter[partnerIdEqual]
      - in: query
        name: filter[partnerIdIn]
      - in: query
        name: filter[relatedObjectIdEqual]
      - in: query
        name: filter[relatedObjectIdIn]
      - in: query
        name: filter[relatedObjectTypeEqual]
        description: 'Enum Type: `KalturaAuditTrailObjectType`'
      - in: query
        name: filter[relatedObjectTypeIn]
      - in: query
        name: filter[requestIdEqual]
      - in: query
        name: filter[requestIdIn]
      - in: query
        name: filter[serverNameEqual]
      - in: query
        name: filter[serverNameIn]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaAuditTrailStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[userIdEqual]
      - in: query
        name: filter[userIdIn]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Audit
      - Audittrail
      - Action
      - List
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---