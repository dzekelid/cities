---
name: Meetup
description: Meetup is an online social networking portal that facilitates offline
  group meetings in various localities around the world. Meetup allows members to
  find and join groups unified by a common interest, such as politics, books, games,
  movies, health, pets, careers or hobbies.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Meetup-Logo-1-med1.jpg
x-kinRank: "9"
x-alexaRank: ""
tags:
- Stack Network
- Stack
- My API Stack
- Meetups
- Media
- Events
created: "2018-05-07"
modified: "2018-05-07"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/cities/master/_listings/meetup/apis.yaml
specificationVersion: "0.14"
apis:
- name: Meetup
  description: Meetup is an online social networking portal that facilitates offline
    group meetings in various localities around the world
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Meetup-Logo-1-med1.jpg
  humanURL: ""
  baseURL: https://api.meetup.com//
  tags: Cities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/cities/master/_listings/meetup/2-cities-get.md
- name: Meetup Cities
  description: Returns Meetup cities. This method supports search by latitude/longitude/radius,
    by country/state, by query term/zip, or a combination of all of these. Location-only
    searches by lat and lon return all cities within a radius of the provided coordinates.
    Searches with a query return up to 10 cities matching the term, and can be sorted
    by size or distance to a given coordinate. 'smart' ordering can be used to return
    the match(es) with the highest member_count, unless a smaller size match exists
    nearby the given coordinates. Query searches are supported for country but not
    country and state
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Meetup-Logo-1-med1.jpg
  humanURL: http://www.meetup.com/
  baseURL: https://api.meetup.com//
  tags: Cities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/cities/master/_listings/meetup/2-cities-get.md
x-common:
- type: x-base
  url: http://api.meetup.com
- type: x-developer
  url: http://www.meetup.com/meetup_api/
- type: x-github
  url: https://github.com/meetup
- type: x-pricing
  url: http://www.meetup.com/pricing/
- type: x-privacy
  url: http://www.meetup.com/privacy/
- type: x-support
  url: http://www.meetup.com/help/
- type: x-terms-of-service
  url: http://www.meetup.com/terms/
- type: x-twitter
  url: https://twitter.com/MeetupAPI
- type: x-website
  url: http://www.meetup.com/
- type: x-base
  url: http://api.meetup.com
- type: x-developer
  url: http://www.meetup.com/meetup_api/
- type: x-github
  url: https://github.com/meetup
- type: x-pricing
  url: http://www.meetup.com/pricing/
- type: x-privacy
  url: http://www.meetup.com/privacy/
- type: x-support
  url: http://www.meetup.com/help/
- type: x-terms-of-service
  url: http://www.meetup.com/terms/
- type: x-twitter
  url: https://twitter.com/MeetupAPI
- type: x-website
  url: http://www.meetup.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---