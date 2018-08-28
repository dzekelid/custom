---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Delete a custom auction milestone
  version: 1.0.0
  description: Delete a custom auction milestone.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/role/auction/milestone/{roleId}/{milestoneId}:
    delete:
      summary: Delete a custom auction milestone
      description: Delete a custom auction milestone.
      operationId: AuctionRole_DeleteAuctionMilestoneByroleIdBymilestoneId
      x-api-path-slug: apiroleauctionmilestoneroleidmilestoneid-delete
      parameters:
      - in: path
        name: milestoneId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Auction
      - Milestone
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