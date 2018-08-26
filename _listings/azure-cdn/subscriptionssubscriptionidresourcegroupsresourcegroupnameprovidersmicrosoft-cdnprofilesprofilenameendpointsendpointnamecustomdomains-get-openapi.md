---
swagger: "2.0"
x-collection-name: Azure CDN
x-complete: 0
info:
  title: Azure CDN API Custom Domains List By Endpoint
  description: Lists all of the existing custom domains within an endpoint.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains
  : get:
      summary: Custom Domains List By Endpoint
      description: Lists all of the existing custom domains within an endpoint.
      operationId: CustomDomains_ListByEndpoint
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomains-get
      parameters:
      - in: path
        name: endpointName
        description: Name of the endpoint under the profile which is unique globally
      - in: query
        name: No Name
      - in: path
        name: profileName
        description: Name of the CDN profile which is unique within the resource group
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Custom Domain
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