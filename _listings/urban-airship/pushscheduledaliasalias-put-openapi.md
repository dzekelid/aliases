---
swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 0
info:
  title: Urban Airship Put Push Scheduled Alias Alias
  description: Changes a scheduled notification alias. Aliases for scheduled notifications
    are unique per Urban Airship application, so you might want to hash the aliases
    with a device ID or use some other mechanism to ensure uniqueness. The only other
    limit is that they must be 255 characters or less.
  version: v3
host: go.urbanairship.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /push/scheduled/alias/{alias}:
    put:
      summary: Put Push Scheduled Alias Alias
      description: Changes a scheduled notification alias. Aliases for scheduled notifications
        are unique per Urban Airship application, so you might want to hash the aliases
        with a device ID or use some other mechanism to ensure uniqueness. The only
        other limit is that they must be 255 characters or less.
      operationId: push.scheduled.alias.alias.put
      x-api-path-slug: pushscheduledaliasalias-put
      parameters:
      - in: query
        name: alias
        description: Scheduled notification alias
      - in: path
        name: alias
      - in: query
        name: Content-Type
        description: Content type
      - in: header
        name: Content-Type
        description: Content type
      responses:
        200:
          description: OK
      tags:
      - Push
      - Scheduled
      - Alias
      - Alias
    delete:
      summary: Delete Push Scheduled Alias Alias
      description: Deletes a scheduled notification alias.  If you attempt to schedule
        an aliased scheduled notification with an alias that already exists for your
        application, it will overwrite the existing one.
      operationId: push.scheduled.alias.alias.delete
      x-api-path-slug: pushscheduledaliasalias-delete
      parameters:
      - in: query
        name: alias
        description: Scheduled notification alias
      - in: path
        name: alias
      responses:
        200:
          description: OK
      tags:
      - Push
      - Scheduled
      - Alias
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