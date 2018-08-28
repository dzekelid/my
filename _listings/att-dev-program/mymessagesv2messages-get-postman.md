{
  "info": {
    "name": "AT&T API Get My Messages",
    "_postman_id": "9120e02b-b520-4a6c-bf61-fbefa3767087",
    "description": "/myMessages/v2/messages",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devicecapabilities",
      "item": [
        {
          "id": "a7c513bc-84e7-4d4e-89a7-212285989b30",
          "name": "1devicecapabilitiesacrauthorizationcapabilities",
          "request": {
            "url": "http://api.att.com/1/devicecapabilities/acr:authorization/capabilities",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/1/devicecapabilities/acr:authorization/capabilities"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d176ea27-45ae-401e-9707-0c6aae270dd2"
            }
          ]
        }
      ]
    },
    {
      "name": "Messaging",
      "item": [
        {
          "id": "d6ff7c19-6078-4d02-bbc1-c0c7ef8a82b6",
          "name": "3messagingoutboundsenderaddressrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/messaging/outbound/:senderAddress/requests"
              ],
              "variable": [
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/3/messaging/outbound/{senderAddress}/requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ba0b308-5ef1-4b73-b00c-f3f2b2ce2d34"
            }
          ]
        },
        {
          "id": "b5da1c44-a0db-4bdc-a1af-98af29c7ac30",
          "name": "3messagingoutboundsenderaddressrequestiddeliveryinfos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/messaging/outbound/:senderAddress/:requestId/deliveryInfos"
              ],
              "variable": [
                {
                  "id": "requestId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/messaging/outbound/{senderAddress}/{requestId}/deliveryInfos"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b680bfb-00cb-434b-8849-f0f8f70b8aba"
            }
          ]
        }
      ]
    },
    {
      "name": "Smsmessaging",
      "item": [
        {
          "id": "da279676-6580-4655-9e7f-efb95ed03a2c",
          "name": "3smsmessaginginboundregistrationsregistrationidmessages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/inbound/registrations/:registrationId/messages"
              ],
              "variable": [
                {
                  "id": "registrationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/inbound/registrations/{registrationId}/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8d31333-e5f0-40f8-8daa-512076153869"
            }
          ]
        },
        {
          "id": "1fbd13c8-aed9-4ce2-abfd-36c62162e51f",
          "name": "3smsmessagingoutboundrequestssenderaddressrequestiddeliveryinfos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/outbound/requests/:senderAddress/:requestId/deliveryInfos"
              ],
              "variable": [
                {
                  "id": "requestId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/outbound/requests/{senderAddress}/{requestId}/deliveryInfos"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0572e17b-2d92-4efc-8bc6-55b9a71f90d4"
            }
          ]
        },
        {
          "id": "70a2a3e0-b827-42a9-b632-4c73ad5b939e",
          "name": "3smsmessagingoutboundsenderaddressrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/outbound/:senderAddress/requests"
              ],
              "variable": [
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/outbound/{senderAddress}/requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "440e58a3-4715-4e54-a01a-d8635edd391f"
            }
          ]
        }
      ]
    },
    {
      "name": "Mms",
      "item": [
        {
          "id": "65128dd6-d99d-4ea2-9d82-a226696fda36",
          "name": "mmsv3messagingoutbox",
          "request": {
            "url": "http://api.att.com/mms/v3/messaging/outbox",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/mms/v3/messaging/outbox"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "17845032-5a71-406c-b70f-608933cc4bc6"
            }
          ]
        },
        {
          "id": "8b446e7f-cd94-4ae7-bcd0-d847afd98f8b",
          "name": "mmsv3messagingoutboxmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "mms/v3/messaging/outbox/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/mms/v3/messaging/outbox/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59b11f52-b512-4f2c-bac2-9362be257fce"
            }
          ]
        }
      ]
    },
    {
      "name": "MyMessages",
      "item": [
        {
          "id": "2df66dd6-ef09-48cd-8992-c03953aeb2bc",
          "name": "mymessagesv2delta",
          "request": {
            "url": "http://api.att.com/myMessages/v2/delta",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/delta"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04d1a0d3-f002-4e3b-bd43-afd1554cfcc1"
            }
          ]
        },
        {
          "id": "db53e838-f5ad-4887-b635-b62b4becf9c9",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8793a996-2eec-42d5-8794-30fa97d8e9b0"
            }
          ]
        },
        {
          "id": "aaa6897d-49f2-4d82-9713-c5959b955160",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e73b8347-664f-4e15-af23-8f7e99f8c545"
            }
          ]
        }
      ]
    }
  ]
}