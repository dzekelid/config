{
  "info": {
    "name": "AWS Simple Email Service API Create Configuration Set",
    "_postman_id": "270ff9d6-0bf7-4125-bfc0-45edb345cf7b",
    "description": "Creates a configuration set.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Receipt Rule Sets",
      "item": [
        {
          "id": "42fdee60-50ab-4e33-a342-173d7ca74941",
          "name": "cloneReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=CloneReceiptRuleSet?OriginalRuleSetName=OriginalRuleSetName&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a receipt rule set by cloning an existing one."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81cec783-bd07-4936-a29a-505f33d7955b"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Sets",
      "item": [
        {
          "id": "35ab3904-114f-47c2-8bc9-1c1310cb8b27",
          "name": "createConfigurationSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateConfigurationSet?ConfigurationSet=ConfigurationSet",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a configuration set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a99280c4-ef8d-4800-aad9-586d3fd53d6d"
            }
          ]
        }
      ]
    }
  ]
}