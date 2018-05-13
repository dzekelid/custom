---
name: Stripe
description: 'Stripe is a simple, developer-friendly way to accept payments online.
  They believe that enabling transactions on the web is a problem rooted in code,
  not finance, and they want to help put more websites in business. '
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stripe Stack
- Stack Network
- Stack
- Payments
- Payments
- Payment API
- Invoicing
- Imports
- Finance
- Change Log Example
- Change Log
- Billing
- API LIfeycle
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/apis.yaml
specificationVersion: "0.14"
apis:
- name: Stripe
  description: Stripe is a simple, developer-friendly way to accept payments online
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: ""
  baseURL: https://api.stripe.com/v1/
  tags: Custom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customers-customer-subscriptions-subscription-exposed-id-discount-get.md
- name: Stripe Delete Customers Customer Subscriptions Subscription Exposed
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Custom
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/custom/master/_listings/stripe/customers-customer-subscriptions-subscription-exposed-id-delete.md
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
- type: x-github
  url: https://github.com/stripe
- type: x-pricing
  url: https://stripe.com/us/pricing
- type: x-twitter
  url: https://twitter.com/stripe
- type: x-website
  url: https://stripe.com/
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
- type: x-github
  url: https://github.com/stripe
- type: x-pricing
  url: https://stripe.com/us/pricing
- type: x-twitter
  url: https://twitter.com/stripe
- type: x-website
  url: https://stripe.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---