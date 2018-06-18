---
swagger: "2.0"
x-collection-name: Google Apps Admin SDK
x-complete: 0
info:
  title: Google Apps Admin SDK API Update Customer
  version: 1.0.0
  description: Update a customer account's settings.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /customers:
    post:
      summary: Create Customer
      description: Order a new customer's account.
      operationId: reseller.customers.insert
      x-api-path-slug: customers-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: customerAuthToken
        description: The customerAuthToken query string is required when creating
          a resold account that transfers a direct customers subscription or transfers
          another reseller customers subscription to your reseller management
      responses:
        200:
          description: OK
      tags:
      - Customer
  /customers/{customerId}:
    get:
      summary: Get Customer
      description: Get a customer account.
      operationId: reseller.customers.get
      x-api-path-slug: customerscustomerid-get
      parameters:
      - in: path
        name: customerId
        description: Either the customers primary domain name or the customers unique
          identifier
      responses:
        200:
          description: OK
      tags:
      - Customer
    patch:
      summary: Update Customer
      description: Update a customer account's settings. This method supports patch
        semantics.
      operationId: reseller.customers.patch
      x-api-path-slug: customerscustomerid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customerId
        description: Either the customers primary domain name or the customers unique
          identifier
      responses:
        200:
          description: OK
      tags:
      - Customer
    put:
      summary: Update Customer
      description: Update a customer account's settings.
      operationId: reseller.customers.update
      x-api-path-slug: customerscustomerid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: customerId
        description: Either the customers primary domain name or the customers unique
          identifier
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