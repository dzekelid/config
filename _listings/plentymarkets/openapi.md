---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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
---