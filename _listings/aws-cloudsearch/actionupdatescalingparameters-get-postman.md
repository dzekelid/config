{
  "info": {
    "name": "AWS CloudSearch Update Scaling Parameters",
    "_postman_id": "459ebf33-6e59-4e21-9e7e-83b970bec158",
    "description": "Configures scaling parameters for a domain.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tags",
      "item": [
        {
          "id": "ee380f17-be42-44c9-b1e9-d9b6d4b34fa5",
          "name": "AddTags",
          "request": {
            "url": "http://example.com/api/?Action=AddTags?Base=Base&InternalException=InternalException&LimitExceededException=LimitExceededException&ValidationException=ValidationException",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches resource tags to an\n Amazon CloudSearch domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31f5ebb9-cde6-4ea0-8e5e-21aa34779c6c"
            }
          ]
        },
        {
          "id": "9852e88e-d4bb-4d82-9350-9b4b4eb95d26",
          "name": "ListTags",
          "request": {
            "url": "http://example.com/api/?Action=ListTags?Base=Base&InternalException=InternalException&LimitExceededException=LimitExceededException&ValidationException=ValidationException",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Displays all of the resource\n tags for an Amazon CloudSearch domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77960378-130e-4115-90fc-f4e3c8d8da50"
            }
          ]
        },
        {
          "id": "8c50f8ce-8369-46ec-b99b-a922ab493eb6",
          "name": "RemoveTags",
          "request": {
            "url": "http://example.com/api/?Action=RemoveTags?Base=Base&InternalException=InternalException&ValidationException=ValidationException",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified resource tags\n from an Amazon ES domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b3e2631-9a40-4cc6-a1ed-54f0c97a577a"
            }
          ]
        }
      ]
    },
    {
      "name": "Suggesters",
      "item": [
        {
          "id": "9de8af73-84b0-42bb-b664-fea123c2ce27",
          "name": "BuildSuggesters",
          "request": {
            "url": "http://example.com/api/?Action=BuildSuggesters?DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Indexes the search suggestions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a82d8296-183a-4068-a1f2-df6f3e6d66ee"
            }
          ]
        },
        {
          "id": "6f92c7be-b024-461f-95b6-189052781663",
          "name": "DefineSuggester",
          "request": {
            "url": "http://example.com/api/?Action=DefineSuggester?DomainName=DomainName&Suggester=Suggester",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures a suggester for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72b6abd1-b8fc-4510-9fa1-722f6f801f66"
            }
          ]
        },
        {
          "id": "de2fe1e6-bb3e-4b85-b6c9-37059651fbb7",
          "name": "DeleteSuggester",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSuggester?DomainName=DomainName&SuggesterName=SuggesterName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a suggester."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7dd4cf7b-dfd8-4294-a224-287fcbfee12e"
            }
          ]
        },
        {
          "id": "a81062eb-b9ab-47ec-bf97-be54f87800b1",
          "name": "DescribeSuggesters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSuggesters?Deployed=Deployed&DomainName=DomainName&SuggesterNames.member.N=SuggesterNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the suggesters configured for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "442c1f47-eb98-4b72-95dc-e5849ba780c4"
            }
          ]
        }
      ]
    },
    {
      "name": "Domains",
      "item": [
        {
          "id": "8a3e874c-a718-4ddf-a1b3-1ec381f06ec4",
          "name": "CreateDomain",
          "request": {
            "url": "http://example.com/api/?Action=CreateDomain?DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04dbc612-8509-4a66-9b2a-f4cb43b2f55f"
            }
          ]
        },
        {
          "id": "b2cb3951-bb45-4d0a-a938-7b7252c235f4",
          "name": "DeleteDomain",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDomain?DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Permanently deletes a search domain and all of its data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "591f2f25-4dcc-430c-8da3-5a0cb86765eb"
            }
          ]
        },
        {
          "id": "ad3788d2-e696-4b08-ae5d-a3f9a3bd2b30",
          "name": "DescribeDomains",
          "request": {
            "url": "http://example.com/api/?Action=DescribeDomains?DomainNames.member.N=DomainNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the search domains owned by this account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3e3ee89-1677-4f37-ba9d-e94069d62ba8"
            }
          ]
        },
        {
          "id": "810c3f3f-2b93-4624-b1cf-97f9fb556b2e",
          "name": "ListDomainNames",
          "request": {
            "url": "http://example.com/api/?Action=ListDomainNames?DomainNames=DomainNames",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all search domains owned by an account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8cc1ef44-8a0e-4691-aa5f-f25cf089cf16"
            }
          ]
        }
      ]
    },
    {
      "name": "Analysis Scheme",
      "item": [
        {
          "id": "62bbbb2c-5d60-45fd-81c0-ea9a081b4d43",
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
              "id": "c0e4f5ba-3046-4475-8ab7-fe81bd8453d2"
            }
          ]
        },
        {
          "id": "924ef017-44b4-4765-9bce-1185df1901a0",
          "name": "DeleteAnalysisScheme",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAnalysisScheme?AnalysisSchemeName=AnalysisSchemeName&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an analysis scheme."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30f2e58a-6324-4b70-9e00-6570ef0b00c3"
            }
          ]
        },
        {
          "id": "0272fb4b-b89f-4ceb-b017-7758d89f840a",
          "name": "DescribeAnalysisSchemes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAnalysisSchemes?AnalysisSchemeNames.member.N=AnalysisSchemeNames.member.N&Deployed=Deployed&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the analysis schemes configured for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f3d1d03-0d21-407e-ab69-b737f06dec5c"
            }
          ]
        }
      ]
    },
    {
      "name": "Expressions",
      "item": [
        {
          "id": "b06c6710-df3c-4199-a810-3a0c96763012",
          "name": "DefineExpression",
          "request": {
            "url": "http://example.com/api/?Action=DefineExpression?DomainName=DomainName&Expression=Expression",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures an Expression  for the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b1c35e9b-1969-4175-bb8a-1185964d0d17"
            }
          ]
        },
        {
          "id": "83ed76b4-2f68-43c6-9fa7-1ae59dd6f62e",
          "name": "DeleteExpression",
          "request": {
            "url": "http://example.com/api/?Action=DeleteExpression?DomainName=DomainName&ExpressionName=ExpressionName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes an \n  Expression\n  from the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f94b03ca-a1e2-4444-8c8f-522f999793a9"
            }
          ]
        },
        {
          "id": "0c27f372-e735-4d39-b7a6-495fe4d01739",
          "name": "DescribeExpressions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeExpressions?Deployed=Deployed&DomainName=DomainName&ExpressionNames.member.N=ExpressionNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the expressions configured for the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ed630c2-cc24-4774-9589-14d150605bd3"
            }
          ]
        }
      ]
    },
    {
      "name": "Index Fields",
      "item": [
        {
          "id": "259dc9f7-5003-445e-99ba-6bc7e1b75ba8",
          "name": "DefineIndexField",
          "request": {
            "url": "http://example.com/api/?Action=DefineIndexField?DomainName=DomainName&IndexField=IndexField",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures an ndexField  for the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92023e77-93f9-464a-b339-95e7bdca238e"
            }
          ]
        },
        {
          "id": "bc0f964a-91fa-4be7-b09a-6d10c367425d",
          "name": "DeleteIndexField",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIndexField?DomainName=DomainName&IndexFieldName=IndexFieldName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes an \n  IndexField\n  from the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a3eac1b-8043-4ff4-8421-4bd557b1ac97"
            }
          ]
        },
        {
          "id": "6099baed-0a7e-4d93-9ac5-5fcf51e9adc1",
          "name": "DescribeIndexFields",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIndexFields?Deployed=Deployed&DomainName=DomainName&FieldNames.member.N=FieldNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the index fields configured for the search domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a49ddc4c-ef62-4d39-8c84-448eea392d94"
            }
          ]
        }
      ]
    },
    {
      "name": "Availability Options",
      "item": [
        {
          "id": "01739a3a-672a-4e5b-b183-4d9678d1783e",
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
              "id": "4ab2a71c-6029-4b5e-bab1-59845db85f98"
            }
          ]
        },
        {
          "id": "99cea443-fdd0-4e91-9380-e92466612194",
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
              "id": "7fc31f43-6012-4ad5-ae04-768119936601"
            }
          ]
        }
      ]
    },
    {
      "name": "Scaling Parameters",
      "item": [
        {
          "id": "d9d4caae-9a74-4cc2-b190-11bfc33742e4",
          "name": "DescribeScalingParameters",
          "request": {
            "url": "http://example.com/api/?Action=DescribeScalingParameters?DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the scaling parameters configured for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01f34a8f-c777-4e6a-901f-1d17bd13b38b"
            }
          ]
        },
        {
          "id": "582cf776-37cc-428f-a219-636e43c7c427",
          "name": "UpdateScalingParameters",
          "request": {
            "url": "http://example.com/api/?Action=UpdateScalingParameters?DomainName=DomainName&ScalingParameters=ScalingParameters",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures scaling parameters for a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82dd8601-72bd-4c43-8072-8bb11b4e61e4"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Access Policies",
      "item": [
        {
          "id": "3d1d3f20-d53f-4d14-b84c-d31822973779",
          "name": "DescribeServiceAccessPolicies",
          "request": {
            "url": "http://example.com/api/?Action=DescribeServiceAccessPolicies?Deployed=Deployed&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about the access policies that control access to the domain's document and search endpoints."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95574b61-9120-4eb5-815b-a769463e29e5"
            }
          ]
        }
      ]
    },
    {
      "name": "Index Documents",
      "item": [
        {
          "id": "ee616841-b34a-4cf0-883c-0b50e5ab7d10",
          "name": "IndexDocuments",
          "request": {
            "url": "http://example.com/api/?Action=IndexDocuments?DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Tells the search domain to start indexing its documents using the latest indexing options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "524ef303-14b9-4de6-9caf-cdde028e8c6c"
            }
          ]
        }
      ]
    }
  ]
}