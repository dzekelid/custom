---
name: Square
x-slug: square
description: Square helps millions of sellers run their business- from secure credit
  card processing to point of sale solutions. Get paid faster with Square and sign
  up today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
x-kinRank: "9"
x-alexaRank: "2436"
tags: Custom
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/square/apis.md
specificationVersion: "0.14"
apis:
- name: Square Connect API ListCustomers
  x-api-slug: square-connect-api
  description: Lists a business's customers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/customers
  tags: ListCustomers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/square/v2customers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/square/v2customers-get-openapi.md
- name: Square Connect API CreateCustomer
  x-api-slug: square-connect-api
  description: |-
    Creates a new customer for a business, which can have associated cards on file.

    You must provide __at least one__ of the following values in your request to this
    endpoint:

    - `given_name`
    - `family_name`
    - `company_name`
    - `email_address`
    - `phone_number`

    This endpoint does not accept an idempotency key. If you accidentally create
    a duplicate customer, you can delete it with the
    [DeleteCustomer](#endpoint-deletecustomer) endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/customers
  tags: CreateCustomer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/square/v2customers-post-openapi.md
- name: Square Connect API DeleteCustomer
  x-api-slug: square-connect-api
  description: Deletes a customer from a business, along with any linked cards on
    file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}
  tags: Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/square/v2customerscustomer-id-delete-openapi.md
- name: Square Connect API RetrieveCustomer
  x-api-slug: square-connect-api
  description: Returns details for a single customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}
  tags: RetrieveCustomer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/square/v2customerscustomer-id-get-openapi.md
- name: Square Connect API UpdateCustomer
  x-api-slug: square-connect-api
  description: |-
    Updates the details of an existing customer.
    The ID of the customer may change if the customer has been merged into another customer.

    You cannot edit a customer's cards on file with this endpoint. To make changes
    to a card on file, you must delete the existing card on file with the
    [DeleteCustomerCard](#endpoint-deletecustomercard) endpoint, then create a new one with the
    [CreateCustomerCard](#endpoint-createcustomercard) endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}
  tags: Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/square/v2customerscustomer-id-put-openapi.md
- name: Square Connect API CreateCustomerCard
  x-api-slug: square-connect-api
  description: |-
    Adds a card on file to an existing customer. In the United States
    Square takes care of automatically updating any cards on file that might
    have expired since you first attached them to a customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}/cards
  tags: CreateCustomerCard
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/square/v2customerscustomer-idcards-post-openapi.md
- name: Square Connect API DeleteCustomerCard
  x-api-slug: square-connect-api
  description: Removes a card on file from a customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}/cards/{card_id}
  tags: CustomerCard
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/square/v2customerscustomer-idcardscard-id-delete-openapi.md
- name: Square Connect API
  x-api-slug: square-connect-api
  description: Square helps millions of sellers run their business- from secure credit
    card processing to point of sale solutions. Get paid faster with Square and sign
    up today!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com//
  tags: Custom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/square/openapi.md
x-common:
- type: x-base
  url: https://connect.squareup.com
- type: x-crunchbase
  url: http://www.crunchbase.com/company/square
- type: x-crunchbase
  url: https://crunchbase.com/organization/square
- type: x-developer
  url: https://connect.squareup.com/
- type: x-email
  url: press@squareup.com
- type: x-email
  url: security@squareup.com
- type: x-email
  url: lawenforcement@squareup.com
- type: x-email
  url: redemption@squareup.com
- type: x-email
  url: privacy@squareup.com
- type: x-email
  url: community@squareup.com
- type: x-email
  url: noreply@messaging.squareup.com
- type: x-email
  url: ir@squareup.com
- type: x-email
  url: takedowns@squareup.com
- type: x-github
  url: https://github.com/square
- type: x-twitter
  url: https://twitter.com/Square
- type: x-website
  url: http://squareup.com
- type: x-website
  url: https://squareup.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---