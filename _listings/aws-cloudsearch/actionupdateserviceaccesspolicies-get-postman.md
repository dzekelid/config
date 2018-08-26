{
  "info": {
    "name": "AWS CloudSearch Update Service Access Policies",
    "_postman_id": "58fc1112-6f71-4e3f-8baf-87f3e5bb7aa5",
    "description": "Configures the access rules that control access to the domain's document and search endpoints.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tags",
      "item": [
        {
          "id": "0632e533-c64d-4b27-8b5e-e79b62bd43b7",
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
              "id": "d85fb6c7-be37-4fbf-b659-867711769a70"
            }
          ]
        },
        {
          "id": "017738a7-e1e8-4cb7-b2fc-d6fb28d06460",
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
              "id": "76af69fb-ff32-4bf8-9acb-124c50c32b3e"
            }
          ]
        },
        {
          "id": "5a08e819-81cd-4061-888c-b1c7043695d4",
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
              "id": "6dc1c7cb-edd9-44b7-9b38-56b16d519510"
            }
          ]
        }
      ]
    },
    {
      "name": "Suggesters",
      "item": [
        {
          "id": "1d4d5c69-08dd-4c70-9f19-7206196e5f13",
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
              "id": "15f8a5ba-5648-49cc-9837-5b4e8cdc6765"
            }
          ]
        },
        {
          "id": "5627b328-d77c-4b38-8f69-1cc224968221",
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
              "id": "2a8f8c58-8b56-49da-8c62-1b38bd3228bd"
            }
          ]
        },
        {
          "id": "7a20930f-fbdc-4811-81d0-c19f288295b0",
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
              "id": "ea278fe4-9e43-4302-a428-8bb6c140217e"
            }
          ]
        },
        {
          "id": "80416a26-495a-4a4e-9065-6d721bb80a71",
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
              "id": "66f5d49c-1ae2-4085-aac2-d13c8532fc96"
            }
          ]
        }
      ]
    },
    {
      "name": "Domains",
      "item": [
        {
          "id": "8ea5d86a-b752-448d-a870-da90a034c9b0",
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
              "id": "f27dcbd3-5b11-42f0-b2ab-ffa73bc45cac"
            }
          ]
        },
        {
          "id": "e0a5681a-6663-4694-8f32-ba9da7f53533",
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
              "id": "f1330a52-d5c9-4de4-81a4-7be59c63b00f"
            }
          ]
        },
        {
          "id": "77b96da9-9daa-4886-91b2-a39fbf5b1463",
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
              "id": "5bf7c3cf-3701-42f2-8ca6-93eb3d2e343b"
            }
          ]
        },
        {
          "id": "ab227325-2ed9-4df9-99d0-13e4c12b9463",
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
              "id": "31b48dfc-7d7f-415d-84b5-e5fca3770ced"
            }
          ]
        }
      ]
    },
    {
      "name": "Analysis Scheme",
      "item": [
        {
          "id": "37d3409b-c237-4050-9a17-8d5f139d59ac",
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
              "id": "3eccf633-7260-4b54-bac8-b26956d10e94"
            }
          ]
        },
        {
          "id": "c3e97661-23e3-45dd-bbce-82294b69e729",
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
              "id": "ccd03e1e-80e9-4c78-9175-87467e5c1eee"
            }
          ]
        },
        {
          "id": "7195310a-a244-460d-bf3e-5ddaf0aa6daa",
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
              "id": "8e238043-9ab0-4aa2-838c-d240f8e792f3"
            }
          ]
        }
      ]
    },
    {
      "name": "Expressions",
      "item": [
        {
          "id": "18327c7f-7b14-42e0-90b1-97ffc8641c88",
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
              "id": "0dd88fd2-f7da-45a5-8f4d-6733bbac6d71"
            }
          ]
        },
        {
          "id": "7533a046-5ee9-40e9-b674-753a3da10e2c",
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
              "id": "bfbf1074-5f17-490c-8285-af1061d32c07"
            }
          ]
        },
        {
          "id": "af2ece90-2a9a-49a6-89df-08addd8eb349",
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
              "id": "e7f995ec-5e79-48bd-a9de-ee864790bd1f"
            }
          ]
        }
      ]
    },
    {
      "name": "Index Fields",
      "item": [
        {
          "id": "71f9213c-b4dd-4a2d-813e-920429578c2f",
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
              "id": "da685d13-b40d-4045-8670-159f1727cb03"
            }
          ]
        },
        {
          "id": "c46a94d8-3ace-4ef7-ab90-66d216432c99",
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
              "id": "9dbcd5ac-834c-4a4c-923d-d02d0cff9e81"
            }
          ]
        },
        {
          "id": "bd91e41e-edf6-4dc9-a903-180d5a03751f",
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
              "id": "1902a4fb-968f-4a03-87d7-1feeb8f588da"
            }
          ]
        }
      ]
    },
    {
      "name": "Availability Options",
      "item": [
        {
          "id": "c2ac31ab-7454-4484-81c6-e4181225b558",
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
              "id": "f0d8d4ce-91be-4fc5-8224-c924d724b977"
            }
          ]
        },
        {
          "id": "1f77cc6b-6abd-441c-ba21-c02fc253e5dc",
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
              "id": "a58a8e45-6922-48a9-bf9f-3fabc6f0d2fb"
            }
          ]
        }
      ]
    },
    {
      "name": "Scaling Parameters",
      "item": [
        {
          "id": "d75a28c5-8be2-4c5f-8d2a-1bdaa2c82164",
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
              "id": "e3dc6f44-411e-4677-bd52-6247602eab4a"
            }
          ]
        },
        {
          "id": "32429007-0bb8-44d5-9d36-1422f99d0d4b",
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
              "id": "a62225dd-f38c-4c60-862a-79d45bf42b1b"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Access Policies",
      "item": [
        {
          "id": "272848ef-ff72-4bbf-9c82-8f561008ebd2",
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
              "id": "3f0a970b-37f6-4618-aee7-360cfb8512a0"
            }
          ]
        },
        {
          "id": "8a28f966-a6a0-4de9-af16-5d10c32084f1",
          "name": "UpdateServiceAccessPolicies",
          "request": {
            "url": "http://example.com/api/?Action=UpdateServiceAccessPolicies?AccessPolicies=AccessPolicies&DomainName=DomainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures the access rules that control access to the domain's document and search endpoints."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd5cb645-7707-451a-833d-18216d91c23f"
            }
          ]
        }
      ]
    },
    {
      "name": "Index Documents",
      "item": [
        {
          "id": "27782578-73ba-4629-b809-388dbac66d82",
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
              "id": "872ada73-d3e3-49c7-82c3-ef370422d4a6"
            }
          ]
        }
      ]
    }
  ]
}