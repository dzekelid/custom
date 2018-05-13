{
  "info": {
    "name": "Stripe Get Customers Customer",
    "_postman_id": "a775a2fc-b48a-49df-bed4-be817ee2a67c",
    "description": "Retrieves the details of an existing customer. You need only supply the unique customer identifier that was returned upon customer creation.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "customers",
      "item": [
        {
          "id": "c4178180-25a9-482c-b816-c4d63c28b1d9",
          "name": "getCustomersCustomer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "customers/:customer"
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
            "description": "Retrieves the details of an existing customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c384ad11-cf3a-4fef-9398-44e82fb7fb3d"
            }
          ]
        }
      ]
    }
  ]
}