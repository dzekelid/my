{
  "info": {
    "name": "reverb Post My Follows Categories Entifier",
    "_postman_id": "cb40284a-09d3-45fd-a4f2-c62660312f49",
    "description": "Post my follows categories entifier.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Categories",
      "item": [
        {
          "id": "ce8c7d32-687b-425c-95b7-2573537ac2a6",
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
              "id": "bdb99467-b99f-4a72-94cb-972f754f0654"
            }
          ]
        },
        {
          "id": "7d0e7bf5-268a-40e1-9f03-660b3037ee3b",
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
              "id": "b9ea9db1-c325-4831-b28e-83a3ac88cc33"
            }
          ]
        },
        {
          "id": "952976dc-f3d2-4539-a3cc-82655e0645f6",
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
              "id": "8afd2670-d848-4102-a030-6cb6adaff2bf"
            }
          ]
        },
        {
          "id": "62f4f9d4-5f9e-4f82-beb1-44f0cad2429b",
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
              "id": "97f861fc-6a91-4b9d-ae3a-5269611f4bfb"
            }
          ]
        },
        {
          "id": "897aa9e7-8d54-4296-bd4d-23c0c0ff5480",
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
              "id": "4969b11d-ae95-44a9-b54b-b3ca11d00c25"
            }
          ]
        }
      ]
    },
    {
      "name": "Csps",
      "item": [
        {
          "id": "1b182ce1-618d-4ae7-9a73-0924a1dc73e6",
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
              "id": "dc565ec0-5e4c-4f44-a12b-50dbfa644931"
            }
          ]
        }
      ]
    },
    {
      "name": "My",
      "item": [
        {
          "id": "335e19b3-615c-4615-a1f3-c81cbdd45322",
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
              "id": "db9affcb-5edc-45c3-87e0-404582861d32"
            }
          ]
        },
        {
          "id": "fc34aace-e96f-463d-99c1-0fe013b6aa93",
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
              "id": "ff3a8f6b-884f-4e48-89f7-842554450a14"
            }
          ]
        },
        {
          "id": "6aead888-67ab-4a6d-b273-f0a09a1f345d",
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
              "id": "bc5cc076-5915-45df-a354-e5d0e327e1c5"
            }
          ]
        },
        {
          "id": "491c3e7f-9874-47b4-b65e-edc508fe3294",
          "name": "getMyFollowsCategoriesEntifier",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get my follows categories entifier."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6b19a87-6710-4545-9a58-f4b35fdaf80a"
            }
          ]
        },
        {
          "id": "0834f254-96d3-4eaf-8d12-0fd2a32f633d",
          "name": "postMyFollowsCategoriesEntifier",
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post my follows categories entifier."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96e6402c-1d17-4cd4-8a95-f0b6cbb3696a"
            }
          ]
        },
        {
          "id": "b325738c-7f86-42ab-ade1-c2ccdc402e77",
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
              "id": "cb55ddb3-c68f-4faa-b537-b001ff7de9b1"
            }
          ]
        }
      ]
    }
  ]
}