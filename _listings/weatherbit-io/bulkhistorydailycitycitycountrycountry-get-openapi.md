---
swagger: "2.0"
x-collection-name: Weatherbit.io
x-complete: 0
info:
  title: Weatherbit Get Bulk History Daily City Country
  description: Returns Historical Observations - Given a city in the format of City,ST
    or City. The state, and country parameters can be provided to make the search
    more accurate.
  version: 2.0.0
host: api.weatherbit.io
basePath: /v2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /bulk/history/daily?city={city}&country={country}:
    get:
      summary: Get Bulk History Daily City Country
      description: Returns Historical Observations - Given a city in the format of
        City,ST or City. The state, and country parameters can be provided to make
        the search more accurate.
      operationId: returns-historical-observations--given-a-city-in-the-format-of-cityst-or-city-the-state-and-country-
      x-api-path-slug: bulkhistorydailycitycitycountrycountry-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback
      - in: path
        name: city
        description: City search
      - in: path
        name: country
        description: Country Code (2 letter)
      - in: query
        name: end_date
        description: End Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: start_date
        description: Start Date (YYYY-MM-DD or YYYY-MM-DD:HH)
      - in: query
        name: state
        description: Full name of state
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Bulk
      - History
      - Daily
      - City
      - City
      - '&country'
      - Country
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---