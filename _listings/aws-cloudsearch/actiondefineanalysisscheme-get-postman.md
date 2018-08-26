{
  "info": {
    "name": "AWS CloudSearch Define Analysis Scheme",
    "_postman_id": "0b0a13e8-f1f1-4b0e-84fd-1ba52b8a917e",
    "description": "Configures an analysis scheme that can be applied to a text or text-array field to define language-specific text processing options.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Analysis Scheme",
      "item": [
        {
          "id": "833749ec-f4a6-42dc-b8aa-ad218a123d88",
          "name": "DefineAnalysisScheme",
          "request": {
            "url": "http://example.com/api/?Action=DefineAnalysisScheme?AnalysisScheme=AnalysisScheme&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures an analysis scheme that can be applied to a text or text-array field to define language-specific text processing options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7064b476-aba3-4f37-9b46-2545bbd1d6af"
            }
          ]
        }
      ]
    }
  ]
}