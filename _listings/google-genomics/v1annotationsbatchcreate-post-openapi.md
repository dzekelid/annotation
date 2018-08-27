---
swagger: "2.0"
x-collection-name: Google Genomics
x-complete: 0
info:
  title: Google Genomics API Create Batch Annotation
  description: |-
    Creates one or more new annotations atomically. All annotations must
    belong to the same annotation set. Caller must have WRITE
    permission for this annotation set. For optimal performance, batch
    positionally adjacent annotations together.

    If the request has a systemic issue, such as an attempt to write to
    an inaccessible annotation set, the entire RPC will fail accordingly. For
    lesser data issues, when possible an error will be isolated to the
    corresponding batch entry in the response; the remaining well formed
    annotations will be created normally.

    For details on the requirements for each individual annotation resource,
    see
    CreateAnnotation.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: genomics.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/annotations:batchCreate:
    post:
      summary: Create Batch Annotation
      description: |-
        Creates one or more new annotations atomically. All annotations must
        belong to the same annotation set. Caller must have WRITE
        permission for this annotation set. For optimal performance, batch
        positionally adjacent annotations together.

        If the request has a systemic issue, such as an attempt to write to
        an inaccessible annotation set, the entire RPC will fail accordingly. For
        lesser data issues, when possible an error will be isolated to the
        corresponding batch entry in the response; the remaining well formed
        annotations will be created normally.

        For details on the requirements for each individual annotation resource,
        see
        CreateAnnotation.
      operationId: genomics.annotations.batchCreate
      x-api-path-slug: v1annotationsbatchcreate-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Annotation
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