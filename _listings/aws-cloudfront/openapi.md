---
swagger: "2.0"
x-collection-name: AWS CloudFront
x-complete: 1
info:
  title: AWS CloudFront API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetCloudFrontOriginAccessIdentityConfig:
    get:
      summary: Get Cloud Front Origin Access Identity Config
      description: Get the configuration information about an origin access identity.
      operationId: getCloudFrontOriginAccessIdentityConfig
      x-api-path-slug: actiongetcloudfrontoriginaccessidentityconfig-get
      parameters:
      - in: query
        name: AutoPlacement
        description: This is enabled by default
        type: string
      - in: query
        name: AvailabilityZone
        description: The Availability Zone for the Dedicated Hosts
        type: string
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure idempotency
          of the request
        type: string
      - in: query
        name: Id
        description: The identitys ID
        type: string
      - in: query
        name: InstanceType
        description: Specify the instance type that you want your Dedicated Hosts
          to be configured for
        type: string
      - in: query
        name: Quantity
        description: The number of Dedicated Hosts you want to allocate to your account
          with these            parameters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloud
      - Front
      - Origin
      - Access
      - Identity
      - Config
  /?Action=GetDistributionConfig:
    get:
      summary: Get Distribution Config
      description: Get the configuration information about a distribution.
      operationId: getDistributionConfig
      x-api-path-slug: actiongetdistributionconfig-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: Id
        description: The distributions ID
        type: string
      - in: query
        name: MaxDuration
        description: This is the maximum duration of the reservation youd like to
          purchase, specified            in seconds
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: MinDuration
        description: This is the minimum duration of the reservation youd like to
          purchase, specified            in seconds
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      - in: query
        name: OfferingId
        description: The ID of the reservation offering
        type: string
      responses:
        200:
          description: OK
      tags:
      - Distribution
      - Config
  /?Action=GetStreamingDistributionConfig:
    get:
      summary: Get Streaming Distribution Config
      description: Get the configuration information about a streaming distribution.
      operationId: getStreamingDistributionConfig
      x-api-path-slug: actiongetstreamingdistributionconfig-get
      parameters:
      - in: query
        name: AutoPlacement
        description: Specify whether to enable or disable auto-placement
        type: string
      - in: query
        name: HostId.N
        description: The host IDs of the Dedicated Hosts you want to modify
        type: string
      - in: query
        name: Id
        description: The streaming distributions ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Streaming
      - Distribution
      - Config
---