---
name: BMC Software
x-slug: bmc-software
description: Transform your digital enterprise with BMC IT solutions. From mainframe
  to cloud to mobile, we???ll help you drive innovation and industrial efficiency.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
x-kinRank: "8"
x-alexaRank: "27308"
tags: Custom
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/apis.md
specificationVersion: "0.14"
apis:
- name: BMC Software API Events?message={message}&amp;severity={severity}&amp;timestamp_utc_from={timestamp_utc_from}&amp;timestamp_utc_to={timestamp_utc_to}
  x-api-slug: bmc-software-api
  description: Gets a list of events for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: 'https://///events?message={message}&amp;severity={severity}&amp;timestamp_utc_from={timestamp_utc_from}&amp;timestamp_utc_to={timestamp_utc_to} '
  tags: Custom Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/eventsmessagemessageampseverityseverityamptimestamp-utc-fromtimestamp-utc-fromamptimestamp-utc-totimestamp-utc-to-get-openapi.md
- name: BMC Software API Custom Events
  x-api-slug: bmc-software-api
  description: Creates new custom event.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: 'https://///custom_events '
  tags: Custom Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/custom-events-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/custom-events-post-openapi.md
- name: BMC Software API Custom_events All?fromUtc={fromUtc}&amp;toUtc={toUtc}
  x-api-slug: bmc-software-api
  description: Gets all custom events using optional filter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: 'https://///custom_events/all?fromUtc={fromUtc}&amp;toUtc={toUtc} '
  tags: Custom Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/custom-eventsallfromutcfromutcamptoutctoutc-get-openapi.md
- name: BMC Software API Custom_events {id}
  x-api-slug: bmc-software-api
  description: Gets custom event by Id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: 'https://///custom_events/{id} '
  tags: Custom Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/custom-eventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/custom-eventsid-get-openapi.md
- name: BMC Software API Custom_events {id}
  x-api-slug: bmc-software-api
  description: Updates custom event.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: 'https://///custom_events/{id} '
  tags: Custom Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/custom-eventsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/custom-eventsid-put-openapi.md
- name: BMC Software API Custom_events {id}
  x-api-slug: bmc-software-api
  description: Deletes custom event.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: 'https://///custom_events/{id} '
  tags: Custom Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/custom-eventsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/custom-eventsid-delete-openapi.md
- name: BMC Software API
  x-api-slug: bmc-software-api
  description: Transform your digital enterprise with BMC IT solutions. From mainframe
    to cloud to mobile, we???ll help you drive innovation and industrial efficiency.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/713-bmc-software.jpg
  humanURL: http://www.bmc.com
  baseURL: https:///
  tags: Custom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/bmc-software/openapi.md
x-common:
- type: x-blog
  url: http://www.bmc.com/blogs
- type: x-blog-rss
  url: http://feeds.feedburner.com/BmcBlogs
- type: x-crunchbase
  url: https://crunchbase.com/organization/bmc
- type: x-documentation
  url: https://docs.bmc.com/docs/dashboard.action
- type: x-email
  url: customer_support@bmc.com
- type: x-email
  url: NA_Accounts_Payable@bmc.com
- type: x-email
  url: Collections_NA@bmc.com
- type: x-email
  url: education@bmc.com
- type: x-email
  url: investor@bmc.com
- type: x-email
  url: global_security@bmc.com
- type: x-email
  url: Compliance_EthicsOffice@bmc.com
- type: x-email
  url: 26Ethics@bmc.com
- type: x-email
  url: Community_Relations@bmc.com
- type: x-github
  url: https://github.com/bmcsoftware
- type: x-twitter
  url: https://twitter.com/bmcsoftware
- type: x-website
  url: http://www.bmc.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---