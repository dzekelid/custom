---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Currencies Get Currency Chart Custom Binary
  description: Draw a custom currency chart for a date range.
  version: 1.0.0
host: www.xignite.com/xCurrencies.json
basePath: /XigniteCurrencies
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  Currency, , Custom:
    get:
      summary: Get Currency Chart Custom
      description: Draw a custom currency chart for a date range.
      operationId: postGetcurrencychartcustom
      x-api-path-slug: currency--custom-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Currency
      - Chart
      - Custom
  Currency, , Custom, Binary:
    get:
      summary: Get Currency Chart Custom Binary
      description: Draw a custom currency chart for a date range.
      operationId: postGetcurrencychartcustombinary
      x-api-path-slug: currency--custom-binary-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Currency
      - Chart
      - Custom
      - Binary
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