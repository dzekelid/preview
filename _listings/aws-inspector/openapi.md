---
swagger: "2.0"
x-collection-name: AWS Inspector
x-complete: 1
info:
  title: AWS Inspector API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=PreviewAgents:
    get:
      summary: Preview Agents
      description: |-
        Previews the agents installed on the EC2 instances that are part of the specified
                 assessment target.
      operationId: previewAgents
      x-api-path-slug: actionpreviewagents-get
      parameters:
      - in: query
        name: maxResults
        description: You can use this parameter to indicate the maximum number of
          items you want in the         response
        type: string
      - in: query
        name: nextToken
        description: You can use this parameter when paginating results
        type: string
      - in: query
        name: previewAgentsArn
        description: The ARN of the assessment target whose agents you want to preview
        type: string
      responses:
        200:
          description: OK
      tags:
      - Agents
---