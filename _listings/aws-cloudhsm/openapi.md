---
swagger: "2.0"
x-collection-name: AWS CloudHSM
x-complete: 1
info:
  title: AWS CloudHSM API
  version: 1.0.0
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
---