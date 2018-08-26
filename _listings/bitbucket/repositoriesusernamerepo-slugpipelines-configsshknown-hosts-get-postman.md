{
  "info": {
    "name": "Bitbucket Get Repositories Username Repo Slug Pipelines Config Ssh Known Hosts",
    "_postman_id": "ec4540bb-6f22-46b8-9d24-1acd5cc546b2",
    "description": "Get repositories username repo slug pipelines config ssh known hosts",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "9b7a5cf9-65b3-464a-a5f1-9b42e65ef16f",
          "name": "getRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHosts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bitbucket.org",
              "path": [
                "2.0",
                "repositories/:username/:repo_slug/pipelines_config/ssh/known_hosts/"
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
            "description": "Get repositories username repo slug pipelines config ssh known hosts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26131617-8a5e-4508-bf37-c6cf2b2d435f"
            }
          ]
        }
      ]
    }
  ]
}