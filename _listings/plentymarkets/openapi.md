---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/listings/option_templates/preview:
    get:
      summary: Get a preview list of option templates
      description: Gets a preview list of all available listing option templates.
      operationId: getRestListingsOptionTemplatesPreview
      x-api-path-slug: restlistingsoption-templatespreview-get
      responses:
        200:
          description: OK
      tags:
      - Preview
      - List
      - Of
      - Option
      - Templates
  /rest/orders/shipping/parcels/preview/{language?}:
    get:
      summary: Get a preview list for parcel services.
      description: Get a preview list for parcel services..
      operationId: getRestOrdersShippingParcelsPreviewLanguage
      x-api-path-slug: restordersshippingparcelspreviewlanguage-get
      parameters:
      - in: query
        name: language
      - in: path
        name: language?
      responses:
        200:
          description: OK
      tags:
      - Preview
      - Listparcel
      - Services
  /rest/orders/shipping/presets/preview/{language?}:
    get:
      summary: Get a preview list for parcel service presets.
      description: Get a preview list for parcel service presets..
      operationId: getRestOrdersShippingPresetsPreviewLanguage
      x-api-path-slug: restordersshippingpresetspreviewlanguage-get
      parameters:
      - in: query
        name: language
      - in: path
        name: language?
      responses:
        200:
          description: OK
      tags:
      - Preview
      - Listparcel
      - Service
      - Presets
  /rest/payments/methods/preview/{language?}:
    get:
      summary: Get a preview list for parcel services.
      description: Get a preview list for parcel services..
      operationId: getRestPaymentsMethodsPreviewLanguage
      x-api-path-slug: restpaymentsmethodspreviewlanguage-get
      parameters:
      - in: query
        name: language
      - in: path
        name: language?
      responses:
        200:
          description: OK
      tags:
      - Preview
      - Listparcel
      - Services
  /rest/plugin_sets/preview_hash:
    get:
      summary: Get the preview hash for a set
      description: Get the hash required to preview a plugin set. Response content
        will be in the form ['previewHash' => 'adf245o9nwu90sdfjw409u4'].
      operationId: getRestPluginSetsPreviewHash
      x-api-path-slug: restplugin-setspreview-hash-get
      responses:
        200:
          description: OK
      tags:
      - Preview
      - Hasha
      - Set
  /rest/warehouses/locations/previews:
    post:
      summary: Generate warehouse location preview and saves it
      description: Generates warehouse location preview and saves it
      operationId: postRestWarehousesLocationsPreviews
      x-api-path-slug: restwarehouseslocationspreviews-post
      responses:
        200:
          description: OK
      tags:
      - Generate
      - Warehouse
      - Location
      - Preview
      - Saves
      - It
---