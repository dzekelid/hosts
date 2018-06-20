---
swagger: "2.0"
x-collection-name: Meetup
x-complete: 1
info:
  title: Meetup
  description: the-meetup-api-provides-simple-restful-http-and-streaming-interfaces-for-exploring-and-interacting-meetup-platform-from-your-own-apps--the-api-is-a-set-of-core-methods-and-a-common-request-format--these-are-combined-to-form-a-url-that-returns-the-information-you-want--
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
---