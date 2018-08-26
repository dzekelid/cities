---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get City Query
  version: 1.0.0
  description: Get city query.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/city/events:
    get:
      summary: Get City Events
      description: Get city events.
      operationId: getApiV1CityEvents
      x-api-path-slug: apiv1cityevents-get
      responses:
        200:
          description: OK
      tags:
      - City
      - Events
  /api/v1/city/current:
    get:
      summary: Get City Current
      description: Get city current.
      operationId: getApiV1CityCurrent
      x-api-path-slug: apiv1citycurrent-get
      responses:
        200:
          description: OK
      tags:
      - City
      - Current
  /api/v1/city/{query}:
    get:
      summary: Get City Query
      description: Get city query.
      operationId: getApiV1CityQuery
      x-api-path-slug: apiv1cityquery-get
      parameters:
      - in: path
        name: query
      responses:
        200:
          description: OK
      tags:
      - City
      - Query
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