{
  "info": {
    "name": "LH Public Cities",
    "_postman_id": "43179490-eea0-4c8d-890c-d38e974cd005",
    "description": "List all cities or one specific city. It is possible to request the response in a specific language.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "References",
      "item": [
        {
          "id": "2aeba4a5-8b7a-4d04-ad00-c2da8ec996f1",
          "name": "ReferencesCitiesByCityCodeGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.lufthansa.com",
              "path": [
                "v1",
                "references/cities/:cityCode"
              ],
              "query": [
                {
                  "key": "lang",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "cityCode",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "http header: application/json or application/xml (Acceptable values are: application/json, application/xml)",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List all cities or one specific city. It is possible to request the response in a specific language."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f12a476f-24c0-404e-ac8f-8ad850811a73"
            }
          ]
        }
      ]
    }
  ]
}