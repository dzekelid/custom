---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: Entertainment Express Get GBUsage by Customer ID.
  description: Requires a valid Customer ID.
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Analytics/GBUsage/:
    get:
      summary: Get GBUsage by Customer ID.
      description: Requires a valid Customer ID.
      operationId: GetAnalyticsGBUsage
      x-api-path-slug: analyticsgbusage-get
      parameters:
      - in: query
        name: Month
        description: Report month
      - in: query
        name: ReportTag
        description: Report Tag filter
      - in: query
        name: Year
        description: Report year
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - GBUsage
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