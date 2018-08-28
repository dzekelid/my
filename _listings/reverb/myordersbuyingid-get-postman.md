{
  "info": {
    "name": "reverb Get My Orders Buying",
    "_postman_id": "732943ef-bff3-4363-84b0-bd618fcb5ab9",
    "description": "Returns order details for a buyer",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "e28d2212-8f6a-4e9e-b730-0b14ba2aa8c8",
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
              "id": "f5c02131-799c-445f-b1d1-69a627d379ef"
            }
          ]
        },
        {
          "id": "df65ac48-df90-4ddd-ad9f-de07e1768a88",
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
              "id": "52e03a5e-5e06-4f38-814b-15f5fa16296c"
            }
          ]
        },
        {
          "id": "72f2a6f3-9a2a-4df4-9966-98b76ed72b78",
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
              "id": "f1e17977-0e0b-4123-a324-6d0a2a283fb7"
            }
          ]
        },
        {
          "id": "1403110b-278c-4059-aa94-c3de63c87647",
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
              "id": "6f51e114-7dac-4cc4-a0da-ffc8ee47fc99"
            }
          ]
        }
      ]
    }
  ]
}