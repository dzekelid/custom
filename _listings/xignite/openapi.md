---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Statistics
  description: delivers-and-charts-more-than-1400-economical-timeseries-fom-the-federal-reserve-bank-
  version: 1.0.0
host: www.xignite.com
basePath: xStatistics.json/XigniteStatistics
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  Topic, , Custom:
    get:
      summary: Get Topic Chart Custom
      description: Get time-series data and a URL to a custom chart for a topic.
      operationId: postGettopicchartcustom
      x-api-path-slug: topic--custom-get
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
      - Topic
      - Chart
      - Custom
  Topic, Binary, , Custom:
    get:
      summary: Get Topic Binary Chart Custom
      description: Get time-series and a custom chart in binary format for a topic.
      operationId: postGettopicbinarychartcustom
      x-api-path-slug: topic-binary--custom-get
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
      - Topic
      - Binary
      - Chart
      - Custom
  ', Url, Custom':
    get:
      summary: Get Chart Url Custom
      description: Get chart url for a topic.
      operationId: postGetcharturlcustom
      x-api-path-slug: url-custom-get
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
      - Chart
      - Url
      - Custom
  ', Binary, Custom':
    get:
      summary: Get Chart Binary Custom
      description: Get chart in binary format for a topic.
      operationId: postGetchartbinarycustom
      x-api-path-slug: binary-custom-get
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
      - Chart
      - Binary
      - Custom
---