{
  "info": {
    "name": "reverb Get My Orders Buying All",
    "_postman_id": "305dbf20-6bb1-4613-b335-be415e179c5b",
    "description": "Returns all orders, newest first.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "b3ada87b-025e-40f4-a871-8eaee5142179",
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
              "id": "764c4450-15f9-4ae2-bc0f-a5e42808a445"
            }
          ]
        },
        {
          "id": "19ccb04c-f713-43c5-9b74-1cf6864c3e3e",
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
              "id": "8450bbc6-c550-462d-99b8-3cd77af816a0"
            }
          ]
        }
      ]
    }
  ]
}