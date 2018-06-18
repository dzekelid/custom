---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  description: the-sendgrid-web-api-v3-documentation--this-is-the-entirety-of-the-documented-v3-endpoints--we-have-updated-all-the-descriptions-parameters-requests-and-responses--authentication-every-endpoint-requires-authentication-in-the-form-of-an-authorization-header-authorization-bearer-api-key
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /contactdb/custom_fields:
    get:
      summary: Get Contactdb Custom Fields
      description: "**This endpoint allows you to retrieve all custom fields.** \n\nThe
        contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)."
      operationId: contactdb.custom_fields.get
      x-api-path-slug: contactdbcustom-fields-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Custom
      - Fields
    post:
      summary: Add Contactdb Custom Fields
      description: |-
        **This endpoint allows you to create a custom field.**

        The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).
      operationId: contactdb.custom_fields.post
      x-api-path-slug: contactdbcustom-fields-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Custom
      - Fields
  /contactdb/custom_fields/{custom_field_id}:
    delete:
      summary: Delete Contactdb Custom Fields Custom Field
      description: |-
        **This endpoint allows you to delete a custom field by ID.**

        The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).
      operationId: contactdb.custom_fields.custom_field_id.delete
      x-api-path-slug: contactdbcustom-fieldscustom-field-id-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Custom
      - Fields
      - Custom
      - Field
    get:
      summary: Get Contactdb Custom Fields Custom Field
      description: |-
        **This endpoint allows you to retrieve a custom field by ID.**

        The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).
      operationId: contactdb.custom_fields.custom_field_id.get
      x-api-path-slug: contactdbcustom-fieldscustom-field-id-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Custom
      - Fields
      - Custom
      - Field
---