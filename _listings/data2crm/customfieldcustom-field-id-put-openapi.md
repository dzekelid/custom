---
swagger: "2.0"
x-collection-name: Data2CRM
x-complete: 0
info:
  title: Data2CRM PUT for CustomField
  description: Update custom field information
  version: "1"
host: api.data2crm.com:80
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /customField:
    get:
      summary: GET for CustomField
      description: Returns all custom field from the system
      operationId: getCustomFieldCollection
      x-api-path-slug: customfield-get
      parameters:
      - in: query
        name: entity
        description: Entity
      - in: query
        name: filter
        description: Filter
      - in: query
        name: label
        description: Label
      - in: query
        name: limit
        description: 'Amount of results (default: 25)'
      - in: query
        name: name
        description: Name
      - in: query
        name: offset
        description: 'Start from record (default: 0)'
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-DATA-ENABLE
        description: Data Enable
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Fields
    post:
      summary: POST for CustomField
      description: Add custom field into the system
      operationId: createCustomFieldEntity
      x-api-path-slug: customfield-post
      parameters:
      - in: body
        name: body
        description: Add custom field into the system
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Fields
  /customField/{custom_field_id}:
    delete:
      summary: DELETE for CustomField
      description: Delete custom field information
      operationId: deleteCustomFieldEntity
      x-api-path-slug: customfieldcustom-field-id-delete
      parameters:
      - in: path
        name: custom_field_id
        description: Custom Field Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Fields
      - Custom
      - Field
    get:
      summary: GET for CustomField
      description: Return custom field information
      operationId: getCustomFieldEntity
      x-api-path-slug: customfieldcustom-field-id-get
      parameters:
      - in: path
        name: custom_field_id
        description: Custom Field Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Fields
      - Custom
      - Field
    put:
      summary: PUT for CustomField
      description: Update custom field information
      operationId: updateCustomFieldEntity
      x-api-path-slug: customfieldcustom-field-id-put
      parameters:
      - in: body
        name: body
        description: Update custom field information
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: custom_field_id
        description: Custom Field Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Fields
      - Custom
      - Field
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