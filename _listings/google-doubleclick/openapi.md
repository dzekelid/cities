---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 1
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
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
---