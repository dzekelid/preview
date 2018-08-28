---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Groups API Preview processed html
  description: Preview processed html.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/preview_html:
    post:
      summary: Preview processed html
      description: Preview processed html.
      operationId: preview-processed-html
      x-api-path-slug: coursescourse-idpreview-html-post
      parameters:
      - in: query
        name: html
        description: The html content to process
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Preview
      - Html
  /groups/{group_id}/preview_html:
    post:
      summary: Preview processed html
      description: Preview processed html.
      operationId: preview-processed-html
      x-api-path-slug: groupsgroup-idpreview-html-post
      parameters:
      - in: query
        name: html
        description: The html content to process
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Group
      - Id
      - Preview
      - Html
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