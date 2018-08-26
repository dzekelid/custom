{
  "info": {
    "name": "Capital One DevExchange Get all customers",
    "_postman_id": "a0034c1b-40b8-4fb5-960c-fa802190f961",
    "description": "Returns the customers that have been assigned to you.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "banks",
      "item": [
        {
          "id": "d2760f5a-b3c9-4ea1-b93e-1519afee0d8b",
          "name": "returns-the-customers-that-have-been-assigned-to-you",
          "request": {
            "url": "http://api.reimaginebanking.com/customers",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the customers that have been assigned to you"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "778c4223-31ee-49e3-b9f7-66aa669c77e8"
            }
          ]
        }
      ]
    }
  ]
}