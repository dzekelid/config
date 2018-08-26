{
  "info": {
    "name": "Bitbucket Delete Repositories Username Repo Slug Pipelines Config Ssh Key Pair",
    "_postman_id": "1f01652a-a97a-4095-8eb3-24453473f35d",
    "description": "Delete repositories username repo slug pipelines config ssh key pair",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "33c154cb-8b28-49fc-99da-5541b4900e08",
          "name": "deleteRepositoriesUsernameRepoSlugPipelinesConfigSshKeyPair",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bitbucket.org",
              "path": [
                "2.0",
                "repositories/:username/:repo_slug/pipelines_config/ssh/key_pair"
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
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete repositories username repo slug pipelines config ssh key pair"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e3e6bac-3364-4adc-9e87-351790c32d3e"
            }
          ]
        }
      ]
    }
  ]
}