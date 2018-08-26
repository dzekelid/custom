---
swagger: "2.0"
x-collection-name: VersaPay
x-complete: 0
info:
  title: VersaPay Create and Update Customer
  description: |-
    Create a customer in ARC using the following attributes (at minimum by providing values for required attributes). If providing an identifier for an existing customer, its information is updated.<br><br>
    *Note: Any additional non-standard attribute will be stored with customer record and available for presentment rendering.*
  contact:
    name: VersaPay Support
    url: https://www.versapay.com/support
    email: support@versapay.com
  version: 1.0.0
host: secure.versapay.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/imports/customer:
    post:
      summary: Create and Update Customer
      description: |-
        Create a customer in ARC using the following attributes (at minimum by providing values for required attributes). If providing an identifier for an existing customer, its information is updated.<br><br>
        *Note: Any additional non-standard attribute will be stored with customer record and available for presentment rendering.*
      operationId: createCustomer
      x-api-path-slug: apiimportscustomer-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Customer
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