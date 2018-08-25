---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Save or update a region alias
  version: 1.0.0
  description: Save or update a region alias.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/region/alias/save:
    post:
      summary: Save or update a region alias
      description: Save or update a region alias.
      operationId: Region_SaveRegionAliasByregionAliasSaveCommand
      x-api-path-slug: apiregionaliassave-post
      parameters:
      - in: body
        name: regionAliasSaveCommand
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - Update
      - Region
      - Alias
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