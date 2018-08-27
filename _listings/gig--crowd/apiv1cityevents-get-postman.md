{
  "info": {
    "name": "GIGANDCROWD Get City Events",
    "_postman_id": "0216416e-a32e-41ed-8160-612dcd7a0f9f",
    "description": "Get city events.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Art",
      "item": [
        {
          "id": "d8d9583d-2ae9-42d0-8a2f-04dc5788d1a5",
          "name": "getApiV1ArtEventsPast",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/art/:id/events/past"
              ],
              "variable": [
                {
                  "id": "id",
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
            "description": "Get art events past."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26da5d9b-575d-42dd-a0ed-6a0c43d4e97d"
            }
          ]
        }
      ]
    },
    {
      "name": "City",
      "item": [
        {
          "id": "a0dbb406-87ac-4e8a-b675-8d6b0b9b8e09",
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
              "id": "e92b4150-f092-4a2a-a090-5b6973216223"
            }
          ]
        }
      ]
    }
  ]
}