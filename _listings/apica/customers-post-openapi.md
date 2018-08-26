---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Customers API Customers
  version: 1.0.0
  description: Creates customer.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/customers/{customerId} ':
    ' get ':
      summary: Customers {customerId}
      description: Returns subcustomer by subcustomer's ID.
      operationId: -customers-customerid-
      x-api-path-slug: customerscustomerid-get
      responses:
        200:
          description: OK
      tags:
      - Customers
  '/customers ':
    ' post ':
      summary: Customers
      description: Creates customer.
      operationId: -customers-
      x-api-path-slug: customers-post
      responses:
        200:
          description: OK
      tags:
      - Customers
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