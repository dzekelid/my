{
  "info": {
    "name": "reverb Get My Orders Selling Unpa",
    "_postman_id": "ae8f3da4-f9c3-49a4-9640-68a105260fa9",
    "description": "Get unpaid seller orders, newest first.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "c60c338f-4e13-49d9-8519-91cad0b51c56",
          "name": "getMyOrdersAwaitingFeedback",
          "request": {
            "url": "http://api.reverb.com/api/my/orders/awaiting_feedback",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List of orders that need feedback"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f555ab4-ad7a-4114-b817-cc4609405e2b"
            }
          ]
        },
        {
          "id": "01e888cd-bfb6-4354-a949-71150f241e4e",
          "name": "getMyOrdersBuyingAll",
          "request": {
            "url": "http://api.reverb.com/api/my/orders/buying/all",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all orders, newest first."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cef4e35b-84b9-4949-804c-7ce715d28302"
            }
          ]
        },
        {
          "id": "4698ca11-7c6f-47b5-926c-b683691387d0",
          "name": "getMyOrdersBuyingUnpa",
          "request": {
            "url": "http://api.reverb.com/api/my/orders/buying/unpaid",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns unpaid orders, newest first."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9dedf419-d520-4a3c-8a8b-ad097b7bec33"
            }
          ]
        },
        {
          "id": "45423cd6-a12c-40ca-a7c9-ccfe0e86ef80",
          "name": "getMyOrdersBuying",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/orders/buying/:id"
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
            "description": "Returns order details for a buyer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4809fe78-c9ea-44e5-b4ae-648321305182"
            }
          ]
        },
        {
          "id": "ac776f4b-3dd7-4d00-a805-45aea5483702",
          "name": "postMyOrdersBuyingMarkReceived",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/orders/buying/:id/mark_received"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Marks an order as received by the buyer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2df5f8c6-1ee2-4a8a-9e7c-4a0e4f533f44"
            }
          ]
        },
        {
          "id": "af3d8148-d427-4fba-ad40-e362ab51adf7",
          "name": "getMyOrdersSellingAll",
          "request": {
            "url": "http://api.reverb.com/api/my/orders/selling/all?created_end_date=%7B%7D&created_start_date=%7B%7D&offset=%7B%7D&page=%7B%7D&per_page=%7B%7D&updated_end_date=%7B%7D&updated_start_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get all seller orders, newest first."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3556e034-08be-4867-bbad-f2542efd85bf"
            }
          ]
        },
        {
          "id": "205b060d-d0bf-407d-8133-6a9615887ee5",
          "name": "getMyOrdersSellingAwaitingShipment",
          "request": {
            "url": "http://api.reverb.com/api/my/orders/selling/awaiting_shipment?created_end_date=%7B%7D&created_start_date=%7B%7D&offset=%7B%7D&page=%7B%7D&per_page=%7B%7D&updated_end_date=%7B%7D&updated_start_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get seller orders awaiting shipment, newest first."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b219cfa0-a9b2-4059-a12a-a7d4f08c3a38"
            }
          ]
        },
        {
          "id": "41e819de-673f-40bb-b8c3-69ccb3200b22",
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
              "id": "578290d5-ddfa-4d30-af07-f0e07ee8dfab"
            }
          ]
        },
        {
          "id": "02ec421f-03cb-4c34-b885-2c84d38fb1a9",
          "name": "getMyOrdersSellingUnpa",
          "request": {
            "url": "http://api.reverb.com/api/my/orders/selling/unpaid?created_end_date=%7B%7D&created_start_date=%7B%7D&offset=%7B%7D&page=%7B%7D&per_page=%7B%7D&updated_end_date=%7B%7D&updated_start_date=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get unpaid seller orders, newest first."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e20243bc-0838-4104-8594-808cfa58b1a4"
            }
          ]
        }
      ]
    }
  ]
}