---
name: Data2CRM
x-slug: data2crm
description: Data2CRM is all-in-one master touch instrument to create the perfect
  data environment for prosperous internal and external connections.Data2CRM.API,
  a Unified API Provider, to Connect Your Business Software with 17+ CRMs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data2crm-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Custom
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/data2crm/apis.md
specificationVersion: "0.14"
apis:
- name: Data2CRM GET for CustomField
  x-api-slug: data2crm
  description: Returns all custom field from the system
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data2crm-logo.png
  humanURL: http://data2crm.com
  baseURL: https://api.data2crm.com:80//v1//customField
  tags: Custom, Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/data2crm/customfield-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/data2crm/customfield-get-openapi.md
- name: Data2CRM POST for CustomField
  x-api-slug: data2crm
  description: Add custom field into the system
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data2crm-logo.png
  humanURL: http://data2crm.com
  baseURL: https://api.data2crm.com:80//v1//customField
  tags: Custom, Fields
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/data2crm/customfield-post-openapi.md
- name: Data2CRM DELETE for CustomField
  x-api-slug: data2crm
  description: Delete custom field information
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data2crm-logo.png
  humanURL: http://data2crm.com
  baseURL: https://api.data2crm.com:80//v1//customField/{custom_field_id}
  tags: Custom, Fields,Custom,Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/data2crm/customfieldcustom-field-id-delete-openapi.md
- name: Data2CRM GET for CustomField
  x-api-slug: data2crm
  description: Return custom field information
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data2crm-logo.png
  humanURL: http://data2crm.com
  baseURL: https://api.data2crm.com:80//v1//customField/{custom_field_id}
  tags: Custom, Fields,Custom,Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/data2crm/customfieldcustom-field-id-get-openapi.md
- name: Data2CRM PUT for CustomField
  x-api-slug: data2crm
  description: Update custom field information
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data2crm-logo.png
  humanURL: http://data2crm.com
  baseURL: https://api.data2crm.com:80//v1//customField/{custom_field_id}
  tags: Custom, Fields,Custom,Field
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/data2crm/customfieldcustom-field-id-put-openapi.md
- name: Data2CRM
  x-api-slug: data2crm
  description: Data2CRM is all-in-one master touch instrument to create the perfect
    data environment for prosperous internal and external connections.Data2CRM.API,
    a Unified API Provider, to Connect Your Business Software with 17+ CRMs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data2crm-logo.png
  humanURL: http://data2crm.com
  baseURL: https://api.data2crm.com:80//v1
  tags: Custom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/data2crm/openapi.md
x-common:
- type: x-twitter
  url: https://twitter.com/data2crm
- type: x-website
  url: http://data2crm.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---