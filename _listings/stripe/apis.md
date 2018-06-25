---
name: Stripe
x-slug: stripe
description: Online payment processing for internet businesses. Stripe is a suite
  of payment APIs that powers commerce for online businesses of all sizes, including
  fraud prevention, and subscription management. Use Stripes payment platform to accept
  and process p...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
x-kinRank: "10"
x-alexaRank: "1914"
tags: Custom
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/apis.md
specificationVersion: "0.14"
apis:
- name: Stripe Get Customers
  x-api-slug: stripe
  description: Returns a list of your customers. The customers are returned sorted
    by creation date, with the most recent customers appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers
  tags: Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customers-get-openapi.md
- name: Stripe Add Customers
  x-api-slug: stripe
  description: Creates a new customer object.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers
  tags: Customers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customers-post-openapi.md
- name: Stripe Delete Customers Customer
  x-api-slug: stripe
  description: Permanently deletes a customer. It cannot be undone. Also immediately
    cancels any active subscriptions on the customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}
  tags: Customers, Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomer-delete-openapi.md
- name: Stripe Get Customers Customer
  x-api-slug: stripe
  description: Retrieves the details of an existing customer. You need only supply
    the unique customer identifier that was returned upon customer creation.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}
  tags: Customers, Customer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomer-get-openapi.md
- name: Stripe Add Customers Customer
  x-api-slug: stripe
  description: Post Customers, Customer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}
  tags: Customers, Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomer-post-openapi.md
- name: Stripe Get Customers Customer Bank Accounts
  x-api-slug: stripe
  description: You can see a list of the bank accounts belonging to a Customer. Note
    that the 10 most recent sources are always available by default on the Customer.
    If you need more than those 10, you can use this API method and the limit and
    starting_after parameters to page through additional bank accounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts
  tags: Customers, Customer, Bank, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerbank-accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerbank-accounts-get-openapi.md
- name: Stripe Add Customers Customer Bank Accounts
  x-api-slug: stripe
  description: Post Customers, Customer, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts
  tags: Customers, Customer, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerbank-accounts-post-openapi.md
- name: Stripe Delete Customers Customer Bank Accounts
  x-api-slug: stripe
  description: Delete Customers, Customer, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts/{id}
  tags: Customers, Customer, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerbank-accountsid-delete-openapi.md
- name: Stripe Get Customers Customer Bank Accounts
  x-api-slug: stripe
  description: By default, you can see the 10 most recent sources stored on a Customer
    directly on the object, but you can also retrieve details about a specific bank
    account stored on the Stripe account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts/{id}
  tags: Customers, Customer, Bank, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerbank-accountsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerbank-accountsid-get-openapi.md
- name: Stripe Add Customers Customer Bank Accounts
  x-api-slug: stripe
  description: Post Customers, Customer, Bank, Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts/{id}
  tags: Customers, Customer, Bank, Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerbank-accountsid-post-openapi.md
- name: Stripe Add Customers Customer Bank Accounts  Verify
  x-api-slug: stripe
  description: Post Customers, Customer, Bank, Accounts, , Verify
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/bank_accounts/{id}/verify
  tags: Customers, Customer, Bank, Accounts, , Verify
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerbank-accountsidverify-post-openapi.md
- name: Stripe Get Customers Customer Cards
  x-api-slug: stripe
  description: Get Customers, Customer, Cards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/cards
  tags: Customers, Customer, Cards
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomercards-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomercards-get-openapi.md
- name: Stripe Add Customers Customer Cards
  x-api-slug: stripe
  description: Post Customers, Customer, Cards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/cards
  tags: Customers, Customer, Cards
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomercards-post-openapi.md
- name: Stripe Delete Customers Customer Cards
  x-api-slug: stripe
  description: Delete Customers, Customer, Cards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/cards/{id}
  tags: Customers, Customer, Cards
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomercardsid-delete-openapi.md
- name: Stripe Get Customers Customer Cards
  x-api-slug: stripe
  description: Get Customers, Customer, Cards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/cards/{id}
  tags: Customers, Customer, Cards
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomercardsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomercardsid-get-openapi.md
- name: Stripe Add Customers Customer Cards
  x-api-slug: stripe
  description: Post Customers, Customer, Cards
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/cards/{id}
  tags: Customers, Customer, Cards
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomercardsid-post-openapi.md
- name: Stripe Delete Customers Customer Discount
  x-api-slug: stripe
  description: Removes the currently applied discount on a customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/discount
  tags: Customers, Customer, Discount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerdiscount-delete-openapi.md
- name: Stripe Get Customers Customer Discount
  x-api-slug: stripe
  description: Get Customers, Customer, Discount
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/discount
  tags: Customers, Customer, Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerdiscount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomerdiscount-get-openapi.md
- name: Stripe Get Customers Customer Sources
  x-api-slug: stripe
  description: Get Customers, Customer, Sources
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources
  tags: Customers, Customer, Sources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersources-get-openapi.md
- name: Stripe Add Customers Customer Sources
  x-api-slug: stripe
  description: Post Customers, Customer, Sources
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources
  tags: Customers, Customer, Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersources-post-openapi.md
- name: Stripe Delete Customers Customer Sources
  x-api-slug: stripe
  description: Delete Customers, Customer, Sources
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources/{id}
  tags: Customers, Customer, Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersourcesid-delete-openapi.md
