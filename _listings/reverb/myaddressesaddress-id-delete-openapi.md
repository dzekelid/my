---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Delete My Addresses Address
  description: Delete an existing address in your address book
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /my/account:
    get:
      summary: Get My Account
      description: Get account details
      operationId: getMyAccount
      x-api-path-slug: myaccount-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Account
    put:
      summary: Put My Account
      description: Update account details
      operationId: putMyAccount
      x-api-path-slug: myaccount-put
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - My
      - Account
  /my/addresses:
    get:
      summary: Get My Addresses
      description: See all addresses in your address book
      operationId: getMyAddresses
      x-api-path-slug: myaddresses-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
    post:
      summary: Post My Addresses
      description: Create a new address in your address book
      operationId: postMyAddresses
      x-api-path-slug: myaddresses-post
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
  /my/addresses/{address_id}:
    delete:
      summary: Delete My Addresses Address
      description: Delete an existing address in your address book
      operationId: deleteMyAddressesAddress
      x-api-path-slug: myaddressesaddress-id-delete
      parameters:
      - in: path
        name: address_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Addresses
      - Address
      - Id
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