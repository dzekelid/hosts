---
swagger: "2.0"
x-collection-name: Meetup
x-complete: 0
info:
  title: Meetup Event Hosts
  description: Returns the list of hosts for a given event
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
      x-api-path-slug: urlnameeventsevent-idcommentscomment-idlikes-post
      responses:
        200:
          description: OK
      tags:
      - Events
      - Hosts
  /:urlname/events/:event_id/hosts:
    get:
      summary: Event Hosts
      description: Returns the list of hosts for a given event
      operationId: hosts
      x-api-path-slug: urlnameeventsevent-idhosts-get
      parameters:
      - in: query
        name: fields
        description: A comma-delimited list of optional fields to append to the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Photos
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