{
  "info": {
    "name": "Weatherbit Get Forecast Daily City",
    "_postman_id": "f6a885b6-f389-4232-9226-3a2417d788d8",
    "description": "**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where each point represents one day (24hr) period. Every point has a datetime string in the format \"YYYY-MM-DD\". One day begins at 00:00 UTC, and ends at 23:59 UTC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "bbe5f8f2-aa1e-466c-9e03-449867fb6933",
          "name": "required-basic-plan-or-higher-returns-a-daily-forecast-where-each-point-represents-one-day-24hr-peri",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "forecast/daily?city_id=:city_id"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "days",
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
                  "key": "units",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "city_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "**(REQUIRED: Basic Plan or Higher)** Returns a daily forecast, where each point represents one day (24hr) period"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e26e0918-743c-45b2-bccc-2a1f07038abb"
            }
          ]
        }
      ]
    }
  ]
}