---
swagger: "2.0"
x-collection-name: Standard Chartered
x-complete: 0
info:
  title: Standard Chartered Retrieve trade finance limit details
  description: Retrieve trade finance limit details
  termsOfService: https://www.sc.com/terms-and-conditions
  contact:
    name: Steve Spicer
    url: https://www.sc.com
    email: steven.spicer@sc.com
  version: 1.0.0
host: developer.sc.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /cib/service/s2b/api/v1/trade/{countryCode}/{customerId}/profile:
    get:
      summary: Retrieve trade finance customer profile
      description: Retrieve trade finance customer profile
      operationId: getCibServiceS2bApiV1TradeCountrycodeCustomerProfile
      x-api-path-slug: cibservices2bapiv1tradecountrycodecustomeridprofile-get
      parameters:
      - in: path
        name: countryCode
        description: ISO Country Code
      - in: path
        name: customerId
        description: Customer Reference Id
      responses:
        200:
          description: OK
      tags:
      - Cib
      - Service
      - S2b
      - Api
      - V1
      - Trade
      - Countrycode
      - Customer
      - Profile
  /cib/service/s2b/api/v1/trade/{countryCode}/{customerId}/limits:
    get:
      summary: Retrieve trade finance limit details
      description: Retrieve trade finance limit details
      operationId: getCibServiceS2bApiV1TradeCountrycodeCustomerLimits
      x-api-path-slug: cibservices2bapiv1tradecountrycodecustomeridlimits-get
      parameters:
      - in: path
        name: countryCode
        description: ISO Country Code
      - in: path
        name: customerId
        description: Customer Reference Id
      responses:
        200:
          description: OK
      tags:
      - Cib
      - Service
      - S2b
      - Api
      - V1
      - Trade
      - Countrycode
      - Customer
      - Limits
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