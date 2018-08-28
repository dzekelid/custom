---
name: Rebilly
x-slug: rebilly
description: ""
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Custom
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/apis.md
specificationVersion: "0.14"
apis:
- name: Rebilly - Retrieve Custom Fields
  x-api-slug: customfieldsresource-get
  description: Retrieve a schema of Custom Fields for the given resource type
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customfieldsresource-get-openapi.md
- name: Rebilly - Delete a custom field
  x-api-slug: customfieldsresourcename-delete
  description: Delete a custom field by its name
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customfieldsresourcename-delete-openapi.md
- name: Rebilly - Retrieve a Custom Field
  x-api-slug: customfieldsresourcename-get
  description: Retrieve a schema of the given Custom Field for the given resource
    type
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customfieldsresourcename-get-openapi.md
- name: Rebilly - Create or alter a Custom Field
  x-api-slug: customfieldsresourcename-put
  description: Create or alter a schema of the given Custom Field for the given resource
    type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customfieldsresourcename-put-openapi.md
- name: Rebilly - Retrieve a list of custom events
  x-api-slug: customevents-get
  description: Retrieve a list of custom events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customevents-get-openapi.md
- name: Rebilly - Create a custom event
  x-api-slug: customevents-post
  description: Create a custom event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customevents-post-openapi.md
- name: Rebilly - Delete a custom event
  x-api-slug: customeventsid-delete
  description: Delete a custom event with predefined identifier string
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customeventsid-delete-openapi.md
- name: Rebilly - Retrieve a custom event
  x-api-slug: customeventsid-get
  description: Retrieve a custom event with predefined identifier string
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customeventsid-get-openapi.md
- name: Rebilly - Create a custom event with predefined ID
  x-api-slug: customeventsid-put
  description: Create a custom event with predefined identifier string
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customeventsid-put-openapi.md
- name: Rebilly - Retrieve the change history of the set of rules for a custom event
  x-api-slug: customeventsidruleshistory-get
  description: |-
    Retrieve the change history of the set of rules for the selected custom event.
    The history is updated each time you change the rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customeventsidruleshistory-get-openapi.md
- name: Rebilly - Retrieve the record from the change history of the set of rules
    for a custom event
  x-api-slug: customeventsidruleshistoryversion-get
  description: |-
    Retrieve the record from the change history of the set of rules for the selected custom event.
    A history record is created each time you change the rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customeventsidruleshistoryversion-get-openapi.md
- name: Rebilly - Retrieve the version of the set of rules for a custom event
  x-api-slug: customeventsidrulesversionsversion-get
  description: |-
    Retrieve the version of the selected set of rules for the selected custom event.
    The versions are created each time you change the rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/customeventsidrulesversionsversion-get-openapi.md
- name: Rebilly - Retrieve a list of scheduled custom events
  x-api-slug: queuecustomevents-get
  description: Retrieve a list of scheduled custom events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/queuecustomevents-get-openapi.md
- name: Rebilly - Delete a scheduled custom event
  x-api-slug: queuecustomeventsid-delete
  description: Delete a scheduled custom event with predefined identifier string
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/queuecustomeventsid-delete-openapi.md
- name: Rebilly - Retrieve a scheduled custom event
  x-api-slug: queuecustomeventsid-get
  description: Retrieve a scheduled custom event with predefined identifier string
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/rebilly.png
  humanURL: https://www.rebilly.com
  baseURL: https://api.rebilly.com//v2.1
  tags: Billing, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/rebilly/queuecustomeventsid-get-openapi.md
x-common:
- type: x-website
  url: https://www.rebilly.com
- type: x-api-gallery
  url: http://rat.genome.database.api.gallery.streamdata.io
- type: x-api-stack
  url: http://rebilly.stack.network
- type: x-documentation
  url: https://rebilly.github.io/RebillyAPI/#
- type: x-github
  url: https://github.com/Rebilly
- type: x-license-agreement
  url: https://www.rebilly.com/api-license/
- type: x-openapi
  url: https://rebilly.github.io/RebillyAPI/swagger.json
- type: x-pricing
  url: https://www.rebilly.com/pricing/
- type: x-privacy-policy
  url: https://www.rebilly.com/privacy-policy/
- type: x-support
  url: https://help.rebilly.com/
- type: x-terms-of-service
  url: https://www.rebilly.com/terms-of-use/
- type: x-twitter
  url: https://twitter.com/RebillyInc
- type: x-website
  url: http://rebilly.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---