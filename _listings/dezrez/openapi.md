---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/screenz/config/{screenid}:
    get:
      summary: Gets the config back for a screen with a guid that was registered against
        a branch
      description: Gets the config back for a screen with a guid that was registered
        against a branch.
      operationId: Screenz_ConfigByscreenid
      x-api-path-slug: apiscreenzconfigscreenid-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: screenid
      responses:
        200:
          description: OK
      tags:
      - S
      - Config
      - Backa
      - Screen
      - Guid
      - That
      - Was
      - Registered
      - Against
      - Branch
  /api/screenz/registered:
    get:
      summary: Gets the config back for a screen with a guid that was registered against
        a branch
      description: Gets the config back for a screen with a guid that was registered
        against a branch.
      operationId: Screenz_Registered
      x-api-path-slug: apiscreenzregistered-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Config
      - Backa
      - Screen
      - Guid
      - That
      - Was
      - Registered
      - Against
      - Branch
  /api/enlistedfeature/executestep/featureConfiguration/{featureConfigurationId}/step/{stepId}/role/{roleId}:
    post:
      summary: ""
      description: .
      operationId: EnlistedFeature_ExecuteStepByroleIdByfeatureConfigurationIdBystepIdByinvocationDataContractBychosenE
      x-api-path-slug: apienlistedfeatureexecutestepfeatureconfigurationfeatureconfigurationidstepstepidroleroleid-post
      parameters:
      - in: query
        name: chosenExternalProviderId
      - in: path
        name: featureConfigurationId
      - in: body
        name: invocationDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
      - in: path
        name: stepId
      responses:
        200:
          description: OK
      tags:
      - ""
---