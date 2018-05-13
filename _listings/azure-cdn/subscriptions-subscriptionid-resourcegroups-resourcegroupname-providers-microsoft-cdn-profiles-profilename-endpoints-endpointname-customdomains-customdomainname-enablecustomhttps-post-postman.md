{
  "info": {
    "name": "Azure CDN API Custom Domains Enable Custom Https",
    "_postman_id": "471d459c-6bb6-49f3-bb78-47a0387af571",
    "description": "Enable https delivery of the custom domain.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cdn",
      "item": [
        {
          "id": "1a5ed9e2-094a-42f8-82c0-731565d57846",
          "name": "CustomDomains_EnableCustomHttps",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Cdn/profiles/:profileName/endpoints/:endpointName/customDomains/:customDomainName/enableCustomHttps"
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Enable https delivery of the custom domain"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b18336f1-4339-4863-ac1d-90f2d75e9089"
            }
          ]
        }
      ]
    }
  ]
}