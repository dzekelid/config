{
  "info": {
    "name": "GIGANDCROWD Get Config",
    "_postman_id": "f8432e05-ce42-4854-ba29-6c0b5422eea7",
    "description": "Get config.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Admin",
      "item": [
        {
          "id": "53d80ef6-c040-46b4-89e8-dffbebcc9a61",
          "name": "getApiV1AdminParserConfig",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/admin/parser/config",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get admin parser config."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc25d9df-36c1-48b1-92c0-8657131ddbb9"
            }
          ]
        }
      ]
    },
    {
      "name": "Config",
      "item": [
        {
          "id": "167cef3e-32f0-4680-bf6b-def8a10d343f",
          "name": "getApiV1Config",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/Config",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get config."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5c379bd-7926-4dac-a79f-f34a7ae68e89"
            }
          ]
        }
      ]
    }
  ]
}