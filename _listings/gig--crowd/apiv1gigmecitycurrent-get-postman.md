{
  "info": {
    "name": "GIGANDCROWD Get Gigme City Current",
    "_postman_id": "30498a2e-4fb1-4261-b573-84f9b4d5081d",
    "description": "Get gigme city current.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "City",
      "item": [
        {
          "id": "75425e45-aa3a-4877-9e6f-b4482a057508",
          "name": "getApiV1CityEvents",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/city/events",
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
            "description": "Get city events."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a18acd3-efb5-4cd3-a28a-99c24aa31ebd"
            }
          ]
        },
        {
          "id": "432bc48d-3347-44b3-814a-24243984cf49",
          "name": "getApiV1CityCurrent",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/city/current",
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
            "description": "Get city current."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d60f463-feab-4442-9101-48404019615f"
            }
          ]
        },
        {
          "id": "e2af0096-3df1-4366-adbe-c8f550ac1340",
          "name": "getApiV1CityQuery",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/city/:query"
              ],
              "variable": [
                {
                  "id": "query",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Get city query."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47d1437a-dd0a-4ee0-bb7c-ed54435ba1cb"
            }
          ]
        }
      ]
    },
    {
      "name": "Gigme",
      "item": [
        {
          "id": "b1a7e0c1-17ce-4243-bd7d-00d0c0d85e65",
          "name": "getApiV1GigmeCityEvents",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/gigme/city/events",
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
            "description": "Get gigme city events."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "046e5da0-0673-4884-984b-40ea5e0ad74f"
            }
          ]
        },
        {
          "id": "15eb99f1-a070-42cd-9839-229fcb37b00b",
          "name": "getApiV1GigmeCityCurrent",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/gigme/city/current",
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
            "description": "Get gigme city current."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04807441-3ee1-4627-853b-e41b9113f399"
            }
          ]
        }
      ]
    }
  ]
}