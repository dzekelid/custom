---
swagger: "2.0"
x-collection-name: Apica
x-complete: 1
info:
  title: Messages API
  version: 1.0.0
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
---