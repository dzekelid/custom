{
  "info": {
    "name": "Entertainment Express Get Summary by Customer ID.",
    "_postman_id": "02e218e0-b677-4aaf-a107-25fecdc74030",
    "description": "Requires a valid Customer ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Analytics",
      "item": [
        {
          "id": "46a5ab89-8d56-4af5-8890-99dde34e9513",
          "name": "GetAnalyticsViewersByCity",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/City/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
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
            "description": "No required parameters, DateValue defaults to Today.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2158cdfa-b352-44ba-9e0f-e0d343d88a2e"
            }
          ]
        },
        {
          "id": "27c5ba2d-0a09-4179-aa10-d4fbe6d96a52",
          "name": "GetAnalyticsViewersByCountry",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Country/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
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
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1f4d795-0b77-4697-829b-07005fe9fd10"
            }
          ]
        },
        {
          "id": "d126f66e-b328-4b2d-b80d-9df441d64a3f",
          "name": "GetAnalyticEngagementActions",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/EngagementActions/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
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
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9bb3bc8-8dc1-42be-8544-fa6d3052f7fc"
            }
          ]
        },
        {
          "id": "a149f25f-80cf-4e91-81bb-d6f0449bba1a",
          "name": "GetAnalyticsEngagementTimes",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/EngagementTimes/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
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
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e65cc4ce-a86d-4ece-9283-02c3692125de"
            }
          ]
        },
        {
          "id": "9159f4b5-4fb7-4968-9909-212251113832",
          "name": "GetAnalyticsGBUsage",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/GBUsage/?Month=%7B%7D&ReportTag=%7B%7D&Year=%7B%7D",
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
            "description": "Requires a valid Customer ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ea54683-5c1a-49d2-9b66-f2461b70c36f"
            }
          ]
        },
        {
          "id": "18686116-eb46-43d2-9221-cd9e4729fb7d",
          "name": "GetAnalyticsMostActive",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/MostActive/?DateValue=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D",
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
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5941445f-473d-4436-96b4-c2632bebea32"
            }
          ]
        },
        {
          "id": "a46a8347-78af-4a16-8209-08c3fb0ef6b7",
          "name": "GetAnalyticsViewersByPlatformHardware",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/PlatformHardware/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
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
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa2e71d6-dfbd-4f6c-8f7a-d94faafb2b5f"
            }
          ]
        },
        {
          "id": "ef95fbf6-8488-431c-95aa-3d9a9e8550d6",
          "name": "GetAnalyticsViewersByPlatformOS",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/PlatformOS/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
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
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "069157ff-e82e-4e29-9398-9af6c6997d31"
            }
          ]
        },
        {
          "id": "5192b99c-e421-4816-8da9-82bd2b6dad22",
          "name": "GetAnalyticsRecentVisitors",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/RecentVisitors/?Limit=%7B%7D&ReportTag=%7B%7D",
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
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85cd8dd0-76a8-4bc9-ac2d-34212983ab20"
            }
          ]
        },
        {
          "id": "228687e0-956e-4c4c-91a6-a36f2a67ed1a",
          "name": "GetAnalyticsSummary",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Summary/?DateValue=%7B%7D&ReportTag=%7B%7D",
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
            "description": "Requires a valid Customer ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5acef1a8-e3a1-4218-b6bb-2306fdbf01e6"
            }
          ]
        },
        {
          "id": "a76b229c-1cdb-45ab-a090-d60ad4a83ff4",
          "name": "GetAnalyticsTitleReport",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/TitleReport/?End=%7B%7D&PublishedId=%7B%7D&Start=%7B%7D",
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
            "description": "Requires a valid published ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9076690-d4db-4c67-9c84-7bf36cb6a2fa"
            }
          ]
        },
        {
          "id": "85a88413-5c1c-40d4-96b0-632e4aad5967",
          "name": "GetAnalyticsViewsByVideoLog",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/VideoLog/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
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
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f68cd4c5-fbf6-4f57-9275-88edc724bc00"
            }
          ]
        },
        {
          "id": "01733de0-4dec-48db-bd31-b714f4b82581",
          "name": "GetAnalyticsViewers",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Viewers/?DateValue=%7B%7D&ReportTag=%7B%7D",
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
            "description": "Optional DateValue for length of report."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bcaec65a-e593-4a7b-aaa3-edcf9ed6d630"
            }
          ]
        },
        {
          "id": "c9433272-55d0-4b98-b5fb-7a619c554cdc",
          "name": "GetAnalyticsViews",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/Views/?DateValue=%7B%7D&ReportTag=%7B%7D",
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
            "description": "Optional DateValue for length of report."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "988a039a-d08b-462e-b727-8e4ab48694e5"
            }
          ]
        },
        {
          "id": "d7f7b54c-b15c-48a3-a1a8-3f7bf6a20a46",
          "name": "GetAnalyticsViewersByWebBrowsers",
          "request": {
            "url": "http://ee.iva-api.com/Analytics/WebBrowsers/?DateValue=%7B%7D&End=%7B%7D&Limit=%7B%7D&ReportTag=%7B%7D&Start=%7B%7D",
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
            "description": "No required parameters, DateValue defaults to Today."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d82c851-a584-4cf4-86ab-d47b128b665d"
            }
          ]
        }
      ]
    }
  ]
}