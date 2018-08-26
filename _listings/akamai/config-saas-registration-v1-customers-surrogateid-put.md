---
swagger: "2.0"
info:
  title: Akamai API Modify a Customer
  description: Modify a Customer
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
  /config-saas-registration/v1/customers/{surrogateId}/:
    put:
      summary: Modify a Customer
      description: Modify a Customer
      operationId: configsaasregistrationv1customerssurrogateidcontractid
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 456
        type: string
      responses:
        200:
          description: OK
      tags:
      - configurations
      - saas
      - registration
      - customers
      - surrogate
      - contract
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