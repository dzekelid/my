---
swagger: "2.0"
x-collection-name: AT&T Dev Program
x-complete: 0
info:
  title: AT&T API Get My Messages Messageid
  description: /myMessages/v2/messages/{messageId}
  version: "1"
host: api.att.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /myMessages/v2/delta:
    get:
      summary: Get My Delta
      description: /myMessages/v2/delta
      operationId: mymessagesv2delta
      x-api-path-slug: mymessagesv2delta-get
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VDelta
  /myMessages/v2/messages:
    delete:
      summary: Delete My Messages
      description: /myMessages/v2/messages
      operationId: mymessagesv2messages
      x-api-path-slug: mymessagesv2messages-delete
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
    get:
      summary: Get My Messages
      description: /myMessages/v2/messages
      operationId: mymessagesv2messages
      x-api-path-slug: mymessagesv2messages-get
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
    post:
      summary: Post My Messages
      description: /myMessages/v2/messages
      operationId: mymessagesv2messages
      x-api-path-slug: mymessagesv2messages-post
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
  /myMessages/v2/messages/index:
    post:
      summary: Post My Messages Index
      description: /myMessages/v2/messages/index
      operationId: mymessagesv2messagesindex
      x-api-path-slug: mymessagesv2messagesindex-post
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
      - Index
  /myMessages/v2/messages/index/info:
    get:
      summary: Get My Messages Index Info
      description: /myMessages/v2/messages/index/info
      operationId: mymessagesv2messagesindexinfo
      x-api-path-slug: mymessagesv2messagesindexinfo-get
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
      - Index
      - Info
  /myMessages/v2/messages/{messageId}:
    delete:
      summary: Delete My Messages Messageid
      description: /myMessages/v2/messages/{messageId}
      operationId: mymessagesv2messagesmessageid
      x-api-path-slug: mymessagesv2messagesmessageid-delete
      parameters:
      - in: path
        name: messageId
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
      - MessageId
    get:
      summary: Get My Messages Messageid
      description: /myMessages/v2/messages/{messageId}
      operationId: mymessagesv2messagesmessageid
      x-api-path-slug: mymessagesv2messagesmessageid-get
      parameters:
      - in: path
        name: messageId
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
      - MessageId
  /myMessages/v2/messages/{messageId}/parts/{partId}:
    get:
      summary: Get My Messages Messageid Parts Partid
      description: /myMessages/v2/messages/{messageId}/parts/{partId}
      operationId: mymessagesv2messagesmessageidpartspartid
      x-api-path-slug: mymessagesv2messagesmessageidpartspartid-get
      parameters:
      - in: path
        name: messageId
      - in: path
        name: partId
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VMessages
      - MessageId
      - Parts
      - PartId
  /myMessages/v2/notificationConnectionDetails:
    get:
      summary: Get My Notificationconnectiondetails
      description: /myMessages/v2/notificationConnectionDetails
      operationId: mymessagesv2notificationconnectiondetails
      x-api-path-slug: mymessagesv2notificationconnectiondetails-get
      responses:
        200:
          description: OK
      tags:
      - MyMessages
      - VNotificationConnectionDetails
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---