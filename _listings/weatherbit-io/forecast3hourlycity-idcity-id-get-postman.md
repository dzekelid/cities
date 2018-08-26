{
  "info": {
    "name": "Weatherbit Get Forecast 3hourly City",
    "_postman_id": "0bedfa86-0f0e-4413-b72b-8abe0cd35be2",
    "description": "Returns a 3-hourly forecast, where each point represents a three hour   period. Every point has a datetime string in the format \"YYYY-MM-DD:HH\". Time is UTC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "39cc3474-a6b1-4c4e-8aea-cf673362d7b0",
          "name": "returns-a-3hourly-forecast-where-each-point-represents-a-three-hour---period-every-point-has-a-datet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "forecast/3hourly?city_id=:city_id"
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
            "description": "Returns a 3-hourly forecast, where each point represents a three hour   period"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "854fae52-c2ce-454d-a028-30e528d58931"
            }
          ]
        }
      ]
    }
  ]
}