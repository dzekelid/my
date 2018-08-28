{
  "info": {
    "name": "reverb Get My Orders Awaiting Feedback",
    "_postman_id": "a2b0615e-837a-4ee4-96f1-3c8dd1efde54",
    "description": "List of orders that need feedback",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "d48b7cc7-7a71-410f-ae41-5da7a867eb13",
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
              "id": "127f4c77-6c2c-483c-9d08-1cec7f492899"
            }
          ]
        }
      ]
    }
  ]
}