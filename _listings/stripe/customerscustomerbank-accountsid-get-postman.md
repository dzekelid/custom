{
  "info": {
    "name": "Stripe Get Customers Customer Bank Accounts",
    "_postman_id": "a031ae97-c1ce-4000-9513-e12f2c86c93c",
    "description": "By default, you can see the 10 most recent sources stored on a Customer directly on the object, but you can also retrieve details about a specific bank account stored on the Stripe account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "customers",
      "item": [
        {
          "id": "9ee34247-f3b4-4828-8691-b3a688f33217",
          "name": "getCustomersCustomerBankAccounts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "customers/:customer/bank_accounts/:id"
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
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "By default, you can see the 10 most recent sources stored on a Customer directly on the object, but you can also retrieve details about a specific bank account stored on the Stripe account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a42ef956-88e0-451e-9281-58e63fcd15e5"
            }
          ]
        }
      ]
    }
  ]
}