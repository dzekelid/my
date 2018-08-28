{
  "info": {
    "name": "Dezrez Update My Biography",
    "_postman_id": "3f7a2787-4b66-4235-a4c0-d1224f8b8c2d",
    "description": "Update my biography.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "e3dbd35e-3657-4282-aa7f-ee3ad129cde7",
          "name": "Negotiator_UpdateBiographyBytext",
          "request": {
            "url": "http://api.dezrez.com/api/negotiator/my/biography?text=%7B%7D",
            "method": "POST",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Update my biography."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "209ab83a-e2f2-4b17-bc1c-ee765356d95c"
            }
          ]
        }
      ]
    }
  ]
}