- name: Stripe Get Customers Customer Sources
  x-api-slug: stripe
  description: Get Customers, Customer, Sources
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources/{id}
  tags: Customers, Customer, Sources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersourcesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersourcesid-get-openapi.md
- name: Stripe Add Customers Customer Sources
  x-api-slug: stripe
  description: Post Customers, Customer, Sources
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources/{id}
  tags: Customers, Customer, Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersourcesid-post-openapi.md
- name: Stripe Add Customers Customer Sources  Verify
  x-api-slug: stripe
  description: Post Customers, Customer, Sources, , Verify
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/sources/{id}/verify
  tags: Customers, Customer, Sources, , Verify
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersourcesidverify-post-openapi.md
- name: Stripe Get Customers Customer Subscriptions
  x-api-slug: stripe
  description: "You can see a list of the customer\u2019s active subscriptions. Note
    that the 10 most recent active subscriptions are always available by default on
    the customer object. If you need more than those 10, you can use the limit and
    starting_after parameters to page through additional subscriptions."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions
  tags: Customers, Customer, Subscriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersubscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersubscriptions-get-openapi.md
- name: Stripe Add Customers Customer Subscriptions
  x-api-slug: stripe
  description: Creates a new subscription on an existing customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions
  tags: Customers, Customer, Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersubscriptions-post-openapi.md
- name: Stripe Delete Customers Customer Subscriptions Subscription Exposed
  x-api-slug: stripe
  description: "Cancels a customer\u2019s subscription. If you set the at_period_end
    parameter to true, the subscription will remain active until the end of the period,
    at which point it will be canceled and not renewed. By default, the subscription
    is terminated immediately. In either case, the customer will not be charged again
    for the subscription. Note, however, that any pending invoice items that you\u2019ve
    created will still be charged for at the end of the period unless manually deleted.
    If you\u2019ve set the subscription to cancel at period end, any pending prorations
    will also be left in place and collected at the end of the period, but if the
    subscription is set to cancel immediately, pending prorations will be removed.By
    default, all unpaid invoices for the customer will be closed upon subscription
    cancellation. We do this in order to prevent unexpected payment attempts once
    the customer has canceled a subscription. However, you can reopen the invoices
    manually after subscription cancellation to have us proceed with payment collection,
    or you could even re-attempt payment yourself on all unpaid invoices before allowing
    the customer to cancel the subscription at all."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions/{subscription_exposed_id}
  tags: Customers, Customer, Subscriptions, Subscription, Exposed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-id-delete-openapi.md
- name: Stripe Get Customers Customer Subscriptions Subscription Exposed
  x-api-slug: stripe
  description: Get Customers, Customer, Subscriptions, Subscription, Exposed
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions/{subscription_exposed_id}
  tags: Customers, Customer, Subscriptions, Subscription, Exposed
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-id-get-openapi.md
- name: Stripe Add Customers Customer Subscriptions Subscription Exposed
  x-api-slug: stripe
  description: Updates an existing subscription on a customer to match the specified
    parameters. When changing plans or quantities, we will optionally prorate the
    price we charge next month to make up for any price changes. To preview how the
    proration will be calculated, use the upcoming invoice endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions/{subscription_exposed_id}
  tags: Customers, Customer, Subscriptions, Subscription, Exposed
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-id-post-openapi.md
- name: Stripe Delete Customers Customer Subscriptions Subscription Exposed  Discount
  x-api-slug: stripe
  description: Delete Customers, Customer, Subscriptions, Subscription, Exposed, ,
    Discount
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions/{subscription_exposed_id}/discount
  tags: Customers, Customer, Subscriptions, Subscription, Exposed, , Discount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-iddiscount-delete-openapi.md
- name: Stripe Get Customers Customer Subscriptions Subscription Exposed  Discount
  x-api-slug: stripe
  description: Get Customers, Customer, Subscriptions, Subscription, Exposed, , Discount
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///customers/{customer}/subscriptions/{subscription_exposed_id}/discount
  tags: Customers, Customer, Subscriptions, Subscription, Exposed, , Discount
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-iddiscount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customerscustomersubscriptionssubscription-exposed-iddiscount-get-openapi.md
- name: Stripe
  x-api-slug: stripe
  description: Web and mobile payments, built for developers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Custom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/openapi.md
x-common:
- type: x-base
  url: https://api.stripe.com/
- type: x-blog
  url: https://stripe.com/blog
- type: x-blog-rss
  url: https://stripe.com/blog/feed.rss
- type: x-change-log
  url: https://stripe.com/docs/upgrades
- type: x-crunchbase
  url: http://www.crunchbase.com/company/stripe
- type: x-crunchbase
  url: https://crunchbase.com/organization/stripe
- type: x-email
  url: info@stripe.com
- type: x-email
  url: privacy@stripe.com
- type: x-email
  url: atlas@stripe.com
- type: x-email
  url: notices@stripe.com
- type: x-email
  url: jane.diaz@stripe.com
- type: x-email
  url: nonprofit@stripe.com
- type: x-email
  url: support@stripe.com
- type: x-email
  url: dpo@stripe.com
- type: x-github
  url: https://github.com/stripe
- type: x-linkedin
  url: https://www.linkedin.com/company/stripe/
- type: x-pricing
  url: https://stripe.com/us/pricing
- type: x-twitter
  url: https://twitter.com/stripe
- type: x-website
  url: https://stripe.com/
- type: x-website
  url: http://stripe.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---