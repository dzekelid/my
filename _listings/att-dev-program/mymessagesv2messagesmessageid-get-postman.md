{
  "info": {
    "name": "AT&T API Get My Messages Messageid",
    "_postman_id": "68cd4ed6-9c93-4505-9924-39d0b564ed5f",
    "description": "/myMessages/v2/messages/{messageId}",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devicecapabilities",
      "item": [
        {
          "id": "44af6521-5e33-46e3-a4d6-7105ba4937a0",
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
              "id": "3cf9f58b-943b-4cbf-8b9d-f54f3ef8138a"
            }
          ]
        }
      ]
    },
    {
      "name": "Messaging",
      "item": [
        {
          "id": "470349d6-ea38-402d-93b1-9840daff2931",
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
              "id": "786f30b3-2f04-46b2-9b97-69af9578cb29"
            }
          ]
        },
        {
          "id": "5a59b7b1-dd18-40f2-9371-fb27cd844877",
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
              "id": "c3042827-c53b-459c-818b-2e5f832507a9"
            }
          ]
        }
      ]
    },
    {
      "name": "Smsmessaging",
      "item": [
        {
          "id": "d4b0ae24-d7ea-4a0a-b216-bb3ca2638be6",
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
              "id": "44316b44-3d75-40f9-b71e-57e4927079c7"
            }
          ]
        },
        {
          "id": "8871910b-59a1-44e9-ab3e-1addc468055d",
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
              "id": "d13e8302-04a6-4490-8f89-11647699a6e5"
            }
          ]
        },
        {
          "id": "d7365870-c1f6-44e6-88d5-a6cd47ddfdc7",
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
              "id": "c75e66c5-0476-435e-9639-e32ec19bd785"
            }
          ]
        }
      ]
    },
    {
      "name": "Mms",
      "item": [
        {
          "id": "3a893c56-3430-4f46-92de-642727f65cb4",
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
              "id": "d4c2d327-7c7e-4b7e-82e8-ec755651fc7e"
            }
          ]
        },
        {
          "id": "f759db0d-b789-4832-9122-aba8e8a2ae09",
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
              "id": "eb2da566-266c-4855-b6b8-3f12c67a8faa"
            }
          ]
        }
      ]
    },
    {
      "name": "MyMessages",
      "item": [
        {
          "id": "3956da74-0b41-40a8-9957-0010dc1a2634",
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
              "id": "525b776d-cd7b-4d89-bcc6-a81fd80168d5"
            }
          ]
        },
        {
          "id": "c0e7a8f8-2351-492f-97a9-f5eaa57cafbb",
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
              "id": "ed668162-ccdd-49f6-9aa4-3717d94ea99a"
            }
          ]
        },
        {
          "id": "907d0213-1538-483a-bb9e-7dd9428d2a83",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "POST",
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
              "id": "76592d4a-9b4d-4724-8b29-4cd284291d35"
            }
          ]
        },
        {
          "id": "d045b506-8894-4287-b439-39b961681c62",
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
              "id": "d9263bb2-4c34-40b0-92e2-39d553eded30"
            }
          ]
        },
        {
          "id": "04676b49-b1b1-48ca-8534-873551bc1bdf",
          "name": "mymessagesv2messagesindex",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages/index",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/index"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a10b98d-26c3-479b-ae9b-062e3dfabebb"
            }
          ]
        },
        {
          "id": "105c52ad-13f0-4a93-9039-05b92125f928",
          "name": "mymessagesv2messagesindexinfo",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages/index/info",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/index/info"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "595c50a5-2ae0-410d-95f9-974480126ebf"
            }
          ]
        },
        {
          "id": "6e8f182d-8cfe-4753-bcf9-4e811ff65fd3",
          "name": "mymessagesv2messagesmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId"
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
            "description": "/myMessages/v2/messages/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "925a99ab-0c37-41c4-af4a-302ef7fa2d72"
            }
          ]
        },
        {
          "id": "b03607be-3c64-42f7-bbf3-0611fa4cd952",
          "name": "mymessagesv2messagesmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0537253e-bf9d-4387-bea0-355342de55ad"
            }
          ]
        }
      ]
    }
  ]
}