{
  "info": {
    "name": "reverb Get My Addresses",
    "_postman_id": "1e3b3c11-1ec6-4040-92ed-0b25affdd999",
    "description": "See all addresses in your address book",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "755ac131-3a57-4d2b-a444-ccfc546c9ab5",
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
              "id": "a35f36f5-04eb-434f-886e-47cd7a4957ea"
            }
          ]
        }
      ]
    }
  ]
}