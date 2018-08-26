{
  "info": {
    "name": "Capital One DevExchange Get customer that owns the specified account",
    "_postman_id": "3222208d-134e-49dd-b557-4306d390c624",
    "description": "Returns the customer that the account belongs to.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "0a9ecd33-80b6-49e1-b49f-ca9d7e682e5c",
          "name": "returns-the-customer-that-the-account-belongs-to",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reimaginebanking.com",
              "path": [
                "accounts/:id/customer"
              ],
              "variable": [
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
            "description": "Returns the customer that the account belongs to"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce8d4617-2d7c-424d-8564-11cc95645b69"
            }
          ]
        }
      ]
    }
  ]
}