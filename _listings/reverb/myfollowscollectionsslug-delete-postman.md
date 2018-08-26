{
  "info": {
    "name": "reverb Delete My Follows Collections Slug",
    "_postman_id": "cb003177-c5e7-4463-801f-22cb76bcc958",
    "description": "Delete my follows collections slug.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "7c478209-a1e1-4c7c-bb71-3d735482dc69",
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
              "id": "d535ecb7-9ffc-4612-a1ee-15c9bf3feaa1"
            }
          ]
        }
      ]
    }
  ]
}