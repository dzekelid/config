{
  "info": {
    "name": "Bitbucket Delete Users Username Pipelines Config Variables Variable Uu",
    "_postman_id": "b98c860e-224e-4853-8744-f8974179956b",
    "description": "Delete users username pipelines config variables variable uu",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "users",
      "item": [
        {
          "id": "58706bb7-0116-48c8-a163-0f07cfbc0b53",
          "name": "deleteUsersUsernamePipelinesConfigVariablesVariableUu",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete users username pipelines config variables variable uu"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5042c68-d332-4926-9c5b-c19a877962ac"
            }
          ]
        }
      ]
    }
  ]
}