---
swagger: "2.0"
x-collection-name: Google Analytics
x-complete: 0
info:
  title: Google Analytics Get Custom Data
  description: List custom data sources to which the user has access.
  contact:
    name: Google
    url: https://google.com
  version: v3
host: www.googleapis.com
basePath: /analytics/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /management/accounts/{accountId}/webproperties/{webPropertyId}/customDataSources:
    get:
      summary: Get Custom Data
      description: List custom data sources to which the user has access.
      operationId: analytics.management.customDataSources.list
      x-api-path-slug: managementaccountsaccountidwebpropertieswebpropertyidcustomdatasources-get
      parameters:
      - in: path
        name: accountId
        description: Account Id for the custom data sources to retrieve
      - in: query
        name: max-results
        description: The maximum number of custom data sources to include in this
          response
      - in: query
        name: start-index
        description: A 1-based index of the first custom data source to retrieve
      - in: path
        name: webPropertyId
        description: Web property Id for the custom data sources to retrieve
      responses:
        200:
          description: OK
      tags:
      - Custom Data
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