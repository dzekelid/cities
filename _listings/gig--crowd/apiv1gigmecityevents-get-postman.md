{
  "info": {
    "name": "GIGANDCROWD Get Gigme City Events",
    "_postman_id": "324c6ee0-7f40-4f46-9bbd-ac180baeeb2b",
    "description": "Get gigme city events.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Art",
      "item": [
        {
          "id": "1c65182a-f6d9-4bd9-830a-8aa8ed73a0e2",
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
              "id": "978e87cc-8ca0-41e2-9344-36ea415b5684"
            }
          ]
        }
      ]
    },
    {
      "name": "City",
      "item": [
        {
          "id": "0ebae0d8-b4da-47d6-96ab-30616d5970b9",
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
              "id": "5703f0db-04ba-44d2-83fc-82231bb794eb"
            }
          ]
        }
      ]
    },
    {
      "name": "Gigme",
      "item": [
        {
          "id": "27664f55-7e3f-47a2-ad05-3e59c5966391",
          "name": "getApiV1GigmeArtistEventsPast",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/gigme/artist/:id/events/past"
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
            "description": "Get gigme artist events past."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38b852ce-72ed-4184-96b2-63740108246d"
            }
          ]
        },
        {
          "id": "e4e5a5fa-a52d-4e94-9579-cc30b00e4dcb",
          "name": "getApiV1GigmeArtistEventsFuture",
          "request": {
            "url": {
              "protocol": "http",
              "host": "gigandcrowd.com",
              "path": [
                "api/v1/gigme/artist/:id/events/future"
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
            "description": "Get gigme artist events future."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "290823c2-3edc-4c0d-ad41-4a6a2b755cff"
            }
          ]
        },
        {
          "id": "b17e6047-10e6-4f1a-bb21-7eb7e93db200",
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
              "id": "13a34e42-fb6f-42f7-b3cb-a377426b8f54"
            }
          ]
        }
      ]
    }
  ]
}