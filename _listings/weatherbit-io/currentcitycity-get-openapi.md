---
swagger: "2.0"
x-collection-name: Weatherbit.io
x-complete: 0
info:
  title: Weatherbit Get Current Cities
  description: '**(Advanced/Advanced+/Enterprise plans only)** Returns a group of
    Current Observations - Given a list of City IDs.'
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
  /current?city={city}:
    get:
      summary: Get Current Cities
      description: '**(Advanced/Advanced+/Enterprise plans only)** Returns a group
        of Current Observations - Given a list of City IDs.'
      operationId: advancedadvancedenterprise-plans-only-returns-a-group-of-current-observations--given-a-list-of-city-
      x-api-path-slug: currentcitycity-get
      parameters:
      - in: query
        name: callback
        description: Wraps return in jsonp callback - Example - callback=func
      - in: query
        name: cities
        description: Comma separated list of City IDs
      - in: query
        name: city
        description: A city name
        type: string
        format: string
      - in: query
        name: key
        description: Your registered API key
      - in: query
        name: lang
        description: 'Language (Default: English) See language field description'
      - in: query
        name: marine
        description: Marine stations only (buoys, oil platforms, etc)
      - in: query
        name: units
        description: Convert to units
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Current
      - Cities
      - Cities
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---