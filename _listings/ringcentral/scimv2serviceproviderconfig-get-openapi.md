---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral get service provider config
  description: ""
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /scim/v2/ServiceProviderConfig:
    get:
      summary: get service provider config
      description: ""
      operationId: getServiceProviderConfig
      x-api-path-slug: scimv2serviceproviderconfig-get
      responses:
        2:
          description: Successful response
        200:
          description: OK
      tags:
      - Get
      - Service
      - Provider
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