---
swagger: "2.0"
x-collection-name: Apica
x-complete: 0
info:
  title: Messages API Messages?active={active}&amp;customerId={customerId}
  version: 1.0.0
  description: Gets a list of UI messages. UI messages are used for user notifications
    on announcements/information/warnings.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '/messages?active={active}&amp;customerId={customerId} ':
    ' get ':
      summary: Messages?active={active}&amp;customerId={customerId}
      description: Gets a list of UI messages. UI messages are used for user notifications
        on announcements/information/warnings.
      operationId: getMessagesActiveActive&amp;customerCustomer
      x-api-path-slug: messagesactiveactiveampcustomeridcustomerid-get
      responses:
        200:
          description: OK
      tags:
      - Messages?active=active&amp;customerId=customerId
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