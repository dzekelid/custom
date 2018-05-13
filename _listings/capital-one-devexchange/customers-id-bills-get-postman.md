{
  "info": {
    "name": "Capital One DevExchange Get bills by customer id",
    "_postman_id": "bdc20bd3-9192-4a7f-a8bc-65a2355bab61",
    "description": "Returns the bills associated with the specific customer",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "08f444cf-9fa9-45e7-af5e-a82f9b4d1d8e",
          "name": "returns-the-bills-associated-with-the-specific-customer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reimaginebanking.com",
              "path": [
                "customers/:id/bills"
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
            "description": "Returns the bills associated with the specific customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc1d5f01-1e85-428c-bb5f-5934084acb34"
            }
          ]
        }
      ]
    }
  ]
}