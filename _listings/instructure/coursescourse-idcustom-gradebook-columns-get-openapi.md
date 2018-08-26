---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API List custom gradebook columns
  description: List custom gradebook columns.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/custom_gradebook_columns:
    get:
      summary: List custom gradebook columns
      description: List custom gradebook columns.
      operationId: list-custom-gradebook-columns
      x-api-path-slug: coursescourse-idcustom-gradebook-columns-get
      parameters:
      - in: query
        name: include_hidden
        description: Include hidden parameters (defaults to false)
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Custom
      - Gradebook
      - Columns
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