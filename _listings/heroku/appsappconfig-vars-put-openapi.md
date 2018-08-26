---
swagger: "2.0"
x-collection-name: Heroku
x-complete: 0
info:
  title: Heroku Put Application Config Variables
  description: Put application config variables.
  version: "1"
host: api.heroku.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps/{app}/config_vars:
    parameters:
      summary: Parameters Application Config Variables
      description: Parameters application config variables.
      operationId: parametersAppsAppConfigVars
      x-api-path-slug: appsappconfig-vars-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Config
      - Variables
    get:
      summary: Get Application Config Variables
      description: Get application config variables.
      operationId: getAppsAppConfigVars
      x-api-path-slug: appsappconfig-vars-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Application
      - Config
      - Variables
    put:
      summary: Put Application Config Variables
      description: Put application config variables.
      operationId: putAppsAppConfigVars
      x-api-path-slug: appsappconfig-vars-put
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Put
      - Application
      - Config
      - Variables
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