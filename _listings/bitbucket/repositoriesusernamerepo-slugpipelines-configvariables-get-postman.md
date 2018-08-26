{
  "info": {
    "name": "Bitbucket Get Repositories Username Repo Slug Pipelines Config Variables",
    "_postman_id": "aa0eea3e-35db-4f01-9eed-4562dda48c39",
    "description": "Get repositories username repo slug pipelines config variables",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "ce69e87b-7998-4df0-9f38-aea1192b5063",
          "name": "getRepositoriesUsernameRepoSlugPipelinesConfigVariables",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bitbucket.org",
              "path": [
                "2.0",
                "repositories/:username/:repo_slug/pipelines_config/variables/"
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
            "description": "Get repositories username repo slug pipelines config variables"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c9048c0-3872-4c3d-a052-4d23f5192d73"
            }
          ]
        }
      ]
    }
  ]
}