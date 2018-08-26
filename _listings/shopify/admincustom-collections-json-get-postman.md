{
  "info": {
    "name": "Shopify Get a list of all custom collections",
    "_postman_id": "9cb7e73a-606a-48d3-98e7-3497cc08ec05",
    "description": "Get a list of all custom collections.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "8157d565-8a34-4a0f-b145-6af4a20676b5",
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
              "id": "9e81a17d-3a19-4d60-83cd-912472fd4466"
            }
          ]
        }
      ]
    }
  ]
}