{
  "info": {
    "name": "Sales Force Desk API Create Customer",
    "_postman_id": "d0a2422f-9225-48c3-bb1c-159149bdd612",
    "description": "Create customer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Customers",
      "item": [
        {
          "id": "4f94d1fa-12f5-43b1-ada0-40d12d17847f",
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
              "id": "0a800945-8844-4ace-b614-4de98f817f12"
            }
          ]
        },
        {
          "id": "b672b85b-5d70-42e6-96a9-dff45bbf6924",
          "name": "create-customer",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/customers.json?format=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create customer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ac35544-3d3f-44c3-b1aa-aea227b6d4af"
            }
          ]
        }
      ]
    }
  ]
}