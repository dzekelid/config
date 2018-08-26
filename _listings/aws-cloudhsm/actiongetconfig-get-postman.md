{
  "info": {
    "name": "AWS CloudHSM API Get Config",
    "_postman_id": "7b22a51c-f539-479c-a865-4990d27bd455",
    "description": "Gets the configuration files necessary to connect to all high availability partition\n      groups the client is associated with.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tags",
      "item": [
        {
          "id": "bbaa53fa-05f6-4b47-a633-f84e81d6a51c",
          "name": "addTagsToResource",
          "request": {
            "url": "http://example.com/api/?Action=AddTagsToResource?ResourceArn=ResourceArn&TagList=TagList",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or overwrites one or more tags for the specified AWS CloudHSM resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "46e78f25-3b0f-4026-b106-dcf161a6eb82"
            }
          ]
        }
      ]
    },
    {
      "name": "High-Availability Partition Group",
      "item": [
        {
          "id": "b2ec3e3a-e539-4bcd-85ad-75c18114c500",
          "name": "createHapg",
          "request": {
            "url": "http://example.com/api/?Action=CreateHapg?Label=Label",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a high-availability partition group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acdd6976-9267-426a-b568-70409818a231"
            }
          ]
        },
        {
          "id": "e0a1fef5-594d-45e5-b7b0-9486c7420a70",
          "name": "deleteHapg",
          "request": {
            "url": "http://example.com/api/?Action=DeleteHapg?HapgArn=HapgArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a high-availability partition group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74ad8161-63a7-445c-9766-0ebcf1e14e7a"
            }
          ]
        },
        {
          "id": "751a7470-9807-4fb3-8472-d4c950a0e1ce",
          "name": "describeHapg",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHapg?HapgArn=HapgArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about a high-availability partition group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f1efc9e-2643-4721-8ace-3c9432137e13"
            }
          ]
        }
      ]
    },
    {
      "name": "HSM Instances",
      "item": [
        {
          "id": "d3509c60-4e5d-4649-8785-b8a436a2afdc",
          "name": "createHsm",
          "request": {
            "url": "http://example.com/api/?Action=CreateHsm?ClientToken=ClientToken&EniIp=EniIp&ExternalId=ExternalId&IamRoleArn=IamRoleArn&SshKey=SshKey&SubnetId=SubnetId&SubscriptionType=SubscriptionType&SyslogIp=SyslogIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an uninitialized HSM instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2ff471b-5b2f-421e-8bd1-d1f70d1ce268"
            }
          ]
        },
        {
          "id": "250b53a8-4f50-41e7-bdf1-e7420c4f7973",
          "name": "deleteHsm",
          "request": {
            "url": "http://example.com/api/?Action=DeleteHsm?HsmArn=HsmArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an HSM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "24ad7f5d-af87-40da-87df-80034c63aaf7"
            }
          ]
        },
        {
          "id": "7a1f055b-3fe2-4b7a-a67b-634c91465c55",
          "name": "describeHsm",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHsm?HsmArn=HsmArn&HsmSerialNumber=HsmSerialNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about an HSM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96fac472-8b22-44b3-b72c-b3bf383a97ce"
            }
          ]
        }
      ]
    },
    {
      "name": "Luna Clients",
      "item": [
        {
          "id": "81173061-2dfb-4d6b-9872-486e149d1a9f",
          "name": "createLunaClient",
          "request": {
            "url": "http://example.com/api/?Action=CreateLunaClient?Certificate=Certificate&Label=Label",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an HSM client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89ad064a-3cd1-44f3-865a-1df290608839"
            }
          ]
        },
        {
          "id": "f8d21298-1dab-4fa3-862b-28d323189f63",
          "name": "deleteLunaClient",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLunaClient?ClientArn=ClientArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d691b211-3e22-4c7d-812f-75cb484c73cd"
            }
          ]
        },
        {
          "id": "f91142c2-bf05-4b93-91fb-f3ef16e3c490",
          "name": "describeLunaClient",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLunaClient?CertificateFingerprint=CertificateFingerprint&ClientArn=ClientArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about an HSM client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91040c82-3b72-4613-a73c-6a2df881b121"
            }
          ]
        }
      ]
    },
    {
      "name": "Config",
      "item": [
        {
          "id": "3b398922-d7ea-45ba-bab7-eab437515eda",
          "name": "getConfig",
          "request": {
            "url": "http://example.com/api/?Action=GetConfig?ClientArn=ClientArn&ClientVersion=ClientVersion&HapgList=HapgList",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the configuration files necessary to connect to all high availability partition\n      groups the client is associated with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efe74435-9040-48ed-807a-ff9cdfc948ae"
            }
          ]
        }
      ]
    }
  ]
}