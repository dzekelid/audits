---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get audit records
  description: Returns auditing records filtered using provided parameters
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/auditing/record:
    get:
      summary: Get audit records
      description: Returns auditing records filtered using provided parameters
      operationId: com.atlassian.jira.rest.v2.admin.auditing.AuditingResource.getAuditRecords_get
      x-api-path-slug: api2auditingrecord-get
      parameters:
      - in: query
        name: filter
        description: \- text query; each record that will be returned must contain
          the provided text in one of its fields
      - in: query
        name: from
        description: \- timestamp in past; from must be less or equal to, otherwise
          the result set will be empty only records that where created in the same
          moment or after the from timestamp will be provided in response
      - in: query
        name: limit
        description: '\- maximum number of returned results (if is limit is  1000,
          it will be set do default value: 1000)'
      - in: query
        name: offset
        description: \- the number of record from which search starts
      - in: query
        name: to
        description: \- timestamp in past; from must be less or equal to, otherwise
          the result set will be empty only records that where created in the same
          moment or earlier than the to timestamp will be provided in response
      responses:
        200:
          description: OK
      tags:
      - Audit
      - Records
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