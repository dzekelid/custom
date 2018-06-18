{
  "info": {
    "name": "Sales Force Desk API Update Customer Phone",
    "_postman_id": "938f985b-13ec-492e-b68e-70196f665ca9",
    "description": "Update customer phone.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Customers",
      "item": [
        {
          "id": "6de2cf64-34aa-4e94-a71a-56facec39c23",
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
              "id": "5d72e4d0-6492-4d60-b981-b0af06cc4387"
            }
          ]
        },
        {
          "id": "6045b4ec-373a-410a-902c-97c95a1dafe3",
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
              "id": "0cab932c-926d-4758-ac66-9051ead57f32"
            }
          ]
        },
        {
          "id": "1f8de557-239c-4bcd-9b04-c972b9ef8aaf",
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
              "id": "bde71b31-1225-4bd0-b7c1-70090efd2ebe"
            }
          ]
        },
        {
          "id": "9159f012-7305-4d3f-a331-778709566d4b",
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
              "id": "4bbffd72-ba2d-4ae0-b163-1f098603da1a"
            }
          ]
        },
        {
          "id": "31c11b19-647b-4628-a8b8-c84f3105d14b",
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
              "id": "727054f8-cedb-4250-91b2-b20beff56f99"
            }
          ]
        },
        {
          "id": "592020c2-e59e-4112-b9bc-b14355a40666",
          "name": "update-customer-phone",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:customer_id/phones/:id.json"
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
            "description": "Update customer phone."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2acab69-fc87-4c98-bdd8-4ab3fd6d74d5"
            }
          ]
        }
      ]
    }
  ]
}