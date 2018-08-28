{
  "info": {
    "name": "reverb Post My Addresses",
    "_postman_id": "6b5fda29-87d8-4bb3-8e08-dc1feaae9a1f",
    "description": "Create a new address in your address book",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "69fe7602-a901-4f9e-ac97-426d1ca0be6d",
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
              "id": "8bedd890-ab8e-42a6-8e76-4f73666a30d5"
            }
          ]
        },
        {
          "id": "a1429dc7-8ad4-4509-9321-2ee47c6476df",
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
              "id": "a7392389-4c6b-4b14-8e83-1509eeaf8d5a"
            }
          ]
        }
      ]
    }
  ]
}