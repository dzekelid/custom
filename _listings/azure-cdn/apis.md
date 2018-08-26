---
name: Azure CDN
x-slug: azure-cdn
description: Ensuring a consistent user experience is important. If your websites
  or mobile apps involve streaming media, gaming software, firmware updates (Smart
  TVs, consumer electronic appliances) or IoT endpoints (cars, sensors), Content Delivery
  Network helps you reduce load times, save bandwidth, and increase responsiveness.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Custom
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/apis.md
specificationVersion: "0.14"
apis:
- name: Azure CDN API Custom Domains List By Endpoint
  x-api-slug: azure-cdn-api
  description: Lists all of the existing custom domains within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains
  tags: CDN,Custom Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomains-get-openapi.md
- name: Azure CDN API Custom Domains Get
  x-api-slug: azure-cdn-api
  description: Gets an exisitng custom domain within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}
  tags: CDN,Custom Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-get-openapi.md
- name: Azure CDN API Custom Domains Create
  x-api-slug: azure-cdn-api
  description: Creates a new custom domain within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}
  tags: CDN,Custom Domain
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-put-openapi.md
- name: Azure CDN API Custom Domains Delete
  x-api-slug: azure-cdn-api
  description: Deletes an existing custom domain within an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}
  tags: CDN,Custom Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainname-delete-openapi.md
- name: Azure CDN API Custom Domains Disable Custom Https
  x-api-slug: azure-cdn-api
  description: Disable https delivery of the custom domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}/disableCustomHttps
  tags: CDN,Custom Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnamedisablecustomhttps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnamedisablecustomhttps-post-openapi.md
- name: Azure CDN API Custom Domains Enable Custom Https
  x-api-slug: azure-cdn-api
  description: Enable https delivery of the custom domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Cdn/profiles/{profileName}/endpoints/{endpointName}/customDomains/{customDomainName}/enableCustomHttps
  tags: CDN,Custom Domain
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnameenablecustomhttps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cdnprofilesprofilenameendpointsendpointnamecustomdomainscustomdomainnameenablecustomhttps-post-openapi.md
- name: Azure CDN API
  x-api-slug: azure-cdn-api
  description: Ensuring a consistent user experience is important. If your websites
    or mobile apps involve streaming media, gaming software, firmware updates (Smart
    TVs, consumer electronic appliances) or IoT endpoints (cars, sensors), Content
    Delivery Network helps you reduce load times, save bandwidth, and increase responsiveness.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/02-delivery.png
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: ://management.azure.com//
  tags: Custom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/azure-cdn/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/cdn/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/cdn/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/cdn/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---