{
  "info": {
    "name": "Bitbucket Delete Repositories Username Repo Slug Pipelines Config Ssh Known Hosts Known Host Uu",
    "_postman_id": "b22a8d3d-d1d7-4c7f-a767-74d0b942e514",
    "description": "Delete repositories username repo slug pipelines config ssh known hosts known host uu",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "repositories",
      "item": [
        {
          "id": "d5b28160-dfd1-4c66-aa8e-0231e74e2d5f",
          "name": "deleteRepositoriesUsernameRepoSlugPipelinesConfigSshKnownHostsKnownHostUu",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete repositories username repo slug pipelines config ssh known hosts known host uu"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15773e5a-3f22-4b8d-9a5f-6295dd04b3f8"
            }
          ]
        }
      ]
    }
  ]
}