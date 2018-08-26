---
swagger: "2.0"
x-collection-name: AWS CloudSearch
x-complete: 1
info:
  title: AWS CloudSearch
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DefineAnalysisScheme:
    get:
      summary: Define Analysis Scheme
      description: Configures an analysis scheme that can be applied to a text or
        text-array field to define language-specific text processing options.
      operationId: DefineAnalysisScheme
      x-api-path-slug: actiondefineanalysisscheme-get
      parameters:
      - in: query
        name: AnalysisScheme
        description: Configuration information for an analysis scheme
        type: string
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Analysis Scheme
  /?Action=DefineExpression:
    get:
      summary: Define Expression
      description: Configures an Expression  for the search domain.
      operationId: DefineExpression
      x-api-path-slug: actiondefineexpression-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: Expression
        description: A named expression that can be evaluated at search time
        type: string
      responses:
        200:
          description: OK
      tags:
      - Expressions
  /?Action=DefineIndexField:
    get:
      summary: Define Index Field
      description: Configures an ndexField  for the search domain.
      operationId: DefineIndexField
      x-api-path-slug: actiondefineindexfield-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: IndexField
        description: The index field and field options you want to configure
        type: string
      responses:
        200:
          description: OK
      tags:
      - Index Fields
  /?Action=DefineSuggester:
    get:
      summary: Define Suggester
      description: Configures a suggester for a domain.
      operationId: DefineSuggester
      x-api-path-slug: actiondefinesuggester-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: Suggester
        description: Configuration information for a search suggester
        type: string
      responses:
        200:
          description: OK
      tags:
      - Suggesters
  /?Action=UpdateAvailabilityOptions:
    get:
      summary: Update Availability Options
      description: Configures the availability options for a domain.
      operationId: UpdateAvailabilityOptions
      x-api-path-slug: actionupdateavailabilityoptions-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: MultiAZ
        description: You expand an existing search domain to a second Availability
          Zone by setting the Multi-AZ option to true
        type: string
      responses:
        200:
          description: OK
      tags:
      - Availability Options
  /?Action=UpdateScalingParameters:
    get:
      summary: Update Scaling Parameters
      description: Configures scaling parameters for a domain.
      operationId: UpdateScalingParameters
      x-api-path-slug: actionupdatescalingparameters-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: ScalingParameters
        description: The desired instance type and desired number of replicas of each
          index partition
        type: string
      responses:
        200:
          description: OK
      tags:
      - Scaling Parameters
  /?Action=UpdateServiceAccessPolicies:
    get:
      summary: Update Service Access Policies
      description: Configures the access rules that control access to the domain's
        document and search endpoints.
      operationId: UpdateServiceAccessPolicies
      x-api-path-slug: actionupdateserviceaccesspolicies-get
      parameters:
      - in: query
        name: AccessPolicies
        description: The access rules you want to configure
        type: string
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Access Policies
---