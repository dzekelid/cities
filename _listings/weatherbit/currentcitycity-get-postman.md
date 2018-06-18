{
  "info": {
    "name": "Weatherbit Get Current Cities",
    "_postman_id": "14e2a4a3-ed03-48aa-b780-43383334d3db",
    "description": "**(Advanced/Advanced+/Enterprise plans only)** Returns a group of Current Observations - Given a list of City IDs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "15875c4a-9c8c-460f-abf5-d98e9993be99",
          "name": "advancedadvancedenterprise-plans-only-returns-a-group-of-current-observations--given-a-list-of-city-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "current?cities=:cities"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "lang",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "marine",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "units",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "cities",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "**(Advanced/Advanced+/Enterprise plans only)** Returns a group of Current Observations - Given a list of City IDs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d78b756-f08d-4858-8d6e-09467bafc046"
            }
          ]
        }
      ]
    }
  ]
}