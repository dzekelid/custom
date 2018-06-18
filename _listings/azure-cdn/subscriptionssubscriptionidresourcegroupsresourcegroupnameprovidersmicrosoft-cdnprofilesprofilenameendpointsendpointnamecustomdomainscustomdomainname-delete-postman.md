{
  "info": {
    "name": "Azure CDN API Custom Domains Delete",
    "_postman_id": "776a10c4-ab3f-4f78-8f4d-b340d3c96515",
    "description": "Deletes an existing custom domain within an endpoint.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cdn",
      "item": [
        {
          "id": "8a1046eb-c823-49e5-a854-f6c305f1c7e2",
          "name": "CustomDomains_Delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Cdn/profiles/:profileName/endpoints/:endpointName/customDomains/:customDomainName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "customDomainName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "endpointName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "profileName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an existing custom domain within an endpoint"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba6cd1f0-c795-42a8-8d8d-61e9b712c48e"
            }
          ]
        }
      ]
    }
  ]
}