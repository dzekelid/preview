swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
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