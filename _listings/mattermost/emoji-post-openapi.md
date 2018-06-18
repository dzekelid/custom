---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Create a custom emoji
  description: |-
    Create a custom emoji for the team.
    ##### Permissions
    Must be authenticated.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /emoji:
    post:
      summary: Create a custom emoji
      description: |-
        Create a custom emoji for the team.
        ##### Permissions
        Must be authenticated.
      operationId: create-a-custom-emoji-for-the-team-permissionsmust-be-authenticated
      x-api-path-slug: emoji-post
      parameters:
      - in: formData
        name: emoji
        description: A JSON object containing a `name` field with the name of the
          emoji and a `creator_id` field with the id of the authenticated user
      - in: formData
        name: image
        description: A file to be uploaded
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Emoji
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