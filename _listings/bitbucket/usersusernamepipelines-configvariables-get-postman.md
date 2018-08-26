{
  "info": {
    "name": "Bitbucket Get Users Username Pipelines Config Variables",
    "_postman_id": "a7c591a1-2a44-47dc-9368-84d0effba9bf",
    "description": "Get users username pipelines config variables",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "e336597d-3bb1-4251-ae46-cf7191aa48e2",
          "name": "getUsersUsernamePipelinesConfigVariables",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bitbucket.org",
              "path": [
                "2.0",
                "users/:username/pipelines_config/variables/"
              ],
              "variable": [
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
            "description": "Get users username pipelines config variables"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6530e5b-6ef5-421f-a44b-7706af033d1a"
            }
          ]
        }
      ]
    }
  ]
}