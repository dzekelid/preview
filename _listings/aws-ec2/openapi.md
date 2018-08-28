swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 1
info:
  title: AWS EC2 API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetHostReservationPurchasePreview:
    get:
      summary: Get Host Reservation Purchase Preview
      description: |-
        Preview a reservation purchase with configurations that match those of your
                    Dedicated Host.
      operationId: gethostreservationpurchasepreview
      x-api-path-slug: actiongethostreservationpurchasepreview-get
      parameters:
      - in: query
        name: AutoPlacement
        description: Specify whether to enable or disable auto-placement
        type: string
      - in: query
        name: HostId.N
        description: The host IDs of the Dedicated Hosts you want to modify
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host Reservation