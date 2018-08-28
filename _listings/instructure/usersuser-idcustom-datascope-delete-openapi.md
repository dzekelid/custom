---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Users API Delete custom data
  description: Delete custom data.
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
  /courses/{course_id}/custom_gradebook_columns/id:
    delete:
      summary: Delete a custom gradebook column
      description: Delete a custom gradebook column.
      operationId: delete-a-custom-gradebook-column
      x-api-path-slug: coursescourse-idcustom-gradebook-columnsid-delete
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
      - Id
    put:
      summary: Update a custom gradebook column
      description: Update a custom gradebook column.
      operationId: update-a-custom-gradebook-column
      x-api-path-slug: coursescourse-idcustom-gradebook-columnsid-put
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
      - Id
  /courses/{course_id}/custom_gradebook_columns/id/data:
    get:
      summary: List entries for a column
      description: List entries for a column.
      operationId: list-entries-for-a-column
      x-api-path-slug: coursescourse-idcustom-gradebook-columnsiddata-get
      parameters:
      - in: query
        name: include_hidden
        description: If true, hidden columns will be included in the result
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
      - Id
      - Data
  /courses/{course_id}/custom_gradebook_columns/id/data/{user_id}:
    put:
      summary: Update column data
      description: Update column data.
      operationId: update-column-data
      x-api-path-slug: coursescourse-idcustom-gradebook-columnsiddatauser-id-put
      parameters:
      - in: query
        name: column_data[content]
        description: Column content
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
      - Id
      - Data
      - User
      - Id
  /courses/{course_id}/custom_gradebook_columns/reorder:
    post:
      summary: Reorder custom columns
      description: Reorder custom columns.
      operationId: reorder-custom-columns
      x-api-path-slug: coursescourse-idcustom-gradebook-columnsreorder-post
      parameters:
      - in: query
        name: order[]
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
      - Reorder
  /users/{user_id}/custom_data(/*scope):
    delete:
      summary: Delete custom data
      description: Delete custom data.
      operationId: delete-custom-data
      x-api-path-slug: usersuser-idcustom-datascope-delete
      parameters:
      - in: query
        name: ns
        description: The namespace from which to delete the data
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Custom
      - Data(
      - '*scope)'
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