{
  "info": {
    "name": "Stripe Get Customers Customer Bank Accounts",
    "_postman_id": "b48845bb-d826-48ed-b3bc-4b5b48c9ec87",
    "description": "You can see a list of the bank accounts belonging to a Customer. Note that the 10 most recent sources are always available by default on the Customer. If you need more than those 10, you can use this API method and the limit and starting_after parameters to page through additional bank accounts.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "customers",
      "item": [
        {
          "id": "9663731d-aad8-45e9-8028-805e78a59797",
          "name": "getCustomersCustomerBankAccounts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "customers/:customer/bank_accounts"
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
            "description": "You can see a list of the bank accounts belonging to a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b0e0c8b-b456-4876-a4fb-31ceadceffb5"
            }
          ]
        }
      ]
    }
  ]
}