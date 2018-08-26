{
  "info": {
    "name": "Bitbucket Delete Repositories Username Repo Slug Pipelines Config Variables Variable Uu",
    "_postman_id": "b6abfd16-8b5a-43e8-b86d-612a19a83f92",
    "description": "Delete repositories username repo slug pipelines config variables variable uu",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "471c16de-7726-4883-b481-069c75c2b919",
          "name": "deleteRepositoriesUsernameRepoSlugPipelinesConfigVariablesVariableUu",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bitbucket.org",
              "path": [
                "2.0",
                "repositories/:username/:repo_slug/pipelines_config/variables/:variable_uuid"
              ],
              "variable": [
                {
                  "id": "repo_slug",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "variable_uuid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete repositories username repo slug pipelines config variables variable uu"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83e15855-b62b-4741-8ab6-0a0142ce0be1"
            }
          ]
        }
      ]
    }
  ]
}