---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 0
info:
  title: Bitbucket Get Repositories Username Repo Slug Pipelines Config Ssh Key Pair
  description: Retrieve the repository SSH key pair excluding the SSH private key.
    The private key is a write only field and will never be exposed in the logs or
    the REST API.
  termsOfService: https://www.atlassian.com/legal/customer-agreement
  contact:
    name: Bitbucket Support
    url: https://support.atlassian.com/bitbucket
    email: support@bitbucket.org
  version: 1.0.0
host: api.bitbucket.org
basePath: /2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /repositories/{username}/{repo_slug}/pipelines_config:
    get:
      summary: Get Repositories Username Repo Slug Pipelines Config
      description: Get repositories username repo slug pipelines config
      operationId: getRepositoriesUsernameRepoSlugPipelinesConfig
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-config-get
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pipelines
      - Config
    put:
      summary: Update Repositories Username Repo Slug Pipelines Config
      description: Update the pipelines configuration for a repository.
      operationId: putRepositoriesUsernameRepoSlugPipelinesConfig
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-config-put
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: body
        name: _body
        description: The updated repository pipelines configuration
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pipelines
      - Config
  /repositories/{username}/{repo_slug}/pipelines_config/ssh/key_pair:
    delete:
      summary: Delete Repositories Username Repo Slug Pipelines Config Ssh Key Pair
      description: Delete repositories username repo slug pipelines config ssh key
        pair
      operationId: deleteRepositoriesUsernameRepoSlugPipelinesConfigSshKeyPair
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshkey-pair-delete
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pipelines
      - Config
      - Ssh
      - Key
      - Pair
    get:
      summary: Get Repositories Username Repo Slug Pipelines Config Ssh Key Pair
      description: Retrieve the repository SSH key pair excluding the SSH private
        key. The private key is a write only field and will never be exposed in the
        logs or the REST API.
      operationId: getRepositoriesUsernameRepoSlugPipelinesConfigSshKeyPair
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshkey-pair-get
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Repositories
      - Username
      - Repo
      - Slug
      - Pipelines
      - Config
      - Ssh
      - Key
      - Pair
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