---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Users API Load custom data
  description: Load custom data.
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
    get:
      summary: Load custom data
      description: Load custom data.
      operationId: load-custom-data
      x-api-path-slug: usersuser-idcustom-datascope-get
      parameters:
      - in: query
        name: ns
        description: The namespace from which to retrieve the data
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