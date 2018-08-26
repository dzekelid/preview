---
swagger: "2.0"
x-collection-name: OneNote
x-complete: 1
info:
  title: One Note
  description: easily-capture-content-into-onenote-with-this-rest-api-
  version: 1.0.0
host: www.onenote.com
basePath: /api/v1.0/me/notes/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pages/{pageId}/preview:
    get:
      summary: Get Pages Pageid Preview
      description: Returns preview text and (if there is one) a preview image for
        the specified page.
      operationId: getPagesPagePreview
      x-api-path-slug: pagespageidpreview-get
      parameters:
      - in: query
        name: Content-Type
        description: 'Required: indicates type of content being sent'
      - in: path
        name: pageId
        description: Specifies the page whose content you want to retrieve
      responses:
        200:
          description: OK
      tags:
      - Pages
      - PageId
      - Preview
---