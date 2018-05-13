{
  "info": {
    "name": "Capital One DevExchange Get customer by id",
    "_postman_id": "4b2625dd-da56-4d2f-9b53-da48458beb4b",
    "description": "Returns the customer with the specific id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "6ee137c4-160a-48f5-add6-edd8508e6ae9",
          "name": "returns-the-customer-with-the-specific-id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reimaginebanking.com",
              "path": [
                "customers/:id"
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
            "description": "Returns the customer with the specific id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59c2df96-9259-40c3-a709-0fdae745ec08"
            }
          ]
        }
      ]
    }
  ]
}