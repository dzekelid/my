{
  "info": {
    "name": "reverb Get My Orders Buying Buying History Seller",
    "_postman_id": "e840e3fc-4499-4ec2-8b9d-dc69235ef58d",
    "description": "Get my orders buying buying history seller.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "f3d86d6a-92e8-4ecf-a6fb-1992e7582957",
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
              "id": "57f9e0ca-0f82-4e29-914a-dc0d5b39f710"
            }
          ]
        },
        {
          "id": "f5d63fc8-e635-4a6e-812b-87572e4dcc0b",
          "name": "getMyOrdersBuyingBuyingHistorySeller",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/orders/buying/buying_history/:seller_id"
              ],
              "variable": [
                {
                  "id": "seller_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get my orders buying buying history seller."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b082e8be-565a-491c-8156-dbbe224fb9c4"
            }
          ]
        }
      ]
    }
  ]
}