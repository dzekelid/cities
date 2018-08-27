---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Get Cities
  version: 1.0.0
  description: Retrieves a list of cities, possibly filtered.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/cities:
    get:
      summary: Get Cities
      description: Retrieves a list of cities, possibly filtered.
      operationId: dfareporting.cities.list
      x-api-path-slug: userprofilesprofileidcities-get
      parameters:
      - in: query
        name: countryDartIds
        description: Select only cities from these countries
      - in: query
        name: dartIds
        description: Select only cities with these DART IDs
      - in: query
        name: namePrefix
        description: Select only cities with names starting with this prefix
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: regionDartIds
        description: Select only cities from these regions
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - City
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