---
swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 0
info:
  title: Jumpseller Get Checkout Custom Fields
  description: Retrieve all checkout custom fields..
  version: "1"
host: api.jumpseller.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /checkout_custom_fields.json:
    get:
      summary: Get Checkout Custom Fields
      description: Retrieve all checkout custom fields..
      operationId: getCheckoutCustomFields.json
      x-api-path-slug: checkout-custom-fields-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Custom
      - Fields
      - Json
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