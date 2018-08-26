---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Save config.
  description: Save config..
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
  /rest/logs/settings:
    get:
      summary: Show config.
      description: Show config..
      operationId: getRestLogsSettings
      x-api-path-slug: restlogssettings-get
      responses:
        200:
          description: OK
      tags:
      - Show
      - Config
    post:
      summary: Save config.
      description: Save config..
      operationId: postRestLogsSettings
      x-api-path-slug: restlogssettings-post
      responses:
        200:
          description: OK
      tags:
      - Save
      - Config
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