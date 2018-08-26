{
  "info": {
    "name": "GIGANDCROWD Get City Query",
    "_postman_id": "8a7a49da-c13e-4604-a7a8-edf48381c03d",
    "description": "Get city query.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "City",
      "item": [
        {
          "id": "51d2ff1a-a5cf-49e8-82f8-a5357ccdddc1",
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
              "id": "8d5c58d3-5c2f-4969-98f3-3e20ff67ccec"
            }
          ]
        },
        {
          "id": "d2aaa46c-0725-4631-b455-d03917ab185c",
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
              "id": "70a8a5b3-200d-4928-831d-997fbca2d7be"
            }
          ]
        },
        {
          "id": "1e1930fb-3421-4d70-87b3-8cf50d88b7fe",
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
              "id": "8694cc69-f31b-4313-896e-55cd91cb6d92"
            }
          ]
        }
      ]
    }
  ]
}