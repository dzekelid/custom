---
swagger: "2.0"
x-collection-name: BMC Software
x-complete: 1
info:
  title: BMC Software Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? '/events?message={message}&amp;severity={severity}&amp;timestamp_utc_from={timestamp_utc_from}&amp;timestamp_utc_to={timestamp_utc_to} '
  : ' get ':
      summary: Events?message={message}&amp;severity={severity}&amp;timestamp_utc_from={timestamp_utc_from}&amp;timestamp_utc_to={timestamp_utc_to}
      description: Gets a list of events for the current user.
      operationId: -eventsmessagemessageampseverityseverityamptimestamp-utc-fromtimestamp-utc-fromamptimestamp-utc-toti
      x-api-path-slug: eventsmessagemessageampseverityseverityamptimestamp-utc-fromtimestamp-utc-fromamptimestamp-utc-totimestamp-utc-to-get
      responses:
        200:
          description: OK
      tags:
      - Custom Events
  '/custom_events ':
    ' post ':
      summary: Custom Events
      description: Creates new custom event.
      operationId: -custom-events-
      x-api-path-slug: custom-events-post
      responses:
        200:
          description: OK
      tags:
      - Custom Events
  '/custom_events/all?fromUtc={fromUtc}&amp;toUtc={toUtc} ':
    ' get ':
      summary: Custom_events All?fromUtc={fromUtc}&amp;toUtc={toUtc}
      description: Gets all custom events using optional filter.
      operationId: -custom-events-allfromutcfromutcamptoutctoutc-
      x-api-path-slug: custom-eventsallfromutcfromutcamptoutctoutc-get
      responses:
        200:
          description: OK
      tags:
      - Custom Events
  '/custom_events/{id} ':
    ' get ':
      summary: Custom_events {id}
      description: Gets custom event by Id.
      operationId: -custom-events-id-
      x-api-path-slug: custom-eventsid-get
      responses:
        200:
          description: OK
      tags:
      - Custom Events
    ' put ':
      summary: Custom_events {id}
      description: Updates custom event.
      operationId: -custom-events-id-
      x-api-path-slug: custom-eventsid-put
      responses:
        200:
          description: OK
      tags:
      - Custom Events
    ' delete ':
      summary: Custom_events {id}
      description: Deletes custom event.
      operationId: -custom-events-id-
      x-api-path-slug: custom-eventsid-delete
      responses:
        200:
          description: OK
      tags:
      - Custom Events
---