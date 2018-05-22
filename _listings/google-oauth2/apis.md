---
name: Google OAuth2
x-slug: google-oauth2
description: Google APIs use the OAuth 2.0 protocol for authentication and authorization.
  Google supports common OAuth 2.0 scenarios such as those for web server, installed,
  and client-side applications. To begin, obtain OAuth 2.0 client credentials from
  the Google API Console. Then your client application requests an access token from
  the Google Authorization Server, extracts a token from the response, and sends the
  token to the Google API that you want to access. For an interactive demonstration
  of using OAuth 2.0 with Google (including the option to use your own client credentials),
  experiment with the OAuth 2.0 Playground.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-OAuth@2x.png
x-kinRank: "9"
x-alexaRank: ""
tags: Google OAuth2
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-oauth2/master/_listings/google-oauth2/apis.md
specificationVersion: "0.14"
apis:
- name: Google OAuth2 APIs Get Certificate
  x-api-slug: google-oauth2-apis
  description: Get the certification for this session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-OAuth@2x.png
  humanURL: https://developers.google.com/identity/protocols/OAuth2
  baseURL: ://www.googleapis.com////oauth2/v2/certs
  tags: Certificate, Certfication
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-oauth2/master/_listings/google-oauth2/oauth2v2certs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-oauth2/master/_listings/google-oauth2/oauth2v2certs-get-openapi.md
- name: Google OAuth2 APIs Get Token Info
  x-api-slug: google-oauth2-apis
  description: Get the token information for this session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-OAuth@2x.png
  humanURL: https://developers.google.com/identity/protocols/OAuth2
  baseURL: ://www.googleapis.com////oauth2/v2/tokeninfo
  tags: Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-oauth2/master/_listings/google-oauth2/oauth2v2tokeninfo-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-oauth2/master/_listings/google-oauth2/oauth2v2tokeninfo-post-openapi.md
- name: Google OAuth2 APIs Get User Info
  x-api-slug: google-oauth2-apis
  description: Get the user information for this session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-OAuth@2x.png
  humanURL: https://developers.google.com/identity/protocols/OAuth2
  baseURL: ://www.googleapis.com////oauth2/v2/userinfo
  tags: User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-oauth2/master/_listings/google-oauth2/oauth2v2userinfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-oauth2/master/_listings/google-oauth2/oauth2v2userinfo-get-openapi.md
- name: Google OAuth2 APIs Get Me
  x-api-slug: google-oauth2-apis
  description: Get the currently authenticated user for this session.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-OAuth@2x.png
  humanURL: https://developers.google.com/identity/protocols/OAuth2
  baseURL: ://www.googleapis.com////userinfo/v2/me
  tags: User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-oauth2/master/_listings/google-oauth2/userinfov2me-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-oauth2/master/_listings/google-oauth2/userinfov2me-get-openapi.md
- name: Google OAuth2 APIs
  x-api-slug: google-oauth2-apis
  description: Google APIs use the OAuth 2.0 protocol for authentication and authorization.
    Google supports common OAuth 2.0 scenarios such as those for web server, installed,
    and client-side applications. To begin, obtain OAuth 2.0 client credentials from
    the Google API Console. Then your client application requests an access token
    from the Google Authorization Server, extracts a token from the response, and
    sends the token to the Google API that you want to access. For an interactive
    demonstration of using OAuth 2.0 with Google (including the option to use your
    own client credentials), experiment with the OAuth 2.0 Playground.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-OAuth@2x.png
  humanURL: https://developers.google.com/identity/protocols/OAuth2
  baseURL: ://www.googleapis.com//
  tags: Google OAuth2
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-oauth2/master/_listings/google-oauth2/openapi.md
x-common:
- type: x-website
  url: https://developers.google.com/identity/protocols/OAuth2
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---