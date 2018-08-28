{
  "info": {
    "name": "reverb Put My Addresses Address",
    "_postman_id": "3eedc255-a7e1-4ea2-bb72-ea54c7cf96db",
    "description": "Update an existing address in your address book",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "e2a7b218-f362-4adf-ba71-c9cca430c2db",
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
              "id": "7cb4d918-b911-4280-ad90-acec98a2794f"
            }
          ]
        },
        {
          "id": "f1d32ba2-0a54-45d7-ba6a-d689a844da88",
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
              "id": "57ef2377-fc62-4903-9026-0408de6fc578"
            }
          ]
        },
        {
          "id": "c1aab99a-a8a0-4e20-b6dc-b3836b4a826e",
          "name": "putMyAddressesAddress",
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
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update an existing address in your address book"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "470fa4e5-4c14-4b11-8b12-cc040fd308b6"
            }
          ]
        },
        {
          "id": "2c602941-d4ca-4c57-8427-ab0edb5fa681",
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
              "id": "92bcbd4f-7fed-4cef-8aef-9924297d213b"
            }
          ]
        }
      ]
    }
  ]
}