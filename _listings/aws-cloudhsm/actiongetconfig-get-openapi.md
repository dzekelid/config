---
swagger: "2.0"
x-collection-name: AWS CloudHSM
x-complete: 0
info:
  title: AWS CloudHSM API Get Config
  version: 1.0.0
  description: |-
    Gets the configuration files necessary to connect to all high availability partition
          groups the client is associated with.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetConfig:
    get:
      summary: Get Config
      description: |-
        Gets the configuration files necessary to connect to all high availability partition
              groups the client is associated with.
      operationId: getConfig
      x-api-path-slug: actiongetconfig-get
      parameters:
      - in: query
        name: ClientArn
        description: The ARN of the client
        type: string
      - in: query
        name: ClientVersion
        description: The client version
        type: string
      - in: query
        name: HapgList
        description: A list of ARNs that identify the high-availability partition
          groups that are associated      with the client
        type: string
      responses:
        200:
          description: OK
      tags:
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