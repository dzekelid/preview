---
swagger: "2.0"
x-collection-name: HHS Media Services
x-complete: 0
info:
  title: HHS Media Services Get JPG preview for MediaItem
  description: Returns the JPG preview, where applicable, for the MediaItem identified
    by the 'id'.
  termsOfService: http://www.hhs.gov/web/socialmedia/policies/tos.html#ready
  version: "2"
host: api.digitalmedia.hhs.gov
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /resources/media/{id}/preview.jpg:
    get:
      summary: Get JPG preview for MediaItem
      description: Returns the JPG preview, where applicable, for the MediaItem identified
        by the 'id'.
      operationId: getMediaPreviewById
      x-api-path-slug: resourcesmediaidpreview-jpg-get
      parameters:
      - in: path
        name: id
        description: The id of the media to get a preview for
      responses:
        200:
          description: OK
      tags:
      - Resources
      - Media
      - Id
      - Preview
      - Jpg
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