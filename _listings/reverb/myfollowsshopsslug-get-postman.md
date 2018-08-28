{
  "info": {
    "name": "reverb Get My Follows Shops Slug",
    "_postman_id": "6bedc413-94b3-47fa-b5df-0d571dcd120d",
    "description": "Get my follows shops slug.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "f9f7d212-2306-4d2d-a692-0088c97bb42c",
          "name": "getMyFollowsShopsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/shops/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get my follows shops slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5969405e-102a-434d-994f-e0c9d5692a02"
            }
          ]
        },
        {
          "id": "9943a980-3666-4539-8b88-3b282343897f",
          "name": "deleteMyFollowsShopsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/shops/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete my follows shops slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be02ad7b-4bad-4c62-80de-cbd2f0bf48e7"
            }
          ]
        }
      ]
    }
  ]
}