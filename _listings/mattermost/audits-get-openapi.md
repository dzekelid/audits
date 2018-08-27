---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Get audits
  description: |-
    Get a page of audits for all users on the system, selected with `page` and `per_page` query parameters.
    ##### Permissions
    Must have `manage_system` permission.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/audits:
    get:
      summary: Get users audits
      description: |-
        Get a list of audit by providing the user GUID.
        ##### Permissions
        Must be logged in as the user or have the `edit_other_users` permission.
      operationId: get-a-list-of-audit-by-providing-the-user-guid-permissionsmust-be-logged-in-as-the-user-or-have-the-
      x-api-path-slug: usersuser-idaudits-get
      parameters:
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Users
      - Audits
  /audits:
    get:
      summary: Get audits
      description: |-
        Get a page of audits for all users on the system, selected with `page` and `per_page` query parameters.
        ##### Permissions
        Must have `manage_system` permission.
      operationId: get-a-page-of-audits-for-all-users-on-the-system-selected-with-page-and-per-page-query-parameters-pe
      x-api-path-slug: audits-get
      parameters:
      - in: query
        name: page
        description: The page to select
      - in: query
        name: per_page
        description: The number of audits per page
      responses:
        200:
          description: OK
      tags:
      - Audits
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