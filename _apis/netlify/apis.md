---
name: Netlify
description: >-
  Netlify is a remote-first cloud computing company that offers a development
  platform that includes build, deploy, and serverless backend services for web
  applications and dynamic websites.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/netlify.yml
created: 2023/11/14
modified: 2023/11/14
specificationVersion: '0.16'
tags: []
apis:
  - name: Netlify API
    description: >-
      Netlify is a hosting service for the programmable web. It understands your
      documents and provides an API to handle atomic deploys of websites, manage
      form submissions, inject JavaScript snippets, and much more. This is a
      REST-style API that uses JSON for serialization and OAuth 2 for
      authentication.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.netlify.com/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://open-api.netlify.com/
      - type: OpenAPI
        url: https://open-api.netlify.com/6dac5474-6daf-41e6-8a14-6d9bcb8aca52
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://open-api.netlify.com/6dac5474-6daf-41e6-8a14-6d9bcb8aca52-openapi-search.yml
    aid: netlify:netlify-api
common:
  - type: Terms of Service
    url: https://www.netlify.com/legal/terms-of-use/
  - type: Blog
    url: https://netlify.com/blog/
  - type: Change Log
    url: https://netlify.com/changelog/
  - type: Forum
    url: https://answers.netlify.com/
  - type: Support
    url: https://www.netlify.com/support/
  - type: CLI
    url: https://www.netlify.com/support/
  - type: Privacy Policy
    url: https://www.netlify.com/privacy/
  - type: Sign Up
    url: https://app.netlify.com/signup
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: netlify
---