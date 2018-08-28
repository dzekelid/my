{
  "info": {
    "name": "reverb Get My Follows Categories Category Subcategory",
    "_postman_id": "6718d083-3670-4bfb-ac3a-61afb0d03075",
    "description": "Get my follows categories category subcategory.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Categories",
      "item": [
        {
          "id": "57553a1b-ba05-4f9b-bb4f-2a2f91a4bcfe",
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
              "id": "e76694d4-216a-457f-bc06-3a4f3d721ed4"
            }
          ]
        },
        {
          "id": "4d001aa8-9706-449e-9fe6-77630738a00a",
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
              "id": "f313976e-166d-4f84-8915-c477f1931725"
            }
          ]
        },
        {
          "id": "d1ef7c7c-c0e0-4c22-bf35-34fe622c554c",
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
              "id": "3e7f69e9-5949-482d-8580-8a95c9e06da2"
            }
          ]
        },
        {
          "id": "b5c94143-ea0a-4575-ad88-ab476225b5ed",
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
              "id": "a4f0073f-67eb-4600-a3dd-c98df483e10c"
            }
          ]
        },
        {
          "id": "3aa95581-7a05-4743-bb2c-ef3459ed5efa",
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
              "id": "8dda86b6-6615-4781-9851-35d58489abc1"
            }
          ]
        }
      ]
    },
    {
      "name": "Csps",
      "item": [
        {
          "id": "15a3671f-83a7-426c-a55e-de3f92bf8548",
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
              "id": "428ed13d-e554-46d0-8042-082142a78161"
            }
          ]
        }
      ]
    },
    {
      "name": "My",
      "item": [
        {
          "id": "8f6868c0-4937-4fb0-b730-dfcebd9a3493",
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
              "id": "39e5146d-a4f3-43a1-9fb7-d68539b63a9c"
            }
          ]
        },
        {
          "id": "8232b771-d810-42f8-96ea-f98b95fb9dfe",
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
              "id": "ddc6b41f-0bac-4edb-b390-a508edfb102b"
            }
          ]
        }
      ]
    }
  ]
}