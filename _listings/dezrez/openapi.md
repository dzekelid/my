swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/negotiator/my/biography:
    post:
      summary: Update My Biography
      description: Update my biography.
      operationId: Negotiator_UpdateBiographyBytext
      x-api-path-slug: apinegotiatormybiography-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: text
      responses:
        200:
          description: OK
      tags:
      - My
      - Biography