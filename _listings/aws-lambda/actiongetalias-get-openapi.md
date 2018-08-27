---
swagger: "2.0"
x-collection-name: AWS Lambda
x-complete: 0
info:
  title: AWS Lambda API Get Alias
  version: 1.0.0
  description: "Returns the specified alias information such as the alias ARN, description,
    and function version it \n      is pointing to."
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
      description: Creates an alias that points to the specified Lambda function version.
      operationId: createAlias
      x-api-path-slug: actioncreatealias-get
      parameters:
      - in: query
        name: FunctionName
        description: Name of the Lambda function for which you want to create an alias
        type: string
      responses:
        200:
          description: OK
      tags:
      - Aliases
  /?Action=DeleteAlias:
    get:
      summary: Delete Alias
      description: Deletes the specified Lambda function alias.
      operationId: deleteAlias
      x-api-path-slug: actiondeletealias-get
      parameters:
      - in: query
        name: FunctionName
        description: The Lambda function name for which the alias is created
        type: string
      - in: query
        name: Name
        description: Name of the alias to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Aliases
  /?Action=GetAlias:
    get:
      summary: Get Alias
      description: "Returns the specified alias information such as the alias ARN,
        description, and function version it \n      is pointing to."
      operationId: getAlias
      x-api-path-slug: actiongetalias-get
      parameters:
      - in: query
        name: FunctionName
        description: Function name for which the alias is created
        type: string
      - in: query
        name: Name
        description: Name of the alias for which you want to retrieve information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Aliases
  /?Action=ListAliases:
    get:
      summary: List Aliases
      description: Returns list of aliases created for a Lambda function.
      operationId: listAliases
      x-api-path-slug: actionlistaliases-get
      parameters:
      - in: query
        name: FunctionName
        description: Lambda function name for which the alias is created
        type: string
      - in: query
        name: FunctionVersion
        description: If you specify this optional parameter, the API returns only
          the aliases that are pointing to the specific Lambda function version, otherwise
          the API returns all of the aliases created for the Lambda function
        type: string
      - in: query
        name: Marker
        description: Optional string
        type: string
      - in: query
        name: MaxItems
        description: Optional integer
        type: string
      responses:
        200:
          description: OK
      tags:
      - Aliases
  /?Action=UpdateAlias:
    get:
      summary: Update Alias
      description: Using this API you can update the function version to which the
        alias points and the alias description.
      operationId: updateAlias
      x-api-path-slug: actionupdatealias-get
      parameters:
      - in: query
        name: FunctionName
        description: The function name for which the alias is created
        type: string
      - in: query
        name: Name
        description: The alias name
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