{
  "info": {
    "name": "reverb Post My Follows Collections Slug",
    "_postman_id": "6d9849a1-a0ec-4ec1-868b-dc4edbbc85cc",
    "description": "Post my follows collections slug.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "8a373a04-23da-444c-b9dd-0d523be01344",
          "name": "getMyFollowsCollectionsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/collections/:slug"
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
            "description": "Get my follows collections slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "526c896c-753a-4f9c-8fd7-fd5ef5d09b6e"
            }
          ]
        },
        {
          "id": "672b8fd7-e08a-4b71-968c-521aa504ad51",
          "name": "postMyFollowsCollectionsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/collections/:slug"
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
            "description": "Post my follows collections slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2b5ee8e-7148-490a-a439-cc975c18be80"
            }
          ]
        },
        {
          "id": "231d78d8-aa59-4cd8-a6d8-bfd38269e4a7",
          "name": "deleteMyFollowsCollectionsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/collections/:slug"
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
            "description": "Delete my follows collections slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac28ec83-f15a-48cd-aa7b-a45e87a5b29b"
            }
          ]
        }
      ]
    }
  ]
}