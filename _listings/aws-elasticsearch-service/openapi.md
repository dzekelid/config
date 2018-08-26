---
swagger: "2.0"
x-collection-name: AWS Elasticsearch Service
x-complete: 1
info:
  title: AWS Elasticsearch Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2015-01-01/es/domain/{domain_name}/config:
    get:
      summary: Describe Elasticsearch Domain Config
      description: |-
        Displays the configuration of an Amazon ES domain. Use the HTTP GET method
                        with this operation.
      operationId: describeElasticsearchDomainConfig
      x-api-path-slug: 20150101esdomaindomain-nameconfig-get
      parameters:
      - in: query
        name: DomainName
        description: Name of the Amazon ES domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Domains
    post:
      summary: Update Elasticsearch Domain Config
      description: |-
        Modifies the configuration of an Amazon ES domain, such as the instance type and the
                        number of instances. Use the POST HTTP method with this
                        operation.
      operationId: updateElasticsearchDomainConfig
      x-api-path-slug: 20150101esdomaindomain-nameconfig-post
      responses:
        200:
          description: OK
      tags:
      - Domains
---