{
  "info": {
    "name": "Stripe Get Customers Customer Discount",
    "_postman_id": "4e36eb82-888d-4595-84ed-01f5cbad1e98",
    "description": "Get Customers, Customer, Discount",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "customers",
      "item": [
        {
          "id": "5794d3d7-da68-498d-9d5f-2fb43eb8c2a3",
          "name": "getCustomersCustomerDiscount",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "customers/:customer/discount"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Customers, Customer, Discount"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bfacf0f7-53a3-4dda-8060-6718f5d4c8d8"
            }
          ]
        }
      ]
    }
  ]
}