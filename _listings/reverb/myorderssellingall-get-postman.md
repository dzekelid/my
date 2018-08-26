{
  "info": {
    "name": "reverb Get My Orders Selling All",
    "_postman_id": "6533eac5-1030-42e6-9002-98699e2132e2",
    "description": "Get all seller orders, newest first.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "b1f890b9-d11d-4f70-a278-339b9ed9652f",
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
              "id": "766c6e77-b347-4a49-8a4e-86322e8a9032"
            }
          ]
        },
        {
          "id": "0e5c1818-12bc-4e3e-ab15-891334c41dc7",
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
              "id": "6ab021b2-7bad-4155-8df4-99aaf53245d9"
            }
          ]
        },
        {
          "id": "bbcd6ed0-4354-4634-b06d-8a719ad89067",
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
              "id": "7cb91a01-4eb1-45d9-b5b6-42f20e19c226"
            }
          ]
        },
        {
          "id": "d539e338-8c25-4fda-a850-54e5ac3683d2",
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
              "id": "37c82519-d25f-4eb1-b38d-068e6bcacf07"
            }
          ]
        },
        {
          "id": "877d25f8-c228-43a9-b6cd-df48a361e994",
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
              "id": "3fe7c9b8-13ff-4d4c-ab71-260eca9340d0"
            }
          ]
        },
        {
          "id": "f6f847ab-6d55-4d93-843e-3cf319433199",
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
              "id": "76b6e00b-631c-4d88-8359-efa53163fd80"
            }
          ]
        }
      ]
    }
  ]
}