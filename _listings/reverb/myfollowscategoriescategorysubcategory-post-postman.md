{
  "info": {
    "name": "reverb Post My Follows Categories Category Subcategory",
    "_postman_id": "26206381-04d4-4288-87df-81621f828648",
    "description": "Post my follows categories category subcategory.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Categories",
      "item": [
        {
          "id": "619d330e-9118-48e0-a12d-e977dff7e986",
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
              "id": "f5da6a68-a792-421a-af88-96f451e435cb"
            }
          ]
        },
        {
          "id": "55863847-5c55-4d3a-9ae6-21654d0d8ef0",
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
              "id": "7d51d60c-e64e-4c0c-9b7f-346dca392208"
            }
          ]
        },
        {
          "id": "b5a2f2d9-e2f8-44be-ac43-b20961730b84",
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
              "id": "e9290642-9f14-4065-84e4-a4e0b7c2cb60"
            }
          ]
        },
        {
          "id": "3d6dd09e-3d82-40da-aa37-0bcbf1ca55d3",
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
              "id": "6b1c16c6-a018-4271-a708-dd402e1ce828"
            }
          ]
        },
        {
          "id": "fd0e16ca-b8fa-4399-9893-7ca9a4e648b0",
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
              "id": "27a5426c-0c7b-4cce-b599-b277cee31e5d"
            }
          ]
        }
      ]
    },
    {
      "name": "Csps",
      "item": [
        {
          "id": "767730df-b64e-4b76-ae1c-6123523a7059",
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
              "id": "c868cd51-a4ae-4d5a-9926-6d6bb1c79583"
            }
          ]
        }
      ]
    },
    {
      "name": "My",
      "item": [
        {
          "id": "bf72bc32-d5f5-4538-8681-fd5287292eea",
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
              "id": "f536cd7d-674e-4760-8745-1396290a2210"
            }
          ]
        },
        {
          "id": "1946fa89-0f67-4251-813e-660a9c2fc052",
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
              "id": "9e04531d-e3f5-495a-bdf8-de73ec14bb07"
            }
          ]
        },
        {
          "id": "344ecf92-2b52-452c-a334-42d17952e8a4",
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
              "id": "7804a480-232a-4d34-9afc-80c0c052d4c7"
            }
          ]
        }
      ]
    }
  ]
}