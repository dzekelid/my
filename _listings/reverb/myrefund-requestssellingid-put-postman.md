{
  "info": {
    "name": "reverb Put My Refund Requests Selling",
    "_postman_id": "565b5132-1683-4d0a-a961-6363b8305692",
    "description": "Update a refund request for a sold order",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "b8c5b48b-4d55-4694-b9bc-713b0d9900d6",
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
              "id": "b24e696c-f20a-4177-9db2-88f4b60cabcc"
            }
          ]
        },
        {
          "id": "5011b00f-1c9f-4b05-90ad-710a7a89eaf2",
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
              "id": "dad28c9a-48f0-4738-990b-4fe200a887c3"
            }
          ]
        },
        {
          "id": "1ce522ba-7b14-41dc-a1e9-c5ca33fbcf9c",
          "name": "putMyRefundRequestsSelling",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/refund_requests/selling/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a refund request for a sold order"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4760c64b-9b8b-43c6-978a-97a3bd8ca43c"
            }
          ]
        }
      ]
    }
  ]
}