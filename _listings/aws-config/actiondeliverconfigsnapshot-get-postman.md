{
  "info": {
    "name": "AWS Config API Deliver Config Snapshot",
    "_postman_id": "f60378d2-5e68-4a00-8451-26f5014138c3",
    "description": "Schedules delivery of a configuration snapshot to the Amazon S3 bucket in the specified delivery channel.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Configuration Rules",
      "item": [
        {
          "id": "74d75672-16de-4ca4-a3b2-d0ee66878995",
          "name": "deleteConfigRule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConfigRule?ConfigRuleName=ConfigRuleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified AWS Config rule and all of its evaluation results."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73c82e5c-646f-40da-a2ed-353436076a9b"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Recorders",
      "item": [
        {
          "id": "ec217224-e372-4898-bec0-881080c52886",
          "name": "deleteConfigurationRecorder",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConfigurationRecorder?ConfigurationRecorderName=ConfigurationRecorderName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the configuration recorder."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c324ba0f-f427-47ee-8e3d-ceff45afe5e6"
            }
          ]
        }
      ]
    },
    {
      "name": "Delivery Channels",
      "item": [
        {
          "id": "84f1becc-d592-4195-bff2-3e69da0bf09c",
          "name": "deleteDeliveryChannel",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDeliveryChannel?DeliveryChannelName=DeliveryChannelName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the delivery channel."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96520db9-277b-4b05-89b2-51ca43f255d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Evaluations",
      "item": [
        {
          "id": "1da98296-9533-4272-b4ba-391701233a83",
          "name": "deleteEvaluationResults",
          "request": {
            "url": "http://example.com/api/?Action=DeleteEvaluationResults?ConfigRuleName=ConfigRuleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the evaluation results for the specified Config rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d993e63e-72c4-4bed-9ed3-ec71b3db4304"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Snapshot",
      "item": [
        {
          "id": "e19731ba-38e3-4a43-bcbc-a0c2611181df",
          "name": "deliverConfigSnapshot",
          "request": {
            "url": "http://example.com/api/?Action=DeliverConfigSnapshot?deliveryChannelName=deliveryChannelName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Schedules delivery of a configuration snapshot to the Amazon S3 bucket in the specified delivery channel."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09c27537-450e-492d-bc4f-9ed58035e4df"
            }
          ]
        }
      ]
    }
  ]
}