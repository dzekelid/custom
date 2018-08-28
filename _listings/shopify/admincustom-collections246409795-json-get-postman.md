{
  "info": {
    "name": "Shopify Get a single custom collections",
    "_postman_id": "047e6e1b-95b1-478b-a0cf-d9a9ca5ec07a",
    "description": "Get a single custom collections.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "7679dc48-0811-4972-b287-e39635263dfd",
          "name": "getAdminCustomCollections.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/custom_collections.json",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all custom collections."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a333b6c9-faf7-41bb-a9bb-c4b19835e28d"
            }
          ]
        },
        {
          "id": "39376dbf-75d4-4e54-862b-717a46d4c48b",
          "name": "getAdminCustomCollections246409795.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/custom_collections/246409795.json",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a single custom collections."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aae36331-af2c-4ba7-b819-f6e051ea56ef"
            }
          ]
        }
      ]
    }
  ]
}