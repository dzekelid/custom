{
  "info": {
    "name": "Sales Force Desk API Update Customer",
    "_postman_id": "5ec7cd2d-cf7a-42bf-969c-7351135024f8",
    "description": "Update customer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Customers",
      "item": [
        {
          "id": "8bb7625b-3433-4ae9-8f0b-54bebf934b89",
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
              "id": "e5f91e2b-ef44-4101-81c0-4999913d6d05"
            }
          ]
        },
        {
          "id": "1208081e-421a-40d0-983b-bdabb627efa0",
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
              "id": "e36e060e-260c-408a-9e55-08c9c3f5b92c"
            }
          ]
        },
        {
          "id": "d253746e-b51a-48c6-a173-1b541875a355",
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
              "id": "4f84b3bd-42d8-438f-8d73-0ae085140923"
            }
          ]
        },
        {
          "id": "19b01c7f-e139-40f9-90d4-c02d2ab307ed",
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
              "id": "fe8733be-dc41-40ce-9878-a54b030fe277"
            }
          ]
        },
        {
          "id": "6b96989b-ae61-4148-970a-d48494ec7ddf",
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
              "id": "a9490519-f098-456c-8448-2df3ad8b027c"
            }
          ]
        },
        {
          "id": "6c76cf04-74cc-4c15-892c-8ddf26ee9bd9",
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
              "id": "8270cad8-b52d-4eed-bb46-688bcf0438f2"
            }
          ]
        },
        {
          "id": "15871425-9f83-49f4-8163-e240aaa03406",
          "name": "get-customer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:id.json"
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
            "description": "Get customer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "230b0815-e855-4a32-a0bb-c5912a8ed395"
            }
          ]
        },
        {
          "id": "66e2e729-ee7d-4fa1-801e-49cc2e3149e0",
          "name": "update-customer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "customers/:id.json"
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
            "description": "Update customer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a6e2bc1-c8b9-4e57-b68a-8f4ed9ed20d8"
            }
          ]
        }
      ]
    }
  ]
}