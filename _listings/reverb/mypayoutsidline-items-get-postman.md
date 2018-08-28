{
  "info": {
    "name": "reverb Get My Payouts Line Items",
    "_postman_id": "9e6bd93f-2728-4ba2-884e-477773131f94",
    "description": "Read the line items of a payout",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "e3b3dca4-e806-4ac5-bda5-49e1be84e436",
          "name": "getMyPayoutsLineItems",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/payouts/:id/line_items"
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
            "description": "Read the line items of a payout"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23f5488b-53d7-420e-a167-8202878a0ea9"
            }
          ]
        }
      ]
    }
  ]
}