{
  "info": {
    "name": "Bitbucket Get Repositories Username Repo Slug Pipelines Config Ssh Key Pair",
    "_postman_id": "a1fb3601-0ae3-49ec-b108-bf168f8b8054",
    "description": "Retrieve the repository SSH key pair excluding the SSH private key. The private key is a write only field and will never be exposed in the logs or the REST API.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "caa76c51-c0c5-4de0-9a27-6d8a25a84940",
          "name": "getRepositoriesUsernameRepoSlugPipelinesConfigSshKeyPair",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve the repository SSH key pair excluding the SSH private key"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ba720f3-b6ce-45b9-b475-746413417ab8"
            }
          ]
        }
      ]
    }
  ]
}