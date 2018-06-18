---
name: Capital One DevExchange
x-slug: capital-one-devexchange
description: What unites us all is a desire to create better end customer experiences.
  Were building a full suite of tools and technology that make essential things in
  peoples everyday life &ndash; money, finances, identity &ndash; simpler for you.
  Now is the time to join our beta program, and help us shape the future.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/capitalone-devexchange.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Custom
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/apis.md
specificationVersion: "0.14"
apis:
- name: Capital One DevExchange Create an account
  x-api-slug: capital-one-devexchange
  description: Creates an account for the customer with the id provided
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/capitalone-devexchange.png
  humanURL: http://capitalone.com
  baseURL: https://api.reimaginebanking.com////customers/{id}/accounts
  tags: Banks,Customers, , Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customersidaccounts-post-openapi.md
- name: Capital One DevExchange Get accounts by customer id
  x-api-slug: capital-one-devexchange
  description: Returns the accounts associated with the specific customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/capitalone-devexchange.png
  humanURL: http://capitalone.com
  baseURL: https://api.reimaginebanking.com////customers/{id}/accounts
  tags: Banks,Customers, , Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customersidaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customersidaccounts-get-openapi.md
- name: Capital One DevExchange Get customer that owns the specified account
  x-api-slug: capital-one-devexchange
  description: Returns the customer that the account belongs to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/capitalone-devexchange.png
  humanURL: http://capitalone.com
  baseURL: https://api.reimaginebanking.com////accounts/{id}/customer
  tags: Banks,Accounts, , Customer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/accountsidcustomer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/accountsidcustomer-get-openapi.md
- name: Capital One DevExchange Get all customers
  x-api-slug: capital-one-devexchange
  description: Returns the customers that have been assigned to you.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/capitalone-devexchange.png
  humanURL: http://capitalone.com
  baseURL: https://api.reimaginebanking.com////customers
  tags: Banks,Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customers-get-openapi.md
- name: Capital One DevExchange Create a customer
  x-api-slug: capital-one-devexchange
  description: Creates a customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/capitalone-devexchange.png
  humanURL: http://capitalone.com
  baseURL: https://api.reimaginebanking.com////customers
  tags: Banks,Customers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customers-post-openapi.md
- name: Capital One DevExchange Get customer by id
  x-api-slug: capital-one-devexchange
  description: Returns the customer with the specific id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/capitalone-devexchange.png
  humanURL: http://capitalone.com
  baseURL: https://api.reimaginebanking.com////customers/{id}
  tags: Banks,Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customersid-get-openapi.md
- name: Capital One DevExchange Update a specific existing customer
  x-api-slug: capital-one-devexchange
  description: Updates the specific customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/capitalone-devexchange.png
  humanURL: http://capitalone.com
  baseURL: https://api.reimaginebanking.com////customers/{id}
  tags: Banks,Customers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customersid-put-openapi.md
- name: Capital One DevExchange Get bills by customer id
  x-api-slug: capital-one-devexchange
  description: Returns the bills associated with the specific customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/capitalone-devexchange.png
  humanURL: http://capitalone.com
  baseURL: https://api.reimaginebanking.com////customers/{id}/bills
  tags: Banks,Customers, , Bills
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customersidbills-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/customersidbills-get-openapi.md
- name: Capital One DevExchange
  x-api-slug: capital-one-devexchange
  description: What unites us all is a desire to create better end customer experiences.
    Were building a full suite of tools and technology that make essential things
    in peoples everyday life &ndash; money, finances, identity &ndash; simpler for
    you. Now is the time to join our beta program, and help us shape the future.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/capitalone-devexchange.png
  humanURL: http://capitalone.com
  baseURL: https://api.reimaginebanking.com//
  tags: Custom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/capital-one-devexchange/openapi.md
x-common:
- type: x-authentication
  url: https://developer.capitalone.com/platform-documentation/authorization-with-oauth-20/
- type: x-blog
  url: https://developer.capitalone.com/blogs/
- type: x-developer
  url: https://developer.capitalone.com/
- type: x-documentation
  url: https://developer.capitalone.com/platform-documentation/
- type: x-errors
  url: https://developer.capitalone.com/platform-documentation/errors/
- type: x-getting-started
  url: https://developer.capitalone.com/platform-documentation/getting-started/
- type: x-github
  url: https://github.com/capitalone
- type: x-website
  url: http://capitalone.com
- type: x-open-source
  url: https://developer.capitalone.com/open-source/
- type: x-sandbox
  url: https://developer.capitalone.com/platform-documentation/using-the-sandbox/
- type: x-login
  url: https://developer.capitalone.com/sign-in/
- type: x-selfservice-registration
  url: https://developer.capitalone.com/sign-up
- type: x-support
  url: https://developer.capitalone.com/support/
- type: x-privacy-policy
  url: https://www.capitalone.com/identity-protection/privacy/statement
- type: x-terms-of-service
  url: https://developer.capitalone.com/single/terms-and-conditions/
- type: x-twitter
  url: https://twitter.com/CapitalOneDevEx
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---