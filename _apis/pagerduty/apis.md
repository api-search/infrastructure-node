---
name: PagerDuty
description: >-
  Datadog is an observability service for cloud-scale applications, providing
  monitoring of servers, databases, tools, and services, through a SaaS-based
  data analytics platform. 
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/pagerduty.yml
created: 2023/11/22
modified: 2023/11/22
specificationVersion: '0.16'
tags: []
apis:
  - name: PagerDuty API
    description: >-
      The Datadog API is an HTTP REST API. The API uses resource-oriented URLs
      to call the API, uses status codes to indicate the success or failure of
      requests, returns JSON from all requests, and uses standard HTTP response
      codes. Use the Datadog API to access the Datadog platform
      programmatically.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.pagerduty.com/api-reference
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.pagerduty.com/api-reference
      - type: Postman Collection
        url: properties/pagerduty-openapi-original.yml
    overlays: []
    aid: pagerduty:pagerduty-api
common:
  - type: Portal
    url: https://developer.pagerduty.com/
  - type: Libraries
    url: https://developer.pagerduty.com/docs/ZG9jOjExMDI5NTg2-api-client-libraries
  - type: Knowledgebase
    url: https://support.pagerduty.com/
  - type: Support
    url: https://www.pagerduty.com/contact-us/#contact-support   
  - type: Twitch
    url: https://www.twitch.tv/pagerduty
  - type: Podcast
    url: https://www.pageittothelimit.com/
  - type: GitHub Org
    url: https://github.com/pagerduty
  - type: LinkedIn Live
    url: https://www.linkedin.com/company/pagerduty/events/  
  - type: Rate Limits
    url: https://developer.pagerduty.com/docs/72d3b724589e3-rest-api-rate-limits
  - type: Errors
    url: https://developer.pagerduty.com/docs/cd9f75aa7ac93-errors       
  - type: Filtering
    url: https://developer.pagerduty.com/docs/ZG9jOjExMDI5NTU2-filtering 
  - type: Versioning
    url: https://developer.pagerduty.com/docs/ZG9jOjExMDI5NTUy-versioning 
  - type: Sorting
    url: https://developer.pagerduty.com/docs/ZG9jOjExMDI5NTU3-sorting 
  - type: Pagination
    url: https://developer.pagerduty.com/docs/ZG9jOjExMDI5NTU4-pagination   
  - type: Developer Agreement
    url: https://developer.pagerduty.com/docs/ZG9jOjExMDI5NTg0-pager-duty-developer-agreement      
  - type: Client Libraries
    url: https://developer.pagerduty.com/docs/ZG9jOjExMDI5NTg2-api-client-libraries                                            
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: pagerduty
---