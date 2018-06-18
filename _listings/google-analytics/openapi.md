---
swagger: "2.0"
x-collection-name: Google Analytics
x-complete: 1
info:
  title: Google Analytics
  description: views-and-manages-your-google-analytics-data-
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
---