---
swagger: "2.0"
x-collection-name: Square
x-complete: 0
info:
  title: Square Connect API ListCustomers
  description: Lists a business's customers.
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/customers:
    get:
      summary: ListCustomers
      description: Lists a business's customers.
      operationId: ListCustomers
      x-api-path-slug: v2customers-get
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: query
        name: cursor
        description: A pagination cursor returned by a previous call to this endpoint
      responses:
        200:
          description: OK
      tags:
      - ListCustomers
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---