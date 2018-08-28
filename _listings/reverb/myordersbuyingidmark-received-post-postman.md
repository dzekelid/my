{
  "info": {
    "name": "reverb Post My Orders Buying Mark Received",
    "_postman_id": "2bce0ff3-64a6-4a09-bc72-5f83b3662655",
    "description": "Marks an order as received by the buyer",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "ab03f592-d0c9-4777-9d3f-df3b6956291d",
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
              "id": "a30947cc-d041-4c21-b245-c47d462d4730"
            }
          ]
        },
        {
          "id": "5bb1f420-6195-4755-9ec3-427a10c88a78",
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
              "id": "e2adee7b-404b-42a5-81a4-14abb171fefb"
            }
          ]
        },
        {
          "id": "5ac97ab8-2e4c-441f-84c4-040dda2a5e30",
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
              "id": "44adf584-abaa-4de1-b0cb-5be9193fbc05"
            }
          ]
        },
        {
          "id": "13b1ad85-09d5-4dfb-a2d1-a1985f0cca54",
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
              "id": "2fb81808-7cf8-49a8-a543-d944ce8cb6ce"
            }
          ]
        },
        {
          "id": "c2b33990-119c-4593-9fe2-b536dac02e8e",
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
              "id": "c1d4fa9f-0942-491e-89cb-09ba41d2b5ae"
            }
          ]
        }
      ]
    }
  ]
}