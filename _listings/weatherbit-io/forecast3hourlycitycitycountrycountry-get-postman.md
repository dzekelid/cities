{
  "info": {
    "name": "Weatherbit Get Forecast 3hourly City & Country",
    "_postman_id": "f28ca8ee-0ba3-4625-973f-e8f1cd1fe82d",
    "description": "Returns a 3-hourly forecast, where each point represents a three hour   period. Every point has a datetime string in the format \"YYYY-MM-DD:HH\". Time is UTC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "8d9d84d0-3eef-4b8d-9309-1e6ca2560462",
          "name": "returns-a-3hourly-forecast-where-each-point-represents-a-three-hour---period-every-point-has-a-datet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "forecast/3hourly?city=:city&country=:country"
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
            "description": "Returns a 3-hourly forecast, where each point represents a three hour   period"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd9d57da-6868-4aca-8e7e-cb7231b9e50c"
            }
          ]
        }
      ]
    }
  ]
}