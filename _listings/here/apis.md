---
name: HERE
x-slug: here
description: HERE Technologies enables people, enterprises and cities around the world
  to harness the power of location and create innovative solutions that make our lives
  safer and more efficient. We transform information from devices, vehicles, infrastructure
  and...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
x-kinRank: "7"
x-alexaRank: "3011"
tags: Cities
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/cities/master/_listings/here/apis.md
specificationVersion: "0.14"
apis:
- name: Public Transport API - Transit Coverage Within a City
  x-api-slug: coveragev1search-json-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://cit.transit.api.here.com//
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/cities/master/_listings/here/coveragev1search-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/cities/master/_listings/here/coveragev1search-json-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://developer.here.com/blog/feed
- type: x-github
  url: https://github.com/heremaps
- type: x-postman-collection
  url: https://github.com/heremaps/postman-collections
- type: x-api-gallery
  url: http://healthcare.gov.api.gallery.streamdata.io
- type: x-api-stack
  url: http://here.stack.network
- type: x-blog
  url: https://developer.here.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/here-inc
- type: x-developer
  url: https://developer.here.com
- type: x-email
  url: dirk.popp@here.com
- type: x-email
  url: sebastian.kurme@here.com
- type: x-email
  url: jordan.stark@here.com
- type: x-email
  url: amy.stupavsky@here.com
- type: x-email
  url: minna.laub@here.com
- type: x-email
  url: stefanie.sirc@here.com
- type: x-email
  url: rachel.kuta@here.com
- type: x-email
  url: laurel.davis-lyons@here.com
- type: x-email
  url: linda.bradley@here.com
- type: x-email
  url: press@here.com
- type: x-twitter
  url: https://twitter.com/here
- type: x-website
  url: https://here.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---