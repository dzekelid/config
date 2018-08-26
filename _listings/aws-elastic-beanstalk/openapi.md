---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 1
info:
  title: AWS Elastic Beanstalk API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateConfigurationTemplate:
    get:
      summary: Create Configuration Template
      description: Creates a configuration template.
      operationId: createConfigurationTemplate
      x-api-path-slug: actioncreateconfigurationtemplate-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application to associate with this configuration
          template
        type: string
      - in: query
        name: Description
        description: Describes this configuration
        type: string
      - in: query
        name: EnvironmentId
        description: The ID of the environment used with this configuration template
        type: string
      - in: query
        name: OptionSettings.member.N
        description: If specified, AWS Elastic Beanstalk sets the specified configuration
          option to the      requested value
        type: string
      - in: query
        name: SolutionStackName
        description: The name of the solution stack used by this configuration
        type: string
      - in: query
        name: SourceConfiguration
        description: If specified, AWS Elastic Beanstalk uses the configuration values
          from the specified      configuration template to create a new configuration
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Templates
  /?Action=DeleteConfigurationTemplate:
    get:
      summary: Delete Configuration Template
      description: Deletes the specified configuration template.
      operationId: deleteConfigurationTemplate
      x-api-path-slug: actiondeleteconfigurationtemplate-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application to delete the configuration template
          from
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Templates
  /?Action=DeleteEnvironmentConfiguration:
    get:
      summary: Delete Environment Configuration
      description: Deletes the draft configuration associated with the running environment.
      operationId: deleteEnvironmentConfiguration
      x-api-path-slug: actiondeleteenvironmentconfiguration-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application the environment is associated with
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to delete the draft configuration
          from
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=DescribeConfigurationOptions:
    get:
      summary: Describe Configuration Options
      description: |-
        Describes the configuration options that are used in a particular configuration
              template or environment, or that a specified solution stack defines.
      operationId: describeConfigurationOptions
      x-api-path-slug: actiondescribeconfigurationoptions-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application associated with the configuration
          template or environment
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment whose configuration options you want
          to describe
        type: string
      - in: query
        name: Options.member.N
        description: If specified, restricts the descriptions to only the specified
          options
        type: string
      - in: query
        name: SolutionStackName
        description: The name of the solution stack whose configuration options you
          want to      describe
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template whose configuration options
          you want to      describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - ConfigurationOptions
  /?Action=DescribeConfigurationSettings:
    get:
      summary: Describe Configuration Settings
      description: |-
        Returns a description of the settings for the specified configuration set, that is,
              either a configuration template or the configuration set associated with a running
              environment.
      operationId: describeConfigurationSettings
      x-api-path-slug: actiondescribeconfigurationsettings-get
      parameters:
      - in: query
        name: ApplicationName
        description: The application for the environment or configuration template
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to describe
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Settings
  /?Action=UpdateConfigurationTemplate:
    get:
      summary: Update Configuration Template
      description: |-
        Updates the specified configuration template to have the specified properties or
              configuration option values.
      operationId: updateConfigurationTemplate
      x-api-path-slug: actionupdateconfigurationtemplate-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application associated with the configuration
          template to      update
        type: string
      - in: query
        name: Description
        description: A new description for the configuration
        type: string
      - in: query
        name: OptionSettings.member.N
        description: A list of configuration option settings to update with the new
          specified option      value
        type: string
      - in: query
        name: OptionsToRemove.member.N
        description: A list of configuration options to remove from the configuration
          set
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Templates
  /?Action=ValidateConfigurationSettings:
    get:
      summary: Validate Configuration Settings
      description: |-
        Takes a set of configuration settings and either a configuration template or
              environment, and determines whether those values are valid.
      operationId: validateConfigurationSettings
      x-api-path-slug: actionvalidateconfigurationsettings-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application that the configuration template or
          environment belongs      to
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to validate the settings against
        type: string
      - in: query
        name: OptionSettings.member.N
        description: A list of the options and desired values to evaluate
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to validate the settings
          against
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Settings
---