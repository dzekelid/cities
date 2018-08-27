{
  "info": {
    "name": "Weatherbit Get Forecast Hourly City & Country",
    "_postman_id": "7c6ebc48-288c-418f-858f-74f0140ddc23",
    "description": "**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast, where each point represents a one hour   period. Every point has a datetime string in the format \"YYYY-MM-DD:HH\". Time is UTC. Accepts a city in the format of City,ST or City. The state, and country parameters can be provided to make the search more accurate.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "25528c56-4993-466b-a729-ef6b3515a153",
          "name": "required-developer-plan-or-higher-returns-an-hourly-forecast-where-each-point-represents-a-one-hour-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "forecast/hourly?city=:city&country=:country"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "hours",
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
                  "key": "state",
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
                  "id": "city",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "country",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "**(REQUIRED: Developer Plan or Higher)** Returns an hourly forecast, where each point represents a one hour   period"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1c8c6b3-0604-4e41-a6e6-88973f2d395d"
            }
          ]
        }
      ]
    }
  ]
}