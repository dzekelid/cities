{
  "info": {
    "name": "Weatherbit Get History Daily City & Country",
    "_postman_id": "6f09850e-67f6-4177-bb36-693234d30c1c",
    "description": "Returns Historical Observations - Given a city in the format of City,ST or City. The state, and country parameters can be provided to make the search more accurate. **(LIMIT 1 day for Low Volume plans. LIMIT 7 days for Basic/Developer. LIMIT 30 days for Advanced/Advanced+/Enterprise)**",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "weather",
      "item": [
        {
          "id": "196f2bb4-8f9e-426f-983b-5055f5fd92cc",
          "name": "returns-historical-observations--given-a-city-in-the-format-of-cityst-or-city-the-state-and-country-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.weatherbit.io",
              "path": [
                "v2.0",
                "history/daily?city=:city&country=:country"
              ],
              "query": [
                {
                  "key": "callback",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "end_date",
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
                  "key": "start_date",
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
            "description": "Returns Historical Observations - Given a city in the format of City,ST or City"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53707471-ea26-4bd5-84b2-bf5fe36e82e4"
            }
          ]
        }
      ]
    }
  ]
}