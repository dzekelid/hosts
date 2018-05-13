---
swagger: "2.0"
info:
  title: Meetup Event Comment Like
  description: Like a given event comment
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:urlname/events/:event_id/comments/:comment_id/likes:
    post:
      summary: Event Comment Like
      description: Like a given event comment
      operationId: comments
      responses:
        200:
          description: OK
      tags:
      - events
      - hosts
definitions: []
x-collection-name: Meetup
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