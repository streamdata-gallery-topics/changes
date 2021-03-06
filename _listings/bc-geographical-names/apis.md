---
name: BC Geographical Names
x-slug: bc-geographical-names
description: Geographical names are more than labels on maps and road signs. They
  can reveal patterns of settlement, exploration and migration, and mirror outside
  influences to our history - aspects of the heritage and promise of an area that
  might otherwise be overlooked or forgotten by visitors and later generations.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Changes
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/changes/master/_listings/bc-geographical-names/apis.md
specificationVersion: "0.14"
apis:
- name: BC Geographical Names - Search for names with metadata changes in a given
    period
  x-api-slug: nameschanges-get
  description: Search for information about geographical names which have changed
    most recently within a specified time window.  Changes may include status cupdates
    and metadata corrections.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/british-columbia.png
  humanURL: https://apps.gov.bc.ca/pub/bcgnws/
  baseURL: https://apps.gov.bc.ca//pub/bcgnws
  tags: Geo, Geography, Locations, API Provider, Profiles, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/changes/master/_listings/bc-geographical-names/nameschanges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/changes/master/_listings/bc-geographical-names/nameschanges-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://bbc.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bc.geographical.names.stack.network
- type: x-website
  url: https://apps.gov.bc.ca/pub/bcgnws/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---