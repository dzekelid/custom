{
  "info": {
    "name": "Stripe Get Customers Customer Subscriptions Subscription Exposed  Discount",
    "_postman_id": "8a955a55-e566-4565-bede-afed0038e02e",
    "description": "Get Customers, Customer, Subscriptions, Subscription, Exposed, , Discount",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "customers",
      "item": [
        {
          "id": "1bd1ca57-92c0-4aa3-934e-bb2bafe5989e",
          "name": "getCustomersCustomerSubscriptionsSubscriptionExposedDiscount",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "customers/:customer/subscriptions/:subscription_exposed_id/discount"
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
            "description": "Get Customers, Customer, Subscriptions, Subscription, Exposed, , Discount"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8487d392-30af-465e-a3f7-5c2f0ebe4dff"
            }
          ]
        }
      ]
    }
  ]
}