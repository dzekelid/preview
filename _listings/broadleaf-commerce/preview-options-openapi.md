---
swagger: "2.0"
x-collection-name: Broadleaf Commerce
x-complete: 0
info:
  title: Broadleaf Commerce API Options Preview **
  description: Options preview **.
  version: 1.0.0
host: demo.broadleafcommerce.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /preview/**:
    get:
      summary: Get Preview **
      description: Get preview **.
      operationId: getPreview**
      x-api-path-slug: preview-get
      responses:
        200:
          description: OK
      tags:
      - Preview
      - '**'
    head:
      summary: Head Preview **
      description: Head preview **.
      operationId: headPreview**
      x-api-path-slug: preview-head
      responses:
        200:
          description: OK
      tags:
      - Head
      - Preview
      - '**'
    post:
      summary: Post Preview **
      description: Post preview **.
      operationId: postPreview**
      x-api-path-slug: preview-post
      responses:
        200:
          description: OK
      tags:
      - Preview
      - '**'
    put:
      summary: Put Preview **
      description: Put preview **.
      operationId: putPreview**
      x-api-path-slug: preview-put
      responses:
        200:
          description: OK
      tags:
      - Preview
      - '**'
    delete:
      summary: Delete Preview **
      description: Delete preview **.
      operationId: deletePreview**
      x-api-path-slug: preview-delete
      responses:
        200:
          description: OK
      tags:
      - Preview
      - '**'
    options:
      summary: Options Preview **
      description: Options preview **.
      operationId: optionsPreview**
      x-api-path-slug: preview-options
      responses:
        200:
          description: OK
      tags:
      - Options
      - Preview
      - '**'
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