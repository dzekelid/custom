---
swagger: "2.0"
x-collection-name: Azure CDN
x-complete: 1
info:
  title: CdnManagementClient
  description: use-these-apis-to-manage-azure-cdn-resources-through-the-azure-resource-manager--you-must-make-sure-that-requests-made-to-these-resources-are-secure-
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}
  : get:
      summary: Custom Domains Get
      description: Gets an exisitng custom domain within an endpoint.
      operationId: CustomDomains_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-get
      parameters:
      - in: path
        name: customDomainName
        description: Name of the custom domain within an endpoint
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
    put:
      summary: Custom Domains Create
      description: Creates a new custom domain within an endpoint.
      operationId: CustomDomains_Create
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-put
      parameters:
      - in: path
        name: customDomainName
        description: Name of the custom domain within an endpoint
      - in: body
        name: customDomainProperties
        description: Properties required to create a new custom domain
        schema:
          $ref: '#/definitions/holder'
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
    delete:
      summary: Custom Domains Delete
      description: Deletes an existing custom domain within an endpoint.
      operationId: CustomDomains_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-delete
      parameters:
      - in: path
        name: customDomainName
        description: Name of the custom domain within an endpoint
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}/disableCustomHttps
  : post:
      summary: Custom Domains Disable Custom Https
      description: Disable https delivery of the custom domain.
      operationId: CustomDomains_DisableCustomHttps
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnamedisablecustomhttps-post
      parameters:
      - in: path
        name: customDomainName
        description: Name of the custom domain within an endpoint
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}/enableCustomHttps
  : post:
      summary: Custom Domains Enable Custom Https
      description: Enable https delivery of the custom domain.
      operationId: CustomDomains_EnableCustomHttps
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnameenablecustomhttps-post
      parameters:
      - in: path
        name: customDomainName
        description: Name of the custom domain within an endpoint
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
---