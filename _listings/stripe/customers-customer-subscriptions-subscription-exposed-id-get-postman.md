{
  "info": {
    "name": "Stripe Get Customers Customer Subscriptions Subscription Exposed",
    "_postman_id": "d4ba6cfb-06ab-427f-8f27-00706a01d962",
    "description": "Get Customers, Customer, Subscriptions, Subscription, Exposed",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "customers",
      "item": [
        {
          "id": "b198f3d4-49b5-4894-bd1f-6cceaeb84343",
          "name": "getCustomersCustomerSubscriptionsSubscriptionExposed",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "customers/:customer/subscriptions/:subscription_exposed_id"
              ],
              "query": [
                {
                  "key": "expand",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "customer",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscription_exposed_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Customers, Customer, Subscriptions, Subscription, Exposed"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc339830-268e-4c8f-80b9-87a9585e1098"
            }
          ]
        }
      ]
    }
  ]
}