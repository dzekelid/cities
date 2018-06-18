---
swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 1
info:
  title: LH Public
  version: "1.0"
host: api.lufthansa.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /references/cities/{cityCode}:
    get:
      summary: Cities
      description: List all cities or one specific city. It is possible to request
        the response in a specific language.
      operationId: ReferencesCitiesByCityCodeGet
      x-api-path-slug: referencescitiescitycode-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: cityCode
        description: 3-letter IATA city code
      - in: query
        name: lang
        description: 2 letter ISO 3166-1 language code
      - in: query
        name: limit
        description: Number of records returned per request
      - in: query
        name: offset
        description: Number of records skipped
      responses:
        200:
          description: OK
      tags:
      - References
      - Cities
      - CityCode
---