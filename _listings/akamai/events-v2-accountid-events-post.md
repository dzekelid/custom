---
swagger: "2.0"
info:
  title: Akamai API POST a New Event
  description: POST a New Event
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
  /events/v2/{accountId}/events:
    post:
      summary: POST a New Event
      description: POST a New Event
      operationId: eventsv2accountideventsstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: customerEventId
        description: Event identifier for your own use
        type: string
      - in: query
        name: endRange
        description: End of event, specified as epoch time milliseconds
        type: string
      - in: query
        name: limit
        description: The maximum number of pagination records to include
        type: string
      - in: query
        name: sortField
        description: The field that should be used to sort the result set
        type: string
      - in: query
        name: sortOrder
        description: The direction of the sort, asc for ascending or desc for descending
        type: string
      - in: query
        name: startIndex
        description: The zero-origin index at which to start the batch of paginated
          results
        type: string
      - in: query
        name: startRange
        description: Start of event, specified as epoch time milliseconds
        type: string
      responses:
        200:
          description: OK
      tags:
      - events
      - account
      - events
      - startrange
      - endrange
      - sortfield
      - sortorder
      - startindex
      - limit
      - customerevent
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