---
name: Okta
description: >-
  Okta connects any person with any application on any device. It's an
  enterprise-grade, identity management service, built for the cloud, but
  compatible with many on-premises applications. With Okta, IT can manage any
  employee's access to any application or device. Okta runs in the cloud, on a
  secure, reliable, extensively audited platform, which integrates deeply with
  on-premises applications, directories, and identity management systems.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/okta.yml
created: 2023/11/20
modified: 2023/11/20
specificationVersion: '0.16'
tags: []
apis:
  - name: Okta API
    description: >-
      The Core Okta API is the primary way that apps and services interact with
      Okta. You can use it to implement basic auth functions such as signing in
      your users and programmatically managing your Okta objects.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.okta.com/docs/reference/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.okta.com/docs/reference/
      - type: OpenAPI
        url: https://github.com/okta/okta-management-openapi-spec
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://github.com/okta/okta-management-openapi-spec-openapi-search.yml
    aid: okta:okta-api
common:
  - type: Concepts
    url: https://developer.okta.com/docs/concepts/
  - type: Guides
    url: https://developer.okta.com/docs/guides/
  - type: SDKs
    url: https://developer.okta.com/docs/guides/
  - type: Change Log
    url: https://developer.okta.com/docs/release-notes/
  - type: Login
    url: https://developer.okta.com/login/
  - type: Sign Up
    url: https://developer.okta.com/signup/
  - type: Blog
    url: https://developer.okta.com/blog/
  - type: Plans
    url: https://www.okta.com/pricing/
  - type: Forum
    url: https://devforum.okta.com/
  - type: Terms of Service
    url: https://developer.okta.com/terms/
  - type: Privacy Policy
    url: >-
      https://www.okta.com/privacy-policy/?_gl=1*7t4881*_gcl_au*ODA3ODU4ODM3LjE2OTg3MDkwODg.*_ga*NDIzNDM3NzgxLjE2OTg3MDkwODg.*_ga_QKMSDV5369*MTcwMDUzMTM5NS4yLjEuMTcwMDUzMTY2Ni4xOC4wLjA.&_ga=2.30811191.940567833.1700531395-423437781.1698709088
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: okta
---