{
  "info": {
    "name": "reverb Get My Follows Categories Entifier",
    "_postman_id": "04a23c86-1ad0-4d92-8461-f4e03b9ea720",
    "description": "Get my follows categories entifier.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Categories",
      "item": [
        {
          "id": "54fd722a-2e5e-445e-8c1b-93e153535a2e",
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
              "id": "b0c0ccaf-e374-4a71-ba2b-956ebe704d12"
            }
          ]
        },
        {
          "id": "e284ce84-c9b4-49ae-a1e7-05bbf27a32e2",
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
              "id": "b96fb632-d5fd-468c-93b5-c8a0d8ad0d7f"
            }
          ]
        },
        {
          "id": "35ecf291-d241-469d-96ec-01b2a584d29d",
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
              "id": "12aa7123-da21-4d4a-8d73-df6d71ea5223"
            }
          ]
        },
        {
          "id": "eda0bb2b-0a06-4f06-af9a-989b9dded011",
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
              "id": "4064c395-2bfc-454b-99c3-d10c76e19805"
            }
          ]
        },
        {
          "id": "6369d4d3-9158-4beb-9cbe-8ed9f4462673",
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
              "id": "1905498b-bf18-4c57-83d9-7c54b610eb52"
            }
          ]
        }
      ]
    },
    {
      "name": "Csps",
      "item": [
        {
          "id": "247caaca-a388-4356-889a-66be912ec9c4",
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
              "id": "93f502cd-7a6f-41f6-9edd-deb59ee160ad"
            }
          ]
        }
      ]
    },
    {
      "name": "My",
      "item": [
        {
          "id": "193ecc56-edbd-4bcc-9de1-874a13bdd7f3",
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
              "id": "8960d2bb-fd9e-4abb-99b8-58b43b901e1e"
            }
          ]
        },
        {
          "id": "a3b68078-9be3-440a-8ac7-a60810e47bff",
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
              "id": "c2915a0a-7814-4239-ad8f-e7e21bb96a21"
            }
          ]
        },
        {
          "id": "7b5da33c-4e88-4d7e-bbed-a9e8d8bfdd1d",
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
              "id": "f8e32069-5512-4693-a81b-3f53ec1199f5"
            }
          ]
        },
        {
          "id": "b5125730-b984-4636-b40f-eb27edc973e3",
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
              "id": "b1daf7dc-c08a-4d8d-b461-bfe063579b01"
            }
          ]
        },
        {
          "id": "dbba1017-fc04-4d3e-b782-06ce678dfb11",
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
              "id": "573523b4-6a14-41b7-b00f-269ff0fca43a"
            }
          ]
        }
      ]
    }
  ]
}