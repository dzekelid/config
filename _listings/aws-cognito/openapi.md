---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 1
info:
  title: AWS Cognito Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetIdentityPoolConfiguration:
    get:
      summary: Get Identity Pool Configuration
      description: Gets the configuration settings of an identity pool.
      operationId: getIdentityPoolConfiguration
      x-api-path-slug: actiongetidentitypoolconfiguration-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pools
  /?Action=SetIdentityPoolConfiguration:
    get:
      summary: Set Identity Pool Configuration
      description: Sets the necessary configuration for push sync.
      operationId: setIdentityPoolConfiguration
      x-api-path-slug: actionsetidentitypoolconfiguration-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pools
---