---
swagger: "2.0"
x-collection-name: Meetup
x-complete: 0
info:
  title: Meetup Cities
  description: Returns Meetup cities. This method supports search by latitude/longitude/radius,
    by country/state, by query term/zip, or a combination of all of these. Location-only
    searches by lat and lon return all cities within a radius of the provided coordinates.
    Searches with a query return up to 10 cities matching the term, and can be sorted
    by size or distance to a given coordinate. 'smart' ordering can be used to return
    the match(es) with the highest member_count, unless a smaller size match exists
    nearby the given coordinates. Query searches are supported for country but not
    country and state
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2/cities:
    get:
      summary: Cities
      description: Returns Meetup cities. This method supports search by latitude/longitude/radius,
        by country/state, by query term/zip, or a combination of all of these. Location-only
        searches by lat and lon return all cities within a radius of the provided
        coordinates. Searches with a query return up to 10 cities matching the term,
        and can be sorted by size or distance to a given coordinate. 'smart' ordering
        can be used to return the match(es) with the highest member_count, unless
        a smaller size match exists nearby the given coordinates. Query searches are
        supported for country but not country and state
      operationId: cities
      x-api-path-slug: 2cities-get
      parameters:
      - in: query
        name: country
        description: A valid country code
        type: string
      - in: query
        name: lat
        description: Latitude to search
        type: string
      - in: query
        name: lon
        description: Longitude to search
        type: string
      - in: query
        name: query
        description: Search term and/or zip to look for (if this is specified, max
          result size limited to 10)
        type: string
      - in: query
        name: radius
        description: When searching by lat/lon only, specify a radius to search (default
          50 miles)
        type: string
      - in: query
        name: state
        description: A valid state code for the given country, if the country has
          states
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Cities
x-streamrank:
  polling_total_time_average: "0.13"
  polling_size_download_average: "72268.59"
  streaming_total_time_average: "0.08"
  streaming_size_download_average: "36705.26"
  change_yes: "119"
  change_no: "2166"
  time_percentage: "43"
  size_percentage: "49"
  change_percentage: "5"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---