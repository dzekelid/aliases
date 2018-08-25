---
swagger: "2.0"
x-collection-name: AWS Key Management Service
x-complete: 0
info:
  title: AWS Key Management Service API Create Alias
  version: 1.0.0
  description: Creates a display name for a customer master key.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateAlias:
    get:
      summary: Create Alias
      description: Creates a display name for a customer master key.
      operationId: createAlias
      x-api-path-slug: actioncreatealias-get
      parameters:
      - in: query
        name: AliasName
        description: String that contains the display name
        type: string
      - in: query
        name: TargetKeyId
        description: An identifier of the key for which you are creating the alias
        type: string
      responses:
        200:
          description: OK
      tags:
      - Aliases
  /?Action=DeleteAlias:
    get:
      summary: Delete Alias
      description: Deletes the specified alias.
      operationId: deleteAlias
      x-api-path-slug: actiondeletealias-get
      parameters:
      - in: query
        name: AliasName
        description: The alias to be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Aliases
  /?Action=ListAliases:
    get:
      summary: List Aliases
      description: Lists all of the key aliases in the account.
      operationId: listAliases
      x-api-path-slug: actionlistaliases-get
      parameters:
      - in: query
        name: Limit
        description: When paginating results, specify the maximum number of items
          to return in the response
        type: string
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only in a
          subsequent request after      you receive a response with truncated results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Aliases
  /?Action=UpdateAlias:
    get:
      summary: Update Alias
      description: Updates an alias to map it to a different key.
      operationId: updateAlias
      x-api-path-slug: actionupdatealias-get
      parameters:
      - in: query
        name: AliasName
        description: String that contains the name of the alias to be modified
        type: string
      - in: query
        name: TargetKeyId
        description: Unique identifier of the customer master key to be mapped to
          the alias
        type: string
      responses:
        200:
          description: OK
      tags:
      - Aliases
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