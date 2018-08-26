{
  "info": {
    "name": "Bitbucket Get Users Username Pipelines Config Variables Variable Uu",
    "_postman_id": "2f824328-08e1-473f-b9fc-cbf638e2f3bc",
    "description": "Get users username pipelines config variables variable uu",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "d477deac-aa81-4862-b304-b142b476689c",
          "name": "getUsersUsernamePipelinesConfigVariablesVariableUu",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bitbucket.org",
              "path": [
                "2.0",
                "users/:username/pipelines_config/variables/:variable_uuid"
              ],
              "variable": [
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
            "description": "Get users username pipelines config variables variable uu"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5717cfc0-7920-4975-a869-25ba31d257a2"
            }
          ]
        }
      ]
    }
  ]
}