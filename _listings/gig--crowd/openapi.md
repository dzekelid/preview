swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/gigme/event/previews/map:
    post:
      summary: Post Gigme Event Previews Map
      description: Post gigme event previews map.
      operationId: postApiV1GigmeEventPreviewsMap
      x-api-path-slug: apiv1gigmeeventpreviewsmap-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Event
      - Previews
      - Map
  /api/v1/gigme/event/previews/{page}:
    post:
      summary: Post Gigme Event Previews Page
      description: Post gigme event previews page.
      operationId: postApiV1GigmeEventPreviewsPage
      x-api-path-slug: apiv1gigmeeventpreviewspage-post
      parameters:
      - in: path
        name: page
      - in: body
        name: preview
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Event
      - Previews
      - Page