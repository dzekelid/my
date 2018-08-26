{
  "info": {
    "name": "reverb Get My Orders Selling Buyer History Buyer",
    "_postman_id": "ad094653-8d3b-4326-bce3-514bbf5c3e54",
    "description": "Get my orders selling buyer history buyer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "d2a2c3de-bad8-4e32-813c-511d3263f0fb",
          "name": "getMyOrdersSellingBuyerHistoryBuyer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/orders/selling/buyer_history/:buyer_id"
              ],
              "variable": [
                {
                  "id": "buyer_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get my orders selling buyer history buyer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b2929dd-f5c9-4daf-860a-0bdf9c987242"
            }
          ]
        }
      ]
    }
  ]
}