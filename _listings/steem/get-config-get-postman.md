{
  "info": {
    "name": "Steem get config",
    "_postman_id": "d2d8952f-84db-47d0-b179-052658e0ed01",
    "description": "get config",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "cf19148c-06a5-45de-87a3-cf0c5a55682e",
          "name": "get-config",
          "request": {
            "url": "http://api.steemjs.com/get_config",
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
            "description": "get config"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13acff31-1479-4d8b-aa2e-f299019e9a4c"
            }
          ]
        }
      ]
    }
  ]
}