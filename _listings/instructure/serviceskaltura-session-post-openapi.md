---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Utility APIs Start Kaltura session
  description: Start kaltura session.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /services/kaltura:
    get:
      summary: Get Kaltura config
      description: Get kaltura config.
      operationId: get-kaltura-config
      x-api-path-slug: serviceskaltura-get
      responses:
        200:
          description: OK
      tags:
      - Services
      - Kaltura
  /services/kaltura_session:
    post:
      summary: Start Kaltura session
      description: Start kaltura session.
      operationId: start-kaltura-session
      x-api-path-slug: serviceskaltura-session-post
      responses:
        200:
          description: OK
      tags:
      - Services
      - Kaltura
      - Session
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