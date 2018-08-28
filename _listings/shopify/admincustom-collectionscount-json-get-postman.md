{
  "info": {
    "name": "Shopify Get a count of all custom collections",
    "_postman_id": "aa374486-51d8-427a-8537-2e26261a16cd",
    "description": "Get a count of all custom collections.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "38cb6c22-6e55-4305-aaa4-c1e9e1317943",
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
              "id": "af924a7f-bd54-47ff-91c1-2626b9aa1238"
            }
          ]
        },
        {
          "id": "b2b43e01-ab4a-4dce-8366-7fa22cbe9a62",
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
              "id": "ffc35c8a-9f67-4bcc-ab13-6ddf71005661"
            }
          ]
        },
        {
          "id": "a0708676-7e39-4d69-b25b-d5e530ea9ff8",
          "name": "getAdminSmartCollectionsCount.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/smart_collections/count.json",
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
            "description": "Get a count of all collections."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5102106e-3ee8-47fc-a2d8-08ecbca748ed"
            }
          ]
        },
        {
          "id": "c9f1060f-25bd-4b82-aaf3-9db3d17d8100",
          "name": "getAdminCustomCollectionsCount.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/custom_collections/count.json",
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
            "description": "Get a count of all custom collections."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36881e72-5a20-4144-bf60-87882e893c95"
            }
          ]
        }
      ]
    }
  ]
}