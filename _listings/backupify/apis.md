---
name: Backupify
x-slug: backupify
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Custom
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/apis.md
specificationVersion: "0.14"
apis:
- name: Backupify A simple method to test authentication of a customer access token.
  x-api-slug: backupify
  description: A simple method to test authentication of a customer access token..
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/authenticate_customer
  tags: V1,Authenticate,Customer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1authenticate-customer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1authenticate-customer-get-openapi.md
- name: Backupify Retrieve a list of customers associated with the authenticated vendor
  x-api-slug: backupify
  description: Requires Access Token granted from client credentials. Records are
    returned in ascending order (by id), with a default of 20 per page. Links to the
    next, previous, first, and last pages can be found in the response headers.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/customers
  tags: V1,Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1customers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1customers-get-openapi.md
- name: Backupify Create a new customer instance identified by the given {name} identifier
  x-api-slug: backupify
  description: Create a new customer instance identified by the given {name} identifier.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/customers
  tags: V1,Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1customers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1customers-post-openapi.md
- name: Backupify Retrieves the customer identified by customer_id
  x-api-slug: backupify
  description: Requires Access Token granted from client credentials.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/customers/{customer_id}
  tags: V1,Customers,Customer,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1customerscustomer-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1customerscustomer-id-get-openapi.md
- name: Backupify Update a customer instance identified by the given customer_id
  x-api-slug: backupify
  description: Update a customer instance identified by the given customer_id.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/customers/{customer_id}
  tags: V1,Customers,Customer,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1customerscustomer-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1customerscustomer-id-put-openapi.md
- name: Backupify Retrieves a list of backup_instances associated with the specified
    customer
  x-api-slug: backupify
  description: It is only possible to retrieve backup_instances for customers you
    are authorized to access. Records are returned in ascending order (by id), with
    a default of 20 per page. Links to the next, previous, first, and last pages can
    be found in the response headers.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/customers/{customer_id}/backup_instances
  tags: V1,Customers,Customer,Id,Backup,Instances
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1customerscustomer-idbackup-instances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/v1customerscustomer-idbackup-instances-get-openapi.md
- name: Backupify
  x-api-slug: backupify
  description: 'Backupify is a backup service for SaaS accounts. Backupify can help
    users backup their SaaS accounts and restore if and when needed. Backupify offers
    a developers program for developers to access and integrate the functionality
    of Backupify with other applications. Public documentation is not available; interested
    developers should sign up here for more information on the developers program:
    https://www.backupify.com/solutions/developers or email developerprogram@backupify.com.'
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com//
  tags: Custom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/backupify/openapi.md
x-common:
- type: x-blog
  url: https://www.backupify.com/blog
- type: x-website
  url: http://backupify.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---