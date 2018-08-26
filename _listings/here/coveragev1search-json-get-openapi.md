---
swagger: "2.0"
x-collection-name: HERE
x-complete: 0
info:
  title: HERE Public Transit API Transit Coverage Within a City
  description: "*Request a list of transit operator coverage within a specified city*\n\nA
    list of operators working within a city is requested using the `coverage/v1/search.json`
    endpoint. The city is specified using the  `q` parameter.\n\n\n\n* **q**  `text`\n
    \\- The name or a part of the name of the city to search.\n\n* **app_id**  `text`\n
    \\- A 20 bytes Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an app_code and app_code with every request.\n\n*
    **app_code**  `text`\n \\- A 20 bytes Base64 URL-safe encoded string used for
    the authentication of the client application.    You must include an app_code
    and app_code with every request.\n\n* **max**  `number`\n \\- Maximum number of
    results to be returned. Default is null.\n\n* **details**  `enum`\n \\- With this
    value set to 1, the list of supported operators and population of the city is
    returned.   When the value is set to 0, only the list of matching city names will
    be returned.  Default value = 1\n\n    Valid values are : `0` - disabled, `1`
    - enabled\n\n* **chinaconfig**  `enum`\n \\- A switch that allows grouping results
    from Taiwan\ntogether with results from China.      \n\n    Valid values are :
    `0` - disabled, `1` - enabled\n\n* **lang**  `text`\n \\- The language of the
    response. The value complies with the ISO 639-1 standard and defaults to <i>en</i>."
  version: 1.0.0
host: cit.transit.api.here.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /coverage/v1/search.json:
    get:
      summary: Transit Coverage Within a City
      description: "*Request a list of transit operator coverage within a specified
        city*\n\nA list of operators working within a city is requested using the
        `coverage/v1/search.json` endpoint. The city is specified using the  `q` parameter.\n\n\n\n*
        **q**  `text`\n \\- The name or a part of the name of the city to search.\n\n*
        **app_id**  `text`\n \\- A 20 bytes Base64 URL-safe encoded string used for
        the authentication of the client application.    You must include an app_code
        and app_code with every request.\n\n* **app_code**  `text`\n \\- A 20 bytes
        Base64 URL-safe encoded string used for the authentication of the client application.
        \   You must include an app_code and app_code with every request.\n\n* **max**
        \ `number`\n \\- Maximum number of results to be returned. Default is null.\n\n*
        **details**  `enum`\n \\- With this value set to 1, the list of supported
        operators and population of the city is returned.   When the value is set
        to 0, only the list of matching city names will be returned.  Default value
        = 1\n\n    Valid values are : `0` - disabled, `1` - enabled\n\n* **chinaconfig**
        \ `enum`\n \\- A switch that allows grouping results from Taiwan\ntogether
        with results from China.      \n\n    Valid values are : `0` - disabled, `1`
        - enabled\n\n* **lang**  `text`\n \\- The language of the response. The value
        complies with the ISO 639-1 standard and defaults to <i>en</i>."
      operationId: CoverageV1SearchJsonGet
      x-api-path-slug: coveragev1search-json-get
      parameters:
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: chinaconfig
      - in: query
        name: details
      - in: query
        name: lang
      - in: query
        name: max
      - in: query
        name: q
      responses:
        200:
          description: OK
      tags:
      - Transit
      - Coverage
      - Within
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