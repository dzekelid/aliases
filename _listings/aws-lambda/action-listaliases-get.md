---
swagger: "2.0"
info:
  title: AWS Lambda API List Aliases
  version: 1.0.0
  description: Returns list of aliases created for a Lambda function.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListAliases:
    get:
      summary: ' List Aliases '
      description: Returns list of aliases created for a Lambda function
      operationId: listAliases
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
      - aliases
definitions: []
x-collection-name: AWS Lambda
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