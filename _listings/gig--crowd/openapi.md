---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/admin/parser/config:
    get:
      summary: Get Admin Parser Config
      description: Get admin parser config.
      operationId: getApiV1AdminParserConfig
      x-api-path-slug: apiv1adminparserconfig-get
      parameters:
      - in: header
        name: Authorization
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Parser
      - Config
  /api/v1/Config:
    get:
      summary: Get Config
      description: Get config.
      operationId: getApiV1Config
      x-api-path-slug: apiv1config-get
      responses:
        200:
          description: OK
      tags:
      - Config
---