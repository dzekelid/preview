---
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
  /api/documentgeneration/previewpack:
    post:
      summary: Generates a pack using the first selected group/property of a type
        to get a quick preview of the pack
      description: Generates a pack using the first selected group/property of a type
        to get a quick preview of the pack.
      operationId: DocumentGeneration_PreviewPackByrandomPackDataContract
      x-api-path-slug: apidocumentgenerationpreviewpack-post
      parameters:
      - in: body
        name: randomPackDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Pack
      - Using
      - First
      - Selected
      - Group
      - Property
      - Of
      - Type
      - To
      - Get
      - Quick
      - Preview
      - Of
      - Pack
---