{
  "info": {
    "name": "reverb Post My Follows Shops Slug",
    "_postman_id": "bd2166ad-1ae1-433f-a118-7d2700b6d291",
    "description": "Post my follows shops slug.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "bd242158-dc57-498b-b96d-0d976521112c",
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
              "id": "60b339ba-2e45-4e2c-90ba-c284d2fff5a0"
            }
          ]
        },
        {
          "id": "ab67b848-466c-42cd-9890-336ff1ccc488",
          "name": "postMyFollowsShopsSlug",
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post my follows shops slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a1f8d9a-d09e-428e-9444-eb8afc6bf039"
            }
          ]
        },
        {
          "id": "77672089-5c5c-47ae-9cf4-b2855868e330",
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
              "id": "99f6b661-9458-4bc8-8295-1963e8958517"
            }
          ]
        }
      ]
    }
  ]
}