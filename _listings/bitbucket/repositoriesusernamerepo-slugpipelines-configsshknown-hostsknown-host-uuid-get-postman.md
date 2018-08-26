{
  "info": {
    "name": "Bitbucket Get Repositories Username Repo Slug Pipelines Config Ssh Known Hosts Known Host Uu",
    "_postman_id": "e4f57203-5a1e-41b9-b78a-300941e2ac1d",
    "description": "Get repositories username repo slug pipelines config ssh known hosts known host uu",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "bed64e48-b04f-4dca-83f6-de38a7cba592",
          "name": "getRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHostsKnownHostUu",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bitbucket.org",
              "path": [
                "2.0",
                "repositories/:username/:repo_slug/pipelines_config/ssh/known_hosts/:known_host_uuid"
              ],
              "variable": [
                {
                  "id": "known_host_uuid",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Get repositories username repo slug pipelines config ssh known hosts known host uu"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83f29b5e-fbf1-4907-9fd1-875093f3e544"
            }
          ]
        }
      ]
    }
  ]
}