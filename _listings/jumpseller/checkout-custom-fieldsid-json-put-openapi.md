---
swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 0
info:
  title: Jumpseller Put Checkout Custom Fields
  description: Update a checkoutcustomfield..
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
    post:
      summary: Post Checkout Custom Fields
      description: Create a new checkoutcustomfield..
      operationId: postCheckoutCustomFields.json
      x-api-path-slug: checkout-custom-fields-json-post
      parameters:
      - in: body
        name: body
        description: CheckoutCustomField parameters
        schema:
          $ref: '#/definitions/holder'
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
  /checkout_custom_fields/{id}.json:
    delete:
      summary: Delete Checkout Custom Fields
      description: Delete an existing checkoutcustomfield..
      operationId: deleteCheckoutCustomFields.json
      x-api-path-slug: checkout-custom-fieldsid-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the CheckoutCustomField
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Custom
      - Fields
      - Id
      - Json
    get:
      summary: Get Checkout Custom Fields
      description: Retrieve a single checkoutcustomfield..
      operationId: getCheckoutCustomFields.json
      x-api-path-slug: checkout-custom-fieldsid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the CheckoutCustomField
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Custom
      - Fields
      - Id
      - Json
    put:
      summary: Put Checkout Custom Fields
      description: Update a checkoutcustomfield..
      operationId: putCheckoutCustomFields.json
      x-api-path-slug: checkout-custom-fieldsid-json-put
      parameters:
      - in: body
        name: body
        description: CheckoutCustomField parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the CheckoutCustomField
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Custom
      - Fields
      - Id
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