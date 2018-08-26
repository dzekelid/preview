---
swagger: "2.0"
x-collection-name: OneNote
x-complete: 0
info:
  title: One Note Get Pages Pageid Preview
  description: Returns preview text and (if there is one) a preview image for the
    specified page.
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