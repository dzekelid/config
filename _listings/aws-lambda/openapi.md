---
swagger: "2.0"
x-collection-name: AWS Lambda
x-complete: 1
info:
  title: AWS Lambda API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetFunctionConfiguration:
    get:
      summary: Get Function Configuration
      description: Returns the configuration information of the Lambda function.
      operationId: getFunctionConfiguration
      x-api-path-slug: actiongetfunctionconfiguration-get
      parameters:
      - in: query
        name: FunctionName
        description: The name of the Lambda function for which you want to retrieve
          the configuration information
        type: string
      - in: query
        name: Qualifier
        description: Using this optional parameter you can specify a function version
          or an alias name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
  /?Action=UpdateFunctionConfiguration:
    get:
      summary: Update Function Configuration
      description: Updates the configuration parameters for the specified Lambda function
        by using the values provided in the request.
      operationId: updateFunctionConfiguration
      x-api-path-slug: actionupdatefunctionconfiguration-get
      parameters:
      - in: query
        name: FunctionName
        description: The name of the Lambda function
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
---