{
  "info": {
    "name": "AWS Simple Email Service API Update Configuration Set Event Destination",
    "_postman_id": "184381bf-7cfe-4e88-8b10-2b19e5d6daa1",
    "description": "Updates the event destination of a configuration set.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Receipt Rule Sets",
      "item": [
        {
          "id": "d7ca735c-f171-44bb-a301-3dc5c1580154",
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
              "id": "3c3756f1-e5df-437f-894d-e3a381c26c71"
            }
          ]
        },
        {
          "id": "58f460fa-f09d-4dcd-b223-a6fa8626f0c7",
          "name": "createReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateReceiptRuleSet?RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an empty receipt rule set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a94b844-b30a-45d2-b1a2-dc80f61fd8e5"
            }
          ]
        },
        {
          "id": "f8bb2e31-4f37-4e6f-9947-956848d10f8f",
          "name": "deleteReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteReceiptRuleSet?RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified receipt rule set and all of the receipt rules it contains."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f5a741d-d5bb-4e3a-9fe9-abbfe8154eb8"
            }
          ]
        },
        {
          "id": "7741a019-9563-4482-ab18-a21290ac6760",
          "name": "describeActiveReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=DescribeActiveReceiptRuleSet?Metadata=Metadata&Rules.member.N=Rules.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the metadata and receipt rules for the receipt rule set that is currently active."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9debc82-6b8d-464c-9de4-cb9b2844401e"
            }
          ]
        },
        {
          "id": "884a52fa-f693-4fd0-b193-9b21e6e73e94",
          "name": "describeReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReceiptRuleSet?RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the details of the specified receipt rule set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be2e6b2b-2c75-4813-b05d-a99a71c75140"
            }
          ]
        },
        {
          "id": "d7d519d0-2a71-413a-accb-249c989cd6dc",
          "name": "listReceiptRuleSets",
          "request": {
            "url": "http://example.com/api/?Action=ListReceiptRuleSets?NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the receipt rule sets that exist under your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a3ec0e9b-8dd3-43ff-b1bc-4425ebe1d7e9"
            }
          ]
        },
        {
          "id": "ef7f3d00-b8bc-4ea0-9b80-60e629615df9",
          "name": "reorderReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=ReorderReceiptRuleSet?RuleNames.member.N=RuleNames.member.N&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Reorders the receipt rules within a receipt rule set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b6127d4e-98f6-40c1-86ef-248f8f117287"
            }
          ]
        },
        {
          "id": "f9239c4d-1642-48ef-86c9-03d85b6522b4",
          "name": "setActiveReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=SetActiveReceiptRuleSet?RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the specified receipt rule set as the active receipt rule set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b64bf7e-6702-4f49-bf08-20ed2ac8b950"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Sets",
      "item": [
        {
          "id": "de8afff4-8d7f-4e3d-8c51-5ebf0b3edcaa",
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
              "id": "da8610a9-19ac-4165-a0cf-67351a736b93"
            }
          ]
        },
        {
          "id": "e162a853-20ea-43d7-bb70-4a619c852dce",
          "name": "deleteConfigurationSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConfigurationSet?ConfigurationSetName=ConfigurationSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a configuration set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0aef695e-25d2-4d78-92e7-52fb3ff319cc"
            }
          ]
        },
        {
          "id": "8236f8b9-a1f0-422e-8605-45f256de5922",
          "name": "describeConfigurationSet",
          "request": {
            "url": "http://example.com/api/?Action=DescribeConfigurationSet?ConfigurationSetAttributeNames.member.N=ConfigurationSetAttributeNames.member.N&ConfigurationSetName=ConfigurationSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the details of the specified configuration set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2faf1b2-5923-406f-9ced-1088e2a22c30"
            }
          ]
        },
        {
          "id": "943ea3a3-c6ef-4717-9a5e-66e3d39f1469",
          "name": "listConfigurationSets",
          "request": {
            "url": "http://example.com/api/?Action=ListConfigurationSets?MaxItems=MaxItems&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the configuration sets associated with your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b5ba7ae-f725-4c43-984c-ecbd8019c998"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Set Event Destination",
      "item": [
        {
          "id": "f4680b8d-82db-4941-aba4-21a8c5c22995",
          "name": "createConfigurationSetEventDestination",
          "request": {
            "url": "http://example.com/api/?Action=CreateConfigurationSetEventDestination?ConfigurationSetName=ConfigurationSetName&EventDestination=EventDestination",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a configuration set event destination."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94874228-15c1-4063-a4c5-d30041cfca55"
            }
          ]
        },
        {
          "id": "115d1490-3214-4a2c-b311-5c07dc3007e7",
          "name": "deleteConfigurationSetEventDestination",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConfigurationSetEventDestination?ConfigurationSetName=ConfigurationSetName&EventDestinationName=EventDestinationName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a configuration set event destination."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6ea92e0-998b-403a-97b3-a906ca6ed49b"
            }
          ]
        },
        {
          "id": "ac7d0677-ed58-4924-b06e-12042a65f8b3",
          "name": "updateConfigurationSetEventDestination",
          "request": {
            "url": "http://example.com/api/?Action=UpdateConfigurationSetEventDestination?ConfigurationSetName=ConfigurationSetName&EventDestination=EventDestination",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the event destination of a configuration set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35d50961-0831-4e3c-98e0-b04a302317e3"
            }
          ]
        }
      ]
    },
    {
      "name": "Receipt Filters",
      "item": [
        {
          "id": "eda7d78a-ba55-49ff-9fdb-798ca9338677",
          "name": "createReceiptFilter",
          "request": {
            "url": "http://example.com/api/?Action=CreateReceiptFilter?Filter=Filter",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new IP address filter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f8aa29d-816e-4b9f-8a45-0a36f707e5af"
            }
          ]
        },
        {
          "id": "b7c42bbb-0f34-4d45-a653-4f89d4e4a8c7",
          "name": "deleteReceiptFilter",
          "request": {
            "url": "http://example.com/api/?Action=DeleteReceiptFilter?FilterName=FilterName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified IP address filter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43bb9a9f-fce3-42d7-a89f-baf8e1b91558"
            }
          ]
        },
        {
          "id": "5939fd6b-dad4-4117-a4d0-362cc5e391d4",
          "name": "listReceiptFilters",
          "request": {
            "url": "http://example.com/api/?Action=ListReceiptFilters?Filters.member.N=Filters.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IP address filters associated with your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85fd9157-0ece-4f9c-b21a-24e657579dca"
            }
          ]
        }
      ]
    },
    {
      "name": "Receipt Rules",
      "item": [
        {
          "id": "0f0cc09b-a1ff-4a2d-9226-9c12ca0c5dc4",
          "name": "createReceiptRule",
          "request": {
            "url": "http://example.com/api/?Action=CreateReceiptRule?After=After&Rule=Rule&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a receipt rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e177d0fa-a488-4f5b-b225-55a3352b8628"
            }
          ]
        },
        {
          "id": "f31e5568-c5df-47aa-b740-db32bdc37256",
          "name": "deleteReceiptRule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteReceiptRule?RuleName=RuleName&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified receipt rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe93a465-df2e-410f-976b-420c029e23cf"
            }
          ]
        },
        {
          "id": "d0b9bb27-be15-4265-ae9f-552f7776c4ca",
          "name": "describeReceiptRule",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReceiptRule?RuleName=RuleName&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the details of the specified receipt rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab75a644-9a46-4488-8fe3-580aa864efaf"
            }
          ]
        },
        {
          "id": "effc9d15-73d6-46e4-a16f-9991f7c9c59d",
          "name": "setReceiptRulePosition",
          "request": {
            "url": "http://example.com/api/?Action=SetReceiptRulePosition?After=After&RuleName=RuleName&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the position of the specified receipt rule in the receipt rule set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cdfe59a6-727b-4ec3-9fb6-f4422594fe99"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity",
      "item": [
        {
          "id": "f936f521-deee-4552-baf2-3d91308b5c33",
          "name": "deleteIdentity",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentity?Identity=Identity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified identity (an email address or a domain) from the list of verified identities."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e5e523e-d994-496d-b5e1-affae681a855"
            }
          ]
        },
        {
          "id": "9e534bf9-fe09-4e52-a3c3-da9b98933260",
          "name": "deleteIdentityPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentityPolicy?Identity=Identity&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified sending authorization policy for the given identity (an email address or a domain)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9842550c-b079-401d-ad56-e91d9544dec9"
            }
          ]
        },
        {
          "id": "86da0d60-caa1-48b1-94f6-a6999c44604f",
          "name": "getIdentityDkimAttributes",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityDkimAttributes?Identities.member.N=Identities.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the current status of Easy DKIM signing for an entity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b21af2b-1827-4cdd-8d17-6e2480b54430"
            }
          ]
        },
        {
          "id": "1025cbd9-44a4-40a3-bc6a-014d174397b4",
          "name": "getIdentityMailFromDomainAttributes",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityMailFromDomainAttributes?Identities.member.N=Identities.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the custom MAIL FROM attributes for a list of identities (email addresses and/or domains)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa9f5cbe-f1ff-4f9d-981d-88f679a75037"
            }
          ]
        },
        {
          "id": "58ab649f-a68b-4de8-974e-e64d56622afe",
          "name": "getIdentityNotificationAttributes",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityNotificationAttributes?Identities.member.N=Identities.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a list of verified identities (email addresses and/or domains), returns a structure describing identity notification attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3a0462a-9370-4723-ba57-53b584c3c026"
            }
          ]
        },
        {
          "id": "927ee0ba-20f6-470b-b12d-26a10332e565",
          "name": "getIdentityPolicies",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityPolicies?Identity=Identity&PolicyNames.member.N=PolicyNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the requested sending authorization policies for the given identity (an email address or a domain)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d54c613b-df17-4946-aa90-b9fcfb8df38d"
            }
          ]
        },
        {
          "id": "59047300-5603-4fd6-9efb-1edc6df1b35d",
          "name": "getIdentityVerificationAttributes",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityVerificationAttributes?Identities.member.N=Identities.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a list of identities (email addresses and/or domains), returns the verification status and (for domain identities) the verification token for each identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca16d814-60b6-4356-a417-688abebd8dd9"
            }
          ]
        },
        {
          "id": "573a5b61-59bc-4fb5-9c4f-dfad316e8f74",
          "name": "listIdentities",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentities?IdentityType=IdentityType&MaxItems=MaxItems&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list containing all of the identities (email addresses and domains) for your AWS account, regardless of verification status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "470189b8-f521-435d-b330-130c3ac6b00c"
            }
          ]
        },
        {
          "id": "6565a71a-5a6e-4a49-bd21-ad04365ade09",
          "name": "listIdentityPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentityPolicies?Identity=Identity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of sending authorization policies that are attached to the given identity (an email address or a domain)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b7596208-f241-4fdf-8864-dd57edd0b585"
            }
          ]
        },
        {
          "id": "4a5870d0-fe92-44cc-9cd6-3172ebe28198",
          "name": "putIdentityPolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutIdentityPolicy?Identity=Identity&Policy=Policy&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or updates a sending authorization policy for the specified identity (an email address or a domain)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74b7a04d-aa95-4915-8109-a74818e428f6"
            }
          ]
        },
        {
          "id": "a3d7e42b-9c28-4002-b77e-0231b0b2bcc7",
          "name": "setIdentityDkimEnabled",
          "request": {
            "url": "http://example.com/api/?Action=SetIdentityDkimEnabled?DkimEnabled=DkimEnabled&Identity=Identity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables or disables Easy DKIM signing of email sent from an identity:If Easy DKIM\n            signing is enabled for a domain name identity (e."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "953823b2-c301-48f4-94cb-ce165914ee2f"
            }
          ]
        },
        {
          "id": "90c180b5-b701-43ca-89d4-a424a7e3e252",
          "name": "setIdentityFeedbackForwardingEnabled",
          "request": {
            "url": "http://example.com/api/?Action=SetIdentityFeedbackForwardingEnabled?ForwardingEnabled=ForwardingEnabled&Identity=Identity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given an identity (an email address or a domain), enables or disables whether Amazon SES forwards bounce and complaint notifications as email."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "806bceab-e1d2-466f-96f1-a3bda22a8b3f"
            }
          ]
        },
        {
          "id": "ba1d3152-e5d6-40ca-b246-12267749e0da",
          "name": "setIdentityHeadersInNotificationsEnabled",
          "request": {
            "url": "http://example.com/api/?Action=SetIdentityHeadersInNotificationsEnabled?Enabled=Enabled&Identity=Identity&NotificationType=NotificationType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given an identity (an email address or a domain), sets whether Amazon SES includes \n            the original email headers in the Amazon Simple Notification Service (Amazon SNS) notifications \n            of a specified type."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cfdc3e08-053c-4b41-8b11-a1e3ea2c3d4c"
            }
          ]
        },
        {
          "id": "75f691fa-2998-4f39-aff0-b6956fa20f80",
          "name": "setIdentityMailFromDomain",
          "request": {
            "url": "http://example.com/api/?Action=SetIdentityMailFromDomain?BehaviorOnMXFailure=BehaviorOnMXFailure&Identity=Identity&MailFromDomain=MailFromDomain",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables or disables the custom MAIL FROM domain setup for a verified identity (an email address or a domain)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc67a60e-b1c6-4b80-af79-da9f3c3486d0"
            }
          ]
        },
        {
          "id": "406db9f8-2c8b-41c8-897a-a2c6d8febc8c",
          "name": "setIdentityNotificationTopic",
          "request": {
            "url": "http://example.com/api/?Action=SetIdentityNotificationTopic?Identity=Identity&NotificationType=NotificationType&SnsTopic=SnsTopic",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given an identity (an email address or a domain), sets the Amazon Simple Notification Service (Amazon SNS) topic to which Amazon SES will publish\n        bounce, complaint, and/or delivery notifications for emails sent with that identity as the Source."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2ae93e9-a149-439f-b4f2-3b85ae8e6687"
            }
          ]
        }
      ]
    },
    {
      "name": "Verified Email Addresses",
      "item": [
        {
          "id": "55fdb0ac-277d-40e3-87b0-c342fc95ecd5",
          "name": "deleteVerifiedEmailAddress",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVerifiedEmailAddress?EmailAddress=EmailAddress",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified email address from the list of verified addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf6ac11e-f4f9-4c91-9ee2-0e3e32f16824"
            }
          ]
        },
        {
          "id": "e7255298-aaa4-4459-86d7-f7020fd26533",
          "name": "listVerifiedEmailAddresses",
          "request": {
            "url": "http://example.com/api/?Action=ListVerifiedEmailAddresses?VerifiedEmailAddresses.member.N=VerifiedEmailAddresses.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list containing all of the email addresses that have been verified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f31fdbb-0d32-4db0-af6c-f05f95dc48f6"
            }
          ]
        }
      ]
    },
    {
      "name": "Send Quota",
      "item": [
        {
          "id": "0fbef963-fcae-456a-becd-0ff3ea9e53cd",
          "name": "getSendQuota",
          "request": {
            "url": "http://example.com/api/?Action=GetSendQuota?Max24HourSend=Max24HourSend&MaxSendRate=MaxSendRate&SentLast24Hours=SentLast24Hours",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the user's current sending limits."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "444183a6-34dd-4a5b-b819-421efd3a673e"
            }
          ]
        }
      ]
    },
    {
      "name": "Send Statistics",
      "item": [
        {
          "id": "40d77eb0-cb41-4e29-a3aa-eb9cca381832",
          "name": "getSendStatistics",
          "request": {
            "url": "http://example.com/api/?Action=GetSendStatistics?SendDataPoints.member.N=SendDataPoints.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the user's sending statistics."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b33dc20-38f2-48f2-a07d-976254978d57"
            }
          ]
        }
      ]
    },
    {
      "name": "Bounce",
      "item": [
        {
          "id": "6e9060ef-a19e-4de2-a7e8-bd9f5bc5cd54",
          "name": "sendBounce",
          "request": {
            "url": "http://example.com/api/?Action=SendBounce?BouncedRecipientInfoList.member.N=BouncedRecipientInfoList.member.N&BounceSender=BounceSender&BounceSenderArn=BounceSenderArn&Explanation=Explanation&MessageDsn=MessageDsn&OriginalMessageId=OriginalMessageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates and sends a bounce message to the sender of an email you received through Amazon SES."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2007f8c4-3846-442a-85a0-cb56ef6d69bb"
            }
          ]
        }
      ]
    },
    {
      "name": "Email",
      "item": [
        {
          "id": "3c2a0a43-1dcd-4349-844f-295aaa7eb940",
          "name": "sendEmail",
          "request": {
            "url": "http://example.com/api/?Action=SendEmail?ConfigurationSetName=ConfigurationSetName&Destination=Destination&Message=Message&ReplyToAddresses.member.N=ReplyToAddresses.member.N&ReturnPath=ReturnPath&ReturnPathArn=ReturnPathArn&Source=Source&SourceArn=SourceArn&Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Composes an email message based on input data, and then immediately queues the message for sending."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f16f642-9a9d-43c2-ae66-42e5551aef01"
            }
          ]
        },
        {
          "id": "fda74fa6-1265-4273-928c-72aa3e54e3dc",
          "name": "sendRawEmail",
          "request": {
            "url": "http://example.com/api/?Action=SendRawEmail?ConfigurationSetName=ConfigurationSetName&Destinations.member.N=Destinations.member.N&FromArn=FromArn&RawMessage=RawMessage&ReturnPathArn=ReturnPathArn&Source=Source&SourceArn=SourceArn&Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sends an email message, with header and content specified by the client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "228fc97c-93ba-452f-a8fe-c8c04e78dcfe"
            }
          ]
        }
      ]
    }
  ]
}