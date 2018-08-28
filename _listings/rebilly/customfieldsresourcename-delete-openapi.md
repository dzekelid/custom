---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Delete a custom field
  description: Delete a custom field by its name
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /custom-fields/{resource}:
    get:
      summary: Retrieve Custom Fields
      description: Retrieve a schema of Custom Fields for the given resource type
      operationId: custom_fields.resource.get
      x-api-path-slug: customfieldsresource-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Custom
      - Fields
  /custom-fields/{resource}/{name}:
    delete:
      summary: Delete a custom field
      description: Delete a custom field by its name
      operationId: custom_fields.resource.name.delete
      x-api-path-slug: customfieldsresourcename-delete
      responses:
        200:
          description: OK
      tags:
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