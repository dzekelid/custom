{
  "info": {
    "name": "Capital One DevExchange Get accounts by customer id",
    "_postman_id": "8e033c64-2774-40c2-aaf5-4fc0d0627a1d",
    "description": "Returns the accounts associated with the specific customer",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "92a74e67-9a2b-45ab-9253-f0e84ef2aa44",
          "name": "returns-the-accounts-associated-with-the-specific-customer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reimaginebanking.com",
              "path": [
                "customers/:id/accounts"
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
            "description": "Returns the accounts associated with the specific customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f318183d-38e0-420b-b5e9-b06cd2ea4ca4"
            }
          ]
        }
      ]
    }
  ]
}