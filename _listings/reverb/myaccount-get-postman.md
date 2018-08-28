{
  "info": {
    "name": "reverb Get My Account",
    "_postman_id": "1a278b1f-eb5d-46fa-812b-6ced5c44168e",
    "description": "Get account details",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Countries",
      "item": [
        {
          "id": "38d66a15-a0cf-4b3b-8085-89e8f86cbb7c",
          "name": "getCountries",
          "request": {
            "url": "http://api.reverb.com/api/countries",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a list of country codes with corresponding subregions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de4d22f7-b49e-4ebf-b3ba-702be2599c28"
            }
          ]
        }
      ]
    },
    {
      "name": "My",
      "item": [
        {
          "id": "144ea931-990a-405d-95f9-852dfe46c717",
          "name": "getMyAccount",
          "request": {
            "url": "http://api.reverb.com/api/my/account",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get account details"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e879ed0a-d8d4-447c-8086-2fb7b68fbdbf"
            }
          ]
        }
      ]
    }
  ]
}