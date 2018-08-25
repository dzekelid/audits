---
swagger: "2.0"
x-collection-name: Watchful
x-complete: 1
info:
  title: Watchful
  description: watchful-resulted-from-the-need-for-a-single-unified-dashboard-to-easily-monitor-all-of-the-web-sites-in-our-portfolios--after-years-of-evolution-our-solution-has-matured-into-a-simple-complete-and-professional-service--
  version: 1.0.0
host: watchful.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /audits:
    get:
      summary: Get A List Of Audits
      description: Returns a list of audits
      operationId: getAudits
      x-api-path-slug: audits-get
      parameters:
      - in: query
        name: limit
        description: Number of object to return (max 100, default 25)
      - in: query
        name: limitstart
        description: Start of the return (default 0)
      - in: query
        name: order
        description: ORDER by this field separete by comas
      responses:
        200:
          description: OK
      tags:
      - Audits
    post:
      summary: Create A Audit
      description: Create a audit.
      operationId: CreateAudits
      x-api-path-slug: audits-post
      parameters:
      - in: body
        name: body
        description: JSON object Audit
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Audits
  /audits/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: getFieldsAudits
      x-api-path-slug: auditsmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Audits
      - Metadata
  /audits/{id}:
    delete:
      summary: Delete A Specific Audit
      description: Delete a specific audit.
      operationId: deleteAuditById
      x-api-path-slug: auditsid-delete
      parameters:
      - in: path
        name: id
        description: ID of audit that needs to be deleted
      responses:
        200:
          description: OK
      tags:
      - Audits
      - Id
    get:
      summary: Find Audit By ID
      description: Returns a audit based on ID
      operationId: getAuditById
      x-api-path-slug: auditsid-get
      parameters:
      - in: query
        name: fields
        description: 'Fields to return separate by comas: name,id'
      - in: path
        name: id
        description: ID of audit that needs to be fetched
      responses:
        200:
          description: OK
      tags:
      - Audits
      - Id
  /sites/{id}/audits:
    get:
      summary: Return Audits For A Specific Website
      description: Return audits for a specific website
      operationId: getSiteAudits
      x-api-path-slug: sitesidaudits-get
      parameters:
      - in: query
        name: fields
        description: 'Fields to return separate by comas: name,id'
      - in: path
        name: id
        description: ID of the website
      - in: query
        name: limit
        description: Number of object to return (max 100, default 25)
      - in: query
        name: limitstart
        description: Start of the return (default 0)
      - in: query
        name: order
        description: ORDER by this field
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Id
      - Audits
    post:
      summary: Create An Audit For The Site
      description: Create an audit for the site
      operationId: createAudits
      x-api-path-slug: sitesidaudits-post
      parameters:
      - in: path
        name: id
        description: ID of the website
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Id
      - Audits
---