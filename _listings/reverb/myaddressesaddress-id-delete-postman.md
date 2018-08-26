{
  "info": {
    "name": "reverb Delete My Addresses Address",
    "_postman_id": "b41ccaec-87cc-48fc-9e48-31e042a2dc9d",
    "description": "Delete an existing address in your address book",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "6be598d3-76e5-4597-8c6e-1e66c61e1dd1",
          "name": "getMyAddresses",
          "request": {
            "url": "http://api.reverb.com/api/my/addresses",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "See all addresses in your address book"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78813e1f-9524-400d-9c6e-fb7a21c4f485"
            }
          ]
        },
        {
          "id": "b5b4aad5-ea1c-4198-ab20-8650b112ba1e",
          "name": "postMyAddresses",
          "request": {
            "url": "http://api.reverb.com/api/my/addresses",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new address in your address book"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aaff1f92-19b8-4089-8c0b-a8e691c75428"
            }
          ]
        },
        {
          "id": "2b407131-0b72-468d-aae9-2ffa95675ea4",
          "name": "deleteMyAddressesAddress",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/addresses/:address_id"
              ],
              "variable": [
                {
                  "id": "address_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete an existing address in your address book"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b0e7721f-43e3-48f8-b766-2c47513d2793"
            }
          ]
        }
      ]
    }
  ]
}