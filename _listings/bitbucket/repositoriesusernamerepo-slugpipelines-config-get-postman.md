{
  "info": {
    "name": "Bitbucket Get Repositories Username Repo Slug Pipelines Config",
    "_postman_id": "d90244b4-e3dd-45b9-9be9-1cb6cd11886d",
    "description": "Get repositories username repo slug pipelines config",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "1c32f308-c093-47f9-a238-8bcc59e7c95e",
          "name": "getRepositoriesUsernameRepoSlugPipelinesConfig",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bitbucket.org",
              "path": [
                "2.0",
                "repositories/:username/:repo_slug/pipelines_config"
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
            "description": "Get repositories username repo slug pipelines config"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5621c5b3-9322-458f-8901-ea5773998fc0"
            }
          ]
        }
      ]
    }
  ]
}