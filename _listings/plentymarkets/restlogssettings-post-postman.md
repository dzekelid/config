{
  "info": {
    "name": "Plentymarkets Save config.",
    "_postman_id": "5c2e128d-d0ec-48d9-b878-4964075b3996",
    "description": "Save config..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Show",
      "item": [
        {
          "id": "c7e1867e-b8a2-4d3a-8157-d088cc2887ab",
          "name": "getRestLogsSettings",
          "request": {
            "url": "http://example.com/rest/logs/settings",
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
            "description": "Show config.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93182e3d-ea0a-4389-94da-153cebd2042b"
            }
          ]
        }
      ]
    },
    {
      "name": "Save",
      "item": [
        {
          "id": "db3457b3-cb87-4089-abc8-74fff908171a",
          "name": "postRestLogsSettings",
          "request": {
            "url": "http://example.com/rest/logs/settings",
            "method": "POST",
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
            "description": "Save config.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c32ca136-bf00-44ed-9879-a45c80e21317"
            }
          ]
        }
      ]
    }
  ]
}