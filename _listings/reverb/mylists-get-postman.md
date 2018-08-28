{
  "info": {
    "name": "reverb Get My Lists",
    "_postman_id": "012675bf-0d73-4298-82a5-6233de8f5b2d",
    "description": "Get a list of your lists (wishlist, watch list, etc)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "201e9963-3738-4628-b2ef-2a4947983ead",
          "name": "getMyLists",
          "request": {
            "url": "http://api.reverb.com/api/my/lists",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of your lists (wishlist, watch list, etc)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b8a027ae-2934-41ea-a09d-d314c5986a7a"
            }
          ]
        }
      ]
    }
  ]
}