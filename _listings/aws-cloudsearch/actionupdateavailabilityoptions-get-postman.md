{
  "info": {
    "name": "AWS CloudSearch Update Availability Options",
    "_postman_id": "d507837e-b2c4-4662-a0b1-90a606b6a96a",
    "description": "Configures the availability options for a domain.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Availability Options",
      "item": [
        {
          "id": "8c8af210-3ecc-4d56-87a4-d894a866e6f6",
          "name": "DescribeAvailabilityOptions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAvailabilityOptions?Deployed=Deployed&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the availability options configured for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1eef3a66-8ebf-44ce-8be5-91fff62e5f4a"
            }
          ]
        },
        {
          "id": "92becc41-3394-4179-b88b-cd76521f92ec",
          "name": "UpdateAvailabilityOptions",
          "request": {
            "url": "http://example.com/api/?Action=UpdateAvailabilityOptions?DomainName=DomainName&MultiAZ=MultiAZ",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures the availability options for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "70278257-98ca-422d-aa5e-979eefb73e14"
            }
          ]
        }
      ]
    }
  ]
}