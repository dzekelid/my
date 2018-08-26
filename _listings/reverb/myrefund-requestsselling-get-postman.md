{
  "info": {
    "name": "reverb Get My Refund Requests Selling",
    "_postman_id": "fc5e6623-c354-4ba7-a386-41ea72a51cb4",
    "description": "Get a list of refund requests as a seller",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "ec246f15-29da-4b80-9ec3-4e3844e92558",
          "name": "postMyOrdersSellingOrderRefundRequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/orders/selling/:order_id/refund_requests"
              ],
              "variable": [
                {
                  "id": "order_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post my orders selling order refund requests."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d043ffd-294a-44d6-b60e-1e0cccc173a7"
            }
          ]
        },
        {
          "id": "bb69375b-b457-4d77-bb1e-b388612faac9",
          "name": "getMyRefundRequestsSelling",
          "request": {
            "url": "http://api.reverb.com/api/my/refund_requests/selling",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of refund requests as a seller"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c26ae5b1-6153-470c-a154-9bbafb9e2263"
            }
          ]
        }
      ]
    }
  ]
}