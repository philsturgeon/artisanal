---
name: Datadog
description: >-
  Datadog is an observability service for cloud-scale applications, providing
  monitoring of servers, databases, tools, and services, through a SaaS-based
  data analytics platform. 
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/datadog.yml
created: 2023/11/22
modified: 2023/11/22
specificationVersion: '0.16'
tags: []
apis:
  - name: Datadog API
    description: >-
      The Datadog API is an HTTP REST API. The API uses resource-oriented URLs
      to call the API, uses status codes to indicate the success or failure of
      requests, returns JSON from all requests, and uses standard HTTP response
      codes. Use the Datadog API to access the Datadog platform
      programmatically.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.datadoghq.com/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.datadoghq.com/api/latest/
      - type: Postman Collection
        url: >-
          https://god.gw.postman.com/run-collection/20651290-809b13c1-4ada-46c1-af65-ab276c434068
    overlays: []
    aid: datadog:datadog-api
common:
  - type: Authentication
    url: https://docs.datadoghq.com/api/latest/authentication/
  - type: Blog
    url: https://www.datadoghq.com/blog/
  - type: Login
    url: https://app.datadoghq.com/account/login
  - type: Plans
    url: https://www.datadoghq.com/pricing/
  - type: Support
    url: https://www.datadoghq.com/support/
  - type: Privacy
    url: https://www.datadoghq.com/privacy/
  - type: Learning Center
    url: >-
      https://learn.datadoghq.com/?_gl=1*q2qaic*_ga*MTEzODQ5NzQzOC4xNjk4NzA5NDM1*_ga_KN80RDFSQK*MTcwMDY5NTk5OC4yLjEuMTcwMDY5NjI3OS4wLjAuMA..*_fplc*clhCUTloMEhBR1UxSG9YNWhrMUhDUmc0OVljaEhHUGZVOEYlMkZ1TU5SM3VHWFV1QUd6T3gzVFRiOVVrU2U3dVdvOFY0TEFuaUt6aUslMkZlN1pZNDV0ZXhMRXJWUzVuYk9XanoxWWJoUXQzUUZONkZQYlFpNyUyQiUyQiUyRkpHWGFNd1R2ZyUzRCUzRA..
  - type: Support
    url: https://www.datadoghq.com/support/
  - type: Terms of Service
    url: https://www.datadoghq.com/legal/terms/
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: datadog
---