---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API Create a custom gradebook column
  description: Create a custom gradebook column.
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
    post:
      summary: Create a custom gradebook column
      description: Create a custom gradebook column.
      operationId: create-a-custom-gradebook-column
      x-api-path-slug: coursescourse-idcustom-gradebook-columns-post
      parameters:
      - in: query
        name: column[hidden]
        description: Hidden columns are not displayed in the gradebook
      - in: query
        name: column[position]
        description: The position of the column relative to other custom columns
      - in: query
        name: column[teacher_notes]
        description: Set this if the column is created by a teacher
      - in: query
        name: column[title]
        description: no description
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