{
  "info": {
    "name": "Sales Force Desk API Create Customer Phone",
    "_postman_id": "42dd9bd0-8098-4022-b58a-7319b93d59d0",
    "description": "Create customer phone.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Customers",
      "item": [
        {
          "id": "1e564673-8b18-41b5-a0e2-af099816e958",
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
              "id": "343d3dc7-f8b1-4713-b0fd-5d4ff254cc51"
            }
          ]
        },
        {
          "id": "5bdce9fb-acf8-4028-854e-64e6a97354fd",
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
              "id": "40e52071-9e4a-4064-9179-996db9d5ffc1"
            }
          ]
        },
        {
          "id": "35adac93-5644-416d-b700-b9ea40be1ff8",
          "name": "create-customer-email",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:customer_id/emails.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "customer_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create customer email."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ed2969c-208c-4d2b-8f8c-a2ff99391ad7"
            }
          ]
        },
        {
          "id": "37fa6359-2111-4df6-8de3-97e4b75086ad",
          "name": "update-customer-email",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:customer_id/emails/:id.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "customer_id",
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
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update customer email."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12708f1d-3ce4-4eb9-a152-97a78575b31c"
            }
          ]
        },
        {
          "id": "ee43a66d-d866-4b08-b721-4326b6a0d17a",
          "name": "create-customer-phone",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:customer_id/phones.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "customer_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create customer phone."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39204801-4ba6-438e-aa78-a25fd0484d44"
            }
          ]
        }
      ]
    }
  ]
}