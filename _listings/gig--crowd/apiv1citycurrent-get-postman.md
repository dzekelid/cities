{
  "info": {
    "name": "GIGANDCROWD Get City Current",
    "_postman_id": "1e96273d-953c-4da6-b5f3-6c3dcf60c385",
    "description": "Get city current.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "City",
      "item": [
        {
          "id": "1cf278b6-170f-481e-a0fb-9185c1c8bae0",
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
              "id": "7cc6576b-b4f1-49a5-b74e-32c707997fcb"
            }
          ]
        },
        {
          "id": "9805dfcd-9ee6-4e5d-9c36-b1172a31c41c",
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
              "id": "0da5a0d2-9abc-4a4d-ad53-9869ea62fb7a"
            }
          ]
        }
      ]
    }
  ]
}