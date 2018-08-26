{
  "info": {
    "name": "Bitbucket Get Repositories Username Repo Slug Pipelines Config Variables Variable Uu",
    "_postman_id": "6d4d6e99-e8ca-4d07-95b9-fd435ddf4671",
    "description": "Get repositories username repo slug pipelines config variables variable uu",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "67f8d13b-d8b2-4a06-aeb2-1a4cfcef374d",
          "name": "getRepositoriesUsernameRepoSlugPipelinesConfigVariablesVariableUu",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get repositories username repo slug pipelines config variables variable uu"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c13ef2b4-baec-42ea-a43a-e16e54690438"
            }
          ]
        }
      ]
    }
  ]
}