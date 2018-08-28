{
  "info": {
    "name": "reverb Get My Orders Selling",
    "_postman_id": "c21a947d-c7e9-4b0b-b7c2-07583e8eb1c7",
    "description": "Returns order details for a seller",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "6fbfc6c9-5b73-4089-8528-c89f61250462",
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
              "id": "f12841c4-673d-4203-beda-0dcb9bf88b14"
            }
          ]
        },
        {
          "id": "a15325de-ec0a-4d76-afbf-4ae681ea9741",
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
              "id": "fc6a0847-8fd6-4263-ac72-76969f10f083"
            }
          ]
        },
        {
          "id": "cfcd618e-c13d-4236-9c4f-ee22dab43271",
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
              "id": "402f2fd1-7f9d-449d-93d9-728447c0f971"
            }
          ]
        },
        {
          "id": "4ef9ef38-374c-4d98-b1ff-f2531c303d13",
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
              "id": "a279f7ce-210e-43ff-8973-5c4f2ab79ef8"
            }
          ]
        },
        {
          "id": "4571baa4-2fcd-4581-917d-219b912a5e3e",
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
              "id": "c060fdd7-b789-431e-8ae4-9c9fd98a2044"
            }
          ]
        },
        {
          "id": "fe9e88a6-4255-430c-b5c8-fb42f9307c58",
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
              "id": "5336bac7-aed6-4a6e-ad7c-604a2baf65e2"
            }
          ]
        },
        {
          "id": "5454b957-1d54-4cef-8327-5e10bdd1ac60",
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
              "id": "4b9908e0-53a8-40b6-8fe5-43277826f75e"
            }
          ]
        },
        {
          "id": "254b3e37-ef5a-4a2a-ba87-85d447d5a370",
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
              "id": "1eacf08e-c78f-4ec4-8726-1bff34cc2c89"
            }
          ]
        },
        {
          "id": "e97acb03-afc4-4fef-bf6a-2cf9ff967ae7",
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
              "id": "b0952258-b54e-4b26-baec-736388361ba9"
            }
          ]
        },
        {
          "id": "34503c5d-2ba5-453e-ab08-d6383f3e86b0",
          "name": "getMyOrdersSelling",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/orders/selling/:id"
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
            "description": "Returns order details for a seller"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3cbfaf58-471f-490c-8ac0-b0583db75002"
            }
          ]
        }
      ]
    }
  ]
}