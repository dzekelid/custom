---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Get Contactdb Custom Fields
  description: "**This endpoint allows you to retrieve all custom fields.** \n\nThe
    contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)."
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