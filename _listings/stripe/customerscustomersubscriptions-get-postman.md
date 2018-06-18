{
  "info": {
    "name": "Stripe Get Customers Customer Subscriptions",
    "_postman_id": "7e55db9d-94b6-4c66-a0ae-695220a9b01f",
    "description": "You can see a list of the customer’s active subscriptions. Note that the 10 most recent active subscriptions are always available by default on the customer object. If you need more than those 10, you can use the limit and starting_after parameters to page through additional subscriptions.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "customers",
      "item": [
        {
          "id": "1e67df55-6e06-429d-88fd-8e49639a36f5",
          "name": "getCustomersCustomerSubscriptions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "customers/:customer/subscriptions"
              ],
              "query": [
                {
                  "key": "ending_before",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "expand",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "starting_after",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "customer",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "You can see a list of the customer’s active subscriptions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c2a80c8-16f1-4ca8-b347-5b9acba9aa5c"
            }
          ]
        }
      ]
    }
  ]
}