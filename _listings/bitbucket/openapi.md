---
swagger: "2.0"
x-collection-name: Bitbucket
x-complete: 1
info:
  title: Bitbucket
  description: code-against-the-bitbucket-api-to-automate-simple-tasks-embed-bitbucket-data-into-your-own-site-build-mobile-or-desktop-apps-or-even-add-custom-ui-addons-into-bitbucket-itself-using-the-connect-framework-
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
    put:
      summary: Update Repositories Username Repo Slug Pipelines Config Ssh Key Pair
      description: Create or update the repository SSH key pair. The private key will
        be set as a default SSH identity in your build container.
      operationId: putRepositoriesUsernameRepoSlugPipelinesConfigSshKeyPair
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshkey-pair-put
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: body
        name: _body
        description: The created or updated SSH key pair
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
      - Ssh
      - Key
      - Pair
  /repositories/{username}/{repo_slug}/pipelines_config/ssh/known_hosts/:
    get:
      summary: Get Repositories Username Repo Slug Pipelines Config Ssh Known Hosts
      description: Get repositories username repo slug pipelines config ssh known
        hosts
      operationId: getRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHosts
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshknown-hosts-get
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
      - Known
      - Hosts
    post:
      summary: Add Repositories Username Repo Slug Pipelines Config Ssh Known Hosts
      description: Post repositories username repo slug pipelines config ssh known
        hosts
      operationId: postRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHosts
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshknown-hosts-post
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: body
        name: _body
        description: The known host to create
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
      - Ssh
      - Known
      - Hosts
  /repositories/{username}/{repo_slug}/pipelines_config/ssh/known_hosts/{known_host_uuid}:
    delete:
      summary: Delete Repositories Username Repo Slug Pipelines Config Ssh Known Hosts
        Known Host Uu
      description: Delete repositories username repo slug pipelines config ssh known
        hosts known host uu
      operationId: deleteRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHostsKnownHostUu
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshknown-hostsknown-host-uuid-delete
      parameters:
      - in: path
        name: known_host_uuid
        description: The UUID of the known host to delete
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
      - Known
      - Hosts
      - Known
      - Host
      - Uu
    get:
      summary: Get Repositories Username Repo Slug Pipelines Config Ssh Known Hosts
        Known Host Uu
      description: Get repositories username repo slug pipelines config ssh known
        hosts known host uu
      operationId: getRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHostsKnownHostUu
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshknown-hostsknown-host-uuid-get
      parameters:
      - in: path
        name: known_host_uuid
        description: The UUID of the known host to retrieve
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
      - Known
      - Hosts
      - Known
      - Host
      - Uu
    put:
      summary: Update Repositories Username Repo Slug Pipelines Config Ssh Known Hosts
        Known Host Uu
      description: Put repositories username repo slug pipelines config ssh known
        hosts known host uu
      operationId: putRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHostsKnownHostUu
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configsshknown-hostsknown-host-uuid-put
      parameters:
      - in: path
        name: known_host_uuid
        description: The UUID of the known host to update
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: body
        name: _body
        description: The updated known host
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
      - Ssh
      - Known
      - Hosts
      - Known
      - Host
      - Uu
  /repositories/{username}/{repo_slug}/pipelines_config/variables/:
    get:
      summary: Get Repositories Username Repo Slug Pipelines Config Variables
      description: Get repositories username repo slug pipelines config variables
      operationId: getRepositoriesUsernameRepoSlugPipelinesConfigVariables
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configvariables-get
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
      - Variables
    post:
      summary: Add Repositories Username Repo Slug Pipelines Config Variables
      description: Post repositories username repo slug pipelines config variables
      operationId: postRepositoriesUsernameRepoSlugPipelinesConfigVariables
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configvariables-post
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: body
        name: _body
        description: The variable to create
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
      - Variables
  /repositories/{username}/{repo_slug}/pipelines_config/variables/{variable_uuid}:
    delete:
      summary: Delete Repositories Username Repo Slug Pipelines Config Variables Variable
        Uu
      description: Delete repositories username repo slug pipelines config variables
        variable uu
      operationId: deleteRepositoriesUsernameRepoSlugPipelinesConfigVariablesVariableUu
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configvariablesvariable-uuid-delete
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to delete
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
      - Variables
      - Variable
      - Uu
    get:
      summary: Get Repositories Username Repo Slug Pipelines Config Variables Variable
        Uu
      description: Get repositories username repo slug pipelines config variables
        variable uu
      operationId: getRepositoriesUsernameRepoSlugPipelinesConfigVariablesVariableUu
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configvariablesvariable-uuid-get
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to retrieve
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
      - Variables
      - Variable
      - Uu
    put:
      summary: Update Repositories Username Repo Slug Pipelines Config Variables Variable
        Uu
      description: Put repositories username repo slug pipelines config variables
        variable uu
      operationId: putRepositoriesUsernameRepoSlugPipelinesConfigVariablesVariableUu
      x-api-path-slug: repositoriesusernamerepo-slugpipelines-configvariablesvariable-uuid-put
      parameters:
      - in: path
        name: repo_slug
        description: The repository
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to update
      - in: body
        name: _body
        description: The updated variable
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
      - Variables
      - Variable
      - Uu
  /teams/{username}/pipelines_config/variables/:
    get:
      summary: Get Teams Username Pipelines Config Variables
      description: Get teams username pipelines config variables
      operationId: getTeamsUsernamePipelinesConfigVariables
      x-api-path-slug: teamsusernamepipelines-configvariables-get
      parameters:
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Username
      - Pipelines
      - Config
      - Variables
    post:
      summary: Add Teams Username Pipelines Config Variables
      description: Post teams username pipelines config variables
      operationId: postTeamsUsernamePipelinesConfigVariables
      x-api-path-slug: teamsusernamepipelines-configvariables-post
      parameters:
      - in: path
        name: username
        description: The account
      - in: body
        name: _body
        description: The variable to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Username
      - Pipelines
      - Config
      - Variables
  /teams/{username}/pipelines_config/variables/{variable_uuid}:
    delete:
      summary: Delete Teams Username Pipelines Config Variables Variable Uu
      description: Delete teams username pipelines config variables variable uu
      operationId: deleteTeamsUsernamePipelinesConfigVariablesVariableUu
      x-api-path-slug: teamsusernamepipelines-configvariablesvariable-uuid-delete
      parameters:
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to delete
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Username
      - Pipelines
      - Config
      - Variables
      - Variable
      - Uu
    get:
      summary: Get Teams Username Pipelines Config Variables Variable Uu
      description: Get teams username pipelines config variables variable uu
      operationId: getTeamsUsernamePipelinesConfigVariablesVariableUu
      x-api-path-slug: teamsusernamepipelines-configvariablesvariable-uuid-get
      parameters:
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to retrieve
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Username
      - Pipelines
      - Config
      - Variables
      - Variable
      - Uu
    put:
      summary: Update Teams Username Pipelines Config Variables Variable Uu
      description: Put teams username pipelines config variables variable uu
      operationId: putTeamsUsernamePipelinesConfigVariablesVariableUu
      x-api-path-slug: teamsusernamepipelines-configvariablesvariable-uuid-put
      parameters:
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable
      - in: body
        name: _body
        description: The updated variable
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Username
      - Pipelines
      - Config
      - Variables
      - Variable
      - Uu
  /users/{username}/pipelines_config/variables/:
    get:
      summary: Get Users Username Pipelines Config Variables
      description: Get users username pipelines config variables
      operationId: getUsersUsernamePipelinesConfigVariables
      x-api-path-slug: usersusernamepipelines-configvariables-get
      parameters:
      - in: path
        name: username
        description: The account
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
      - Pipelines
      - Config
      - Variables
    post:
      summary: Add Users Username Pipelines Config Variables
      description: Post users username pipelines config variables
      operationId: postUsersUsernamePipelinesConfigVariables
      x-api-path-slug: usersusernamepipelines-configvariables-post
      parameters:
      - in: path
        name: username
        description: The account
      - in: body
        name: _body
        description: The variable to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
      - Pipelines
      - Config
      - Variables
  /users/{username}/pipelines_config/variables/{variable_uuid}:
    delete:
      summary: Delete Users Username Pipelines Config Variables Variable Uu
      description: Delete users username pipelines config variables variable uu
      operationId: deleteUsersUsernamePipelinesConfigVariablesVariableUu
      x-api-path-slug: usersusernamepipelines-configvariablesvariable-uuid-delete
      parameters:
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to delete
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
      - Pipelines
      - Config
      - Variables
      - Variable
      - Uu
    get:
      summary: Get Users Username Pipelines Config Variables Variable Uu
      description: Get users username pipelines config variables variable uu
      operationId: getUsersUsernamePipelinesConfigVariablesVariableUu
      x-api-path-slug: usersusernamepipelines-configvariablesvariable-uuid-get
      parameters:
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable to retrieve
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
      - Pipelines
      - Config
      - Variables
      - Variable
      - Uu
    put:
      summary: Update Users Username Pipelines Config Variables Variable Uu
      description: Put users username pipelines config variables variable uu
      operationId: putUsersUsernamePipelinesConfigVariablesVariableUu
      x-api-path-slug: usersusernamepipelines-configvariablesvariable-uuid-put
      parameters:
      - in: path
        name: username
        description: The account
      - in: path
        name: variable_uuid
        description: The UUID of the variable
      - in: body
        name: _body
        description: The updated variable
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
      - Pipelines
      - Config
      - Variables
      - Variable
      - Uu
---