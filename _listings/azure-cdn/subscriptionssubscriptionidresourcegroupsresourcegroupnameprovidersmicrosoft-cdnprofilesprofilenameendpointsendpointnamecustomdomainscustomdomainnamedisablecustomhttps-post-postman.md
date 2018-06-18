{
  "info": {
    "name": "Azure CDN API Custom Domains Disable Custom Https",
    "_postman_id": "6076fc66-55a9-441c-9e11-3cd91b316179",
    "description": "Disable https delivery of the custom domain.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "cdn",
      "item": [
        {
          "id": "533a7e83-c82e-4f96-abe2-97fc1d6261c9",
          "name": "CustomDomains_DisableCustomHttps",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Cdn/profiles/:profileName/endpoints/:endpointName/customDomains/:customDomainName/disableCustomHttps"
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
            "description": "Disable https delivery of the custom domain"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b491a508-0f31-46da-9d49-389de2813f11"
            }
          ]
        }
      ]
    }
  ]
}