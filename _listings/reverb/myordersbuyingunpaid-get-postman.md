{
  "info": {
    "name": "reverb Get My Orders Buying Unpa",
    "_postman_id": "af995483-9a07-4afc-b7d5-50a0e039ee3e",
    "description": "Returns unpaid orders, newest first.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "54d5271d-0f0a-42a5-97b1-c13575e40184",
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
              "id": "68e90df8-3c9a-4343-82a0-556381095ea4"
            }
          ]
        },
        {
          "id": "d1d09775-579e-4131-badd-3b356314e448",
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
              "id": "96c54549-501d-4da0-bf71-b6c361679be0"
            }
          ]
        },
        {
          "id": "1907a3f2-a549-40c3-8874-f0d69afe75bf",
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
              "id": "68ab93a3-6efb-405e-8656-d0b6c56ee2d1"
            }
          ]
        }
      ]
    }
  ]
}