{
  "info": {
    "name": "Jumpseller Get Checkout Custom Fields",
    "_postman_id": "4bf46653-9da3-403b-b68a-90341917934c",
    "description": "Retrieve all checkout custom fields..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Checkout",
      "item": [
        {
          "id": "7d53f926-ef44-4eea-a25b-f22d23ea24eb",
          "name": "getCheckoutCustomFields.json",
          "request": {
            "url": "http://api.jumpseller.com/v1/checkout_custom_fields.json?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve all checkout custom fields.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f75708a-2702-444b-962c-f343a64744a8"
            }
          ]
        }
      ]
    }
  ]
}