---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
---