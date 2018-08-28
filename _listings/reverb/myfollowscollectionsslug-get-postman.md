{
  "info": {
    "name": "reverb Get My Follows Collections Slug",
    "_postman_id": "42ed532a-80d2-44d9-80d9-0f3b9ef884df",
    "description": "Get my follows collections slug.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "33a55ed5-b0d2-48ea-ac03-ba454abf09af",
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
              "id": "11e41aed-7d94-47c3-b316-75f9f3a924ff"
            }
          ]
        },
        {
          "id": "85a53fbc-1e68-4349-bcae-b3744c2d1f8d",
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
              "id": "f58fe271-547a-4467-ab28-f6028cef21a5"
            }
          ]
        }
      ]
    }
  ]
}