{
  "info": {
    "name": "reverb Delete My Follows Categories Entifier",
    "_postman_id": "25b67125-62b3-4260-8ed5-a4792ded395b",
    "description": "Delete my follows categories entifier.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Categories",
      "item": [
        {
          "id": "3bf31022-9d5e-42a7-b77c-af62b7ceaf66",
          "name": "getCategories",
          "request": {
            "url": "http://api.reverb.com/api/categories",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List of supported product categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "135a2529-ecf9-4fe1-8713-25639e0551d7"
            }
          ]
        },
        {
          "id": "b12717b6-7234-4049-8420-b104799c460b",
          "name": "getCategoriesFlat",
          "request": {
            "url": "http://api.reverb.com/api/categories/flat",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get categories flat."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6c1565d2-fc90-4a5e-9509-eca233020dc9"
            }
          ]
        },
        {
          "id": "012dbdbe-9902-48dc-8338-3f17f8e91f11",
          "name": "getCategoriesTaxonomy",
          "request": {
            "url": "http://api.reverb.com/api/categories/taxonomy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Full taxonomy tree of categories including middle categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e4f18e3-eaf2-46e1-817c-28114b148b83"
            }
          ]
        },
        {
          "id": "bfdaa537-8369-401d-9e89-f2f67ac7ea5f",
          "name": "getCategoriesProductTypeCategory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "categories/:product_type/:category"
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "product_type",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get categories product type category."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2646376-6843-45cd-b372-b11ddad84dcd"
            }
          ]
        },
        {
          "id": "93948822-c416-42c2-b3cd-f21db06b7535",
          "name": "getCategoriesUu",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "categories/:uuid"
              ],
              "variable": [
                {
                  "id": "uuid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get category details"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "447e3ed2-eab3-4dcb-a703-4f6253c0fe5a"
            }
          ]
        }
      ]
    },
    {
      "name": "Csps",
      "item": [
        {
          "id": "cb86d447-a9c0-490e-871e-1310723c35dd",
          "name": "getCspsCategories",
          "request": {
            "url": "http://api.reverb.com/api/csps/categories",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get csps categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "375ccfcf-ac8f-47bb-a6eb-ab9f835441d3"
            }
          ]
        }
      ]
    },
    {
      "name": "My",
      "item": [
        {
          "id": "cc1e2055-4a66-4d9b-98b4-6950ee10a8a8",
          "name": "getMyFollowsCategoriesCategorySubcategory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/categories/:category/:subcategory"
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subcategory",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get my follows categories category subcategory."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57a36a8d-059e-4950-bfd2-e4707fa310a0"
            }
          ]
        },
        {
          "id": "7126b01f-5c94-4f63-983c-686d029d9dc0",
          "name": "postMyFollowsCategoriesCategorySubcategory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/categories/:category/:subcategory"
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subcategory",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post my follows categories category subcategory."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fe41ccf-621d-4917-aed6-4e6262d437ab"
            }
          ]
        },
        {
          "id": "4026630a-5074-481e-970d-c1fd299d258a",
          "name": "deleteMyFollowsCategoriesCategorySubcategory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/categories/:category/:subcategory"
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subcategory",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete my follows categories category subcategory."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98fbc4b7-5fa0-49e5-bce9-6497c2ceceed"
            }
          ]
        },
        {
          "id": "64a3bcac-6c38-4034-aa4a-e8ecde953784",
          "name": "deleteMyFollowsCategoriesEntifier",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/categories/:identifier"
              ],
              "variable": [
                {
                  "id": "identifier",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete my follows categories entifier."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f96101a6-21c6-4ce9-9a7a-83c6fc732c3f"
            }
          ]
        }
      ]
    }
  ]
}