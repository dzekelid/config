---
name: AWS Storage Gateway Service
x-slug: aws-storage-gateway-service
description: The AWS Storage Gateway service seamlessly enables hybrid storage between
  on-premises storage environments andthe AWS Cloud. It combines a multi-protocol
  storage appliance with highly efficient network connectivity toAmazon cloud storageservices,
  delivering local performance with virtually unlimited scale. Customers use it in
  remote offices and datacenters for hybrid cloud workloads, backup and restore, archive,
  disaster recovery, and tiered storage.The Storage Gateway virtual appliance connects
  seamlessly to your local infrastructure as a file server, as a volume, or as a virtual
  tape library (VTL). This seamless connection makes it simple for organizations to
  augment existing on-premises storage investments with the high scalability, extreme
  durability and low cost of cloud storage.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Config
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/config/master/_listings/aws-storage-gateway-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Storage Gateway Service API - Add Cache
  x-api-slug: actionaddcache-get
  description: Configures one or more gateway local disks as cache for a cached-volume
    gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/config/master/_listings/aws-storage-gateway-service/actionaddcache-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/config/master/_listings/aws-storage-gateway-service/actionaddcache-get-openapi.md
- name: AWS Storage Gateway Service API - Add Upload Buffer
  x-api-slug: actionadduploadbuffer-get
  description: Configures one or more gateway local disks as upload buffer for a specified
    gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Storage-Content-Delivery_AWSStorageGateway.png
  humanURL: https://aws.amazon.com/storagegateway/
  baseURL: :///
  tags: Amazon Web Services, Gateway, Data, Stack Network, API Service Provider, API
    Service Provider, API Provider, Databases, Deployments, Profiles, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/config/master/_listings/aws-storage-gateway-service/actionadduploadbuffer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/config/master/_listings/aws-storage-gateway-service/actionadduploadbuffer-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.step.functions.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.storage.gateway.service.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/storagegateway/latest/APIReference
- type: x-faq
  url: https://aws.amazon.com/storagegateway/faqs/
- type: x-pricing
  url: https://aws.amazon.com/storagegateway/pricing/
- type: x-website
  url: https://aws.amazon.com/storagegateway/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---