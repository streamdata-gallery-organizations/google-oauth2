---
swagger: "2.0"
x-collection-name: Google OAuth2
x-complete: 0
info:
  title: Google OAuth2 APIs Get User Info
  description: Get the user information for this session.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oauth2/v2/certs:
    get:
      summary: Get Certificate
      description: Get the certification for this session.
      operationId: oauth2.getCertForOpenIdConnect
      x-api-path-slug: oauth2v2certs-get
      responses:
        200:
          description: OK
      tags:
      - Certificate
      - Certfication
  /oauth2/v2/tokeninfo:
    post:
      summary: Get Token Info
      description: Get the token information for this session.
      operationId: oauth2.tokeninfo
      x-api-path-slug: oauth2v2tokeninfo-post
      parameters:
      - in: query
        name: access_token
      - in: query
        name: id_token
      - in: query
        name: token_handle
      responses:
        200:
          description: OK
      tags:
      - Token
  /oauth2/v2/userinfo:
    get:
      summary: Get User Info
      description: Get the user information for this session.
      operationId: oauth2.userinfo.get
      x-api-path-slug: oauth2v2userinfo-get
      responses:
        200:
          description: OK
      tags:
      - User
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