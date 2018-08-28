{
  "info": {
    "name": "reverb Delete My Follows Shops Slug",
    "_postman_id": "364834a0-a5b2-41b3-b6ee-2dd6e84a43d6",
    "description": "Delete my follows shops slug.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "a451c7fa-82c4-48b0-96f5-63e8e7687f02",
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
              "id": "7cb2373c-4a3b-4cdb-9230-93199c69d1f5"
            }
          ]
        }
      ]
    }
  ]
}