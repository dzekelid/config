---
swagger: "2.0"
x-collection-name: AWS Simple Email Service
x-complete: 0
info:
  title: AWS Simple Email Service API Update Configuration Set Event Destination
  version: 1.0.0
  description: Updates the event destination of a configuration set.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateConfigurationSet:
    get:
      summary: Create Configuration Set
      description: Creates a configuration set.
      operationId: createConfigurationSet
      x-api-path-slug: actioncreateconfigurationset-get
      parameters:
      - in: query
        name: ConfigurationSet
        description: A data structure that contains the name of the configuration
          set
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Sets
  /?Action=CreateConfigurationSetEventDestination:
    get:
      summary: Create Configuration Set Event Destination
      description: Creates a configuration set event destination.
      operationId: createConfigurationSetEventDestination
      x-api-path-slug: actioncreateconfigurationseteventdestination-get
      parameters:
      - in: query
        name: ConfigurationSetName
        description: The name of the configuration set to which to apply the event
          destination
        type: string
      - in: query
        name: EventDestination
        description: An object that describes the AWS service to which Amazon SES
          will publish the email sending events associated with the specified configuration
          set
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Set Event Destination
  /?Action=DeleteConfigurationSet:
    get:
      summary: Delete Configuration Set
      description: Deletes a configuration set.
      operationId: deleteConfigurationSet
      x-api-path-slug: actiondeleteconfigurationset-get
      parameters:
      - in: query
        name: ConfigurationSetName
        description: The name of the configuration set to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Sets
  /?Action=DeleteConfigurationSetEventDestination:
    get:
      summary: Delete Configuration Set Event Destination
      description: Deletes a configuration set event destination.
      operationId: deleteConfigurationSetEventDestination
      x-api-path-slug: actiondeleteconfigurationseteventdestination-get
      parameters:
      - in: query
        name: ConfigurationSetName
        description: The name of the configuration set from which to delete the event
          destination
        type: string
      - in: query
        name: EventDestinationName
        description: The name of the event destination to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Set Event Destination
  /?Action=DescribeConfigurationSet:
    get:
      summary: Describe Configuration Set
      description: Returns the details of the specified configuration set.
      operationId: describeConfigurationSet
      x-api-path-slug: actiondescribeconfigurationset-get
      parameters:
      - in: query
        name: ConfigurationSetAttributeNames.member.N
        description: A list of configuration set attributes to return
        type: string
      - in: query
        name: ConfigurationSetName
        description: The name of the configuration set to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Sets
  /?Action=ListConfigurationSets:
    get:
      summary: List Configuration Sets
      description: Lists the configuration sets associated with your AWS account.
      operationId: listConfigurationSets
      x-api-path-slug: actionlistconfigurationsets-get
      parameters:
      - in: query
        name: MaxItems
        description: The number of configuration sets to return
        type: string
      - in: query
        name: NextToken
        description: A token returned from a previous call to ListConfigurationSets
          to indicate the position of the configuration set in the configuration set
          list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Sets
  /?Action=UpdateConfigurationSetEventDestination:
    get:
      summary: Update Configuration Set Event Destination
      description: Updates the event destination of a configuration set.
      operationId: updateConfigurationSetEventDestination
      x-api-path-slug: actionupdateconfigurationseteventdestination-get
      parameters:
      - in: query
        name: ConfigurationSetName
        description: The name of the configuration set that you want to update
        type: string
      - in: query
        name: EventDestination
        description: The event destination object that you want to apply to the specified
          configuration set
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Set Event Destination
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---