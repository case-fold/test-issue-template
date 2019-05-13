---
name: New Fastly Service
about: Use this template when requesting a brand new Fastly service
title: Create new service for [your app name]
labels: ''
assignees: ''

---

## Your email

## Public hostname(s) that will need to resolve to Fastly.  Include the envs
- myapp.nytimes.com
- myapp.stg.nytimes.com
- myapp.dev.nytimes.com

## Backend public hostname that Fastly will point to for each env.
- origin.nyt.net
- origin.stg.nyt.net
- origin.dev.nyt.net

## Healthcheck URL - it must be unauthenticated endpoint
- /.status

## Test URLs - please provide some URLs to validate your routes are functioning

## Response headers
Be sure you understand that cache settings are controlled by response headers from the origin, so make sure you review your `cache-control: ` header values are set properly.  For more information, refer to this doc (provide link).
