---
swagger: "2.0"
x-collection-name: Steem
x-complete: 0
info:
  title: Steem get config
  description: get config
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /get_config:
    get:
      summary: get config
      description: get config
      operationId: get-config
      x-api-path-slug: get-config-get
      responses:
        200:
          description: OK
      tags:
      - Get
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