{
  "info": {
    "name": "Sales Force Desk API Get Customers",
    "_postman_id": "469b542f-d5ac-49ba-b0ab-39b528a6f64a",
    "description": "Get customers.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Customers",
      "item": [
        {
          "id": "25172b7b-50f3-4384-8858-bcf5a82830da",
          "name": "get-customers",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/customers.json?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get customers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b0410c0-d954-452e-a31d-7973bcfc5efc"
            }
          ]
        }
      ]
    }
  ]
}