---
swagger: "2.0"
info:
  title: Akamai API Reactivate a Client
  description: Reactivate a Client
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /galaxy/v1/customers/{clientId}/op/reactivate:
    post:
      summary: Reactivate a Client
      description: Reactivate a Client
      operationId: galaxyv1customersclientidopreactivate
      parameters:
      - in: query
        name: clientId
        description: Client ID of the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - galaxy
      - customers
      - client
      - op
      - reactivate
definitions: []
x-collection-name: Akamai
